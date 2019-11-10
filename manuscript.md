---
author-meta:
- Olga Borisovna Botvinnik
- Venkata Naga Pranathi Vemuri
- Phoenix Aja Logan
date-meta: '2019-11-10'
keywords:
- comparative transcriptomics
- single-cell RNA-seq
- k-mer
- hashing
- MinHash
lang: en-US
title: Smashing single cells into $k$-mer sketches
...






<small><em>
This manuscript
([permalink](https://czbiohub.github.io/primate-brain-organoid-paper/v/7f4a9ad793349dc6a218ce149b3a6bc68ce73890/))
was automatically generated
from [czbiohub/primate-brain-organoid-paper@7f4a9ad](https://github.com/czbiohub/primate-brain-organoid-paper/tree/7f4a9ad793349dc6a218ce149b3a6bc68ce73890)
on November 10, 2019.
</em></small>

## Authors



+ **Olga Borisovna Botvinnik**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-4412-7970](https://orcid.org/0000-0003-4412-7970)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [olgabot](https://github.com/olgabot)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [olgabot](https://twitter.com/olgabot)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>

+ **Venkata Naga Pranathi Vemuri**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-5748-9594](https://orcid.org/0000-0002-5748-9594)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [pranathivemuri](https://github.com/pranathivemuri)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [pranuvemuri](https://twitter.com/pranuvemuri)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>

+ **Phoenix Aja Logan**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-4581-0552](https://orcid.org/0000-0003-4581-0552)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [phoenixAja](https://github.com/phoenixAja)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [phoenixlogan](https://twitter.com/phoenixlogan)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>



## Abstract


Single-cell RNA-sequencing is a powerful technology for identifying novel and known cell types, however its power is limited to organisms with well-annotated genomes.
We demonstrate the utility of using annotation-agnostic methods which quantify cell-cell similarity using $k$-mer profiles.
We benchmark a few methods and demonstrate the utility of converting cell types from mouse to human and back, and compare to using purely 1:1 mapped orthologous genes.


## Introduction  {.page_break_before}

There are a predicted 8.7 million Eukaryotic species on earth [@OkFljXKC], yet only 14% (1,233,500) have been catalogued and 0.001% (9,449) have genomes deposited in the National Center for Biotechnology Information Genome Assembly [@16wL4sfFU#!/overview/].
And yet, the genome sequence is not enough.
To truly understand the diversity of life on this planet, we need to determine not just the DNA blueprints of life, but understand the instantiation of the DNA, the cell types of the species.
While sequencing DNA gives a quantitative measure of the nucleotide differences, it does not inform the functional strategies that change with DNA sequence.
As new species can be defined by a new cell type.
For example, the existence of a single cell type, the Cnidocyte [@18WcUBCuN], a stinging cell of a single-celled biological weapon, defines the phylum Cnidaria.
Thus, entire clades, not only species, can be defined by the introduction of an additional cell type or state.

Novel organizations of existing cell states can also define cell types.
For example, the development of genitalia in amniotes, while using similar cell types, ultimately uses a different physical organization of cell types to generate genitalia in mammals compared to reptiles [@rn7vCWvt]

Determining common gene ancestry ("orthology") is a difficult problem.
Many approaches exist [@LkrS4xXB; @46R7aU4N].

Determining common ancestry of cell types ("orthologous cell types") [@ogAGO9KH; @wdzgXUGy] is an additional difficult problem.
Comparative transcriptomics begins with finding a common feature set for embedding molecular profiles across divergent species into a common space.
Many researchers take the approach of using one-to-one orthologous genes [Cite: brawand2011, CCA, LIGER, Scanorama, basically all the single cell "alignment" packages], others use clusters of orthologous groups [@1tMQTfnh], others map reads onto a common genome derived from whole-genome alignment [cite: recent primate brain paper from Barbara Treutlein], or map onto native genomes [@y7xGipW5] and re-annotate using a tool such as Comparative Annotation Toolkit [@1BnfHjbCA].

$k$-mers have been proposed for comparing single cells [@wtk13QGK] as they are a fast, simple way to create cell-cell similarities.
However, the work so far has focused on using annotated organisms and not cross-species analyses.


## Methods

Methods go here.

### Experimental

#### Primate brain organoid protocols

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

#### Single-cell capture of primate brain organoids

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

#### Long read library prep

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].


#### Short read library prep

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

#### Sequencing

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

### Computational

#### $k$-mer comparison of orthologous genes

We used ENSEMBL version 97.
We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

#### Extraction of putative coding reads from RNA-seq

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].

#### $bam2fasta$ conversion

The `.bam` file generated by the Drop-seq [@11pOKbwng] pipeline for the different primates in this study are in the order of 6-12 GB. 
The Drop-seq `.bam` files so obtained can attribute to few limitations as discussed below.
Firstly, loading them in memory all at once would require a lot of RAM depending on how the program will allocate memory for different data typed tags in the `.bam` file. 
Secondly, if Drop-seq data is not accompanied by a barcodes file to filter the `.bam` file on, it would mean we would have to recursively go through the alignments in the bam file and deduce alignments with higher quality and combine sequences with already exisiting barcodes. 
This would need a look up dictionary to be updated as it loops through the alignments in the `.bam` file and would search the look up dictionary as it updates the barcodes. 
In conclusion, this is a very memory intensive process that seemed to fail on even machines with 2TB RAM.


Hence we propose a method that could work on a computer with lesser RAM and not cause computer hangups. 
We released an open source pypi package for the same [@1EPeNLOEg].
The package contains solution for the above discussed problem by sharding the `.bam` file into chunks of smaller `.bam` files and stores them in the machine's temporary folder, e.g. `/tmp`.
The chunk size of the `.bam` file is a tunable parameter that can be accessed with `--line_count`; by default it is 1500 alignment lines.
This process is done serially by iterating through the alignments in the `.bam` file, using `pysam`, a Python wrapper around samtools [@IPc8cy7s].
Now we employ a MapReduce [@xE3EYmck] approach to the temporary `.bam` files to obtain all the reads per cell barcode in a `.fasta` file.
In the "Map" step, we distribute the computation i.e parsing the barcode, determining the quality of the read, and if alignment is not duplicated, in parallel across multiple processes on the temporary shards of `.bam` files. 
These bam shards create temporary `.fasta` files that contain for each read: the cell barcode, unique molecular identifier (UMI), and the aligned sequence.
There might be a cell barcode that would be present in different chunks of these sharded `.bam` files.
As a result we would have multiple temporary `.fasta` files for the same barcodes.
We implemented a method to find the unique barcodes based on these temporary `.fasta` file names and then assigning each of the unique barcodes all the temporary barcode `.fasta` files created by different `.bam` shards in a dictionary. 
In the "Reduce" step, we concatenate of strings of temporary `.fasta` file names, hence its memory consumption is less than it would be if appending to a list. 
These temporary `.fasta` files are then combined to one `.fasta` file per barcode by concatenating all the sequences obtained from different `.fasta` files. 
The concatenation of all sequences for each of the unique barcodes is also then parallelized to use multiple processes.
For each of the cell barcodes, there is an option to obtain valid cell barcodes, based on the UMI count per cell barcode.
For our datasets we have set the minimum number of UMIs per cell barcode to 1000, a common threshold. 
The minimum number of UMIs per cell barcode can be customized with the flag `--min-umi-per-barcode`.
The computational resources and time taken for processing is as shown in Table [@tbl:bam2fasta-runtime-ram].


|  Primate  | BAM file size(GB)  | Time(hrs)| RAM(GB) | Processes |
| :-------- | :------------------| :--------| :-------| :---------|
| Human     | 12                 | 7        | 16      | 32        |
| Orangutan | 9                  | 4        | 16      | 32        |
| Chimp     | 9                  | 4        | 16      | 32        |

Table: Human primate species bam file here is from a brain organoid for human {#tbl:bam2fasta-runtime-ram}

This method primarily gives us time performance improvement. 
It reduces time from days or just process running out of memory to hours. 
Depending on the size of `.bam` file and resources of the cluster/computer it can be further reduced. 

Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].


## Results

To determine whether short segments of sequences could detect gene orthologues, we $k$-merized orthologous genes derived from the ENSEMBL version 97 [@lBlqrqAO] COMPARA database [@j0y6s0kf] (Figure [@fig:fig1]).
We compared human protein sequences to orthologous chimpanzee, mouse, (orangutan, bonobo, gorilla, macaque, opossum, platypus, chicken) protein sequences, as these are species used in [@fBCZ87Cf].
As a background, we randomly chose 10 non-orthologous genes relative to the human gene.
In addition to $k$-merizing the protein-coding sequence, we also re-encoded the protein-coding sequence into Dayhoff [@66KDHtpG] and hydrophobic-polar encodings [@1GiMcbPLs], show in Table [@tbl:sequence-encodings].


|  Amino acid                    | Property              | Dayhoff | Hydrophobic-polar (HP) |
| :----------------------------- | :-------------------- | :------ | :--------------------- |
| C                              | Sulfur polymerization | a       | p                      |
| A, G, P, S, T                  | Small                 | b       | A, G, P: h             |
|                                |                       |         | S,T: p                 |
| D, E, N, Q                     | Acid and amide        | c       | p                      |
| H, K, R                        | Basic                 | d       | p                      |
| I, L, M, V                     | Hydrophobic           | e       | h                      |
| F, W, Y                        | Aromatic              | f       | h                      |

Table: Dayhoff and hydrophobic-polar encodings are a reduced amino acid
alphabet allowing for permissive cross-species sequence comparisons. For
example, the amino acid sequence `SASHAFIERCE` would be Dayhoff-encoded
to `bbbdbfecdac`, and HP-encoded to `phpphhhpppp`. {#tbl:sequence-encodings}



![Figure 1.](images/figure1.svg){#fig:fig1}


We found that, consistent with previous knowledge, that 1:1 orthologues had higher $k$-mer similarities as determined by the Jaccard Index.


Additionally, more recently diverged genes had higher $k$-mer similarity as well.


![Figure 2.](images/figure2.svg){#fig:fig2}


### Outlines

#### Figure 1 outline

- Kmers can approximate orthologies
  - Jaccard similarity of orthologues is higher than non-orthologues
  - Benchmarking using https://orthology.benchmarkservice.org/cgi-bin/gateway.pl
  - Finding orthologues
    - Gold standard
      - ENSEMBL COMPARA
      - Quest for Orthologs consortium, Altenhoff, A. M., Boeckmann, B., Capella-Gutierrez, S., Dalquen, D. A., DeLuca, T., et al. (2016). Standardized benchmarking in the quest for orthologs. Nature Methods, 13(5), 425–430. http://doi.org/10.1038/nmeth.3830 [@LkrS4xXB]
    - Orthologous groups/Conserved Domain Database [@bkF0801R]
- Kmers can find correct reading from of RNA-seq reads
  - Human peptides → human RNAseq
  - Human peptides → chimp RNAseq
  - Human peptides → mouse RNAseq
- Kmers can find only transcription factor reads of TFs from RNA-seq reads
  - Human TFs → human RNAseq
  - Human TFs → chimp RNAseq
  - Human TFs → mouse RNAseq
- Overview of kmermaid pipeline
  - Comparison of tissue across species
    - Partition reads to coding/noncoding bins
    - MinHash the Dayhoff-encoded coding sequences
    - Jaccard similarity on the MinHashes


#### Figure 2 outline

References for Primate Brain development

- Florio, M., Heide, M., Pinson, A., Brandl, H., Albert, M., Winkler, S., et al. (2018). Evolution and cell-type specificity of human-specific genes preferentially expressed in progenitors of fetal neocortex. eLife, 7, D635. http://doi.org/10.7554/eLife.32332 [@nbBjh1sL]
- Mazin, P. V., Jiang, X., Fu, N., Han, D., Guo, M., Gelfand, M. S., & Khaitovich, P. (2018). Conservation, evolution, and regulation of splicing during prefrontal cortex development in humans, chimpanzees, and macaques. Rna, 24(4), 585–596. http://doi.org/10.1261/rna.064931.117 [@G7TPi9Sb]
- Xiong, J., Jiang, X., Ditsiou, A., Gao, Y., Sun, J., Lowenstein, E. D., et al. (2018). Predominant patterns of splicing evolution on human, chimpanzee and macaque evolutionary lineages. Human Molecular Genetics, 27(8), 1474–1485. http://doi.org/10.1093/hmg/ddy058 [@n7a1Lgjf]

##### No need for 1:1 orthology

Gene expression evolution through duplications

- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@1DcTxE8Z3]
- Thornton, J. W., & DeSalle, R. (2000). Gene family evolution and homology: genomics meets phylogenetics. Annual Review of Genomics and Human Genetics, 1(1), 41–73. http://doi.org/10.1146/annurev.genom.1.1.41 [@uQLS9NYU]
- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@1DcTxE8Z3]

Taxa-restricted genes

- Human-specific genes in fetal neocortex
Florio, M., Heide, M., Pinson, A., Brandl, H., Albert, M., Winkler, S., et al. (2018). Evolution and cell-type specificity of human-specific genes preferentially expressed in progenitors of fetal neocortex. eLife, 7, D635. http://doi.org/10.7554/eLife.32332 [@nbBjh1sL]
- Insects -- Santos, M. E., Le Bouquin, A., Crumière, A. J. J., & Khila, A. (2017). Taxon-restricted genes at the origin of a novel trait allowing access to a new environment. Science, 358(6361), 386–390. http://doi.org/10.1126/science.aan2748 [@lJHQuvIH]

Don't need to normalize gene expression counts since we just have presence/absence

Full transcript analyses

- Brain Organoid -- Droplet + PacBio data

Correlated evolution of celltypes?

- Liang, C., Musser, J. M., Cloutier, A., Prum, R. O., & Wagner, G. P. (2018). Pervasive Correlated Evolution in Gene Expression Shapes Cell and Tissue Type Transcriptomes. Genome Biology and Evolution, 10(2), 538–552. http://doi.org/10.1093/gbe/evy016 [@FTv2KYrZ]

Cell type homology

- Thornton, J. W., & DeSalle, R. (2000). Gene family evolution and homology: genomics meets phylogenetics. Annual Review of Genomics and Human Genetics, 1(1), 41–73. http://doi.org/10.1146/annurev.genom.1.1.41 [@uQLS9NYU]
- Tschopp, P., & Tabin, C. J. (2017). Deep homology in the age of next-generation sequencing. Philosophical Transactions of the Royal Society B: Biological Sciences, 372(1713), 20150475–8. http://doi.org/10.1098/rstb.2015.0475 [@hdRo8a7z]
- Hejnol, A., & Lowe, C. J. (2015). Embracing the comparative approach: how robust phylogenies and broader developmental sampling impacts the understanding of nervous system evolution. Philosophical Transactions of the Royal Society B: Biological Sciences, 370(1684), 20150045–16. http://doi.org/10.1098/rstb.2015.0045 [@1GRtpoh49]
- Santos, M. E., Le Bouquin, A., Crumière, A. J. J., & Khila, A. (2017). Taxon-restricted genes at the origin of a novel trait allowing access to a new environment. Science, 358(6361), 386–390. http://doi.org/10.1126/science.aan2748 [@lJHQuvIH]
- Mammalian decidual cell

Cell type evolution

- Erkenbrack, E. M., Maziarz, J. D., Griffith, O. W., Liang, C., Chavan, A. R., Nnamani, M. C., & Wagner, G. P. (2018). The mammalian decidual cell evolved from a cellular stress response. PLOS Biology, 16(8), e2005594–27. http://doi.org/10.1371/journal.pbio.2005594 [@8cGr6TE]

#### Figure 3 -- long evolutionary distances with HP encoding?

Metazoan body plan formation

- Early development in Cnidarians/Hydra [@17wCcfFdm; @w8ZV4B95]
- sponges and others [@w8ZV4B95]
- planaria [@EtU319GV; @1FnDb3m4L],
- drosophila [@1EawBz4WT]
- zebrafish [@JWLQWOpG; @4frea8Pi; @yrCPHI0k],
- mouse [@kTAtFDTa]

#### Figure 4 -- What features are k-mers able to pick up that mapping doesn't?

- Which reads are found to have coding features but didn’t map to the genome?
- Do these features map to novel genes or gene fusions?


## Discussion

Conclusions and future directions go here.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
