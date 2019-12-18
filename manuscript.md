---
author-meta:
- Olga Borisovna Botvinnik
- Venkata Naga Pranathi Vemuri
- Phoenix Aja Logan
- Saba Nafees
date-meta: '2019-12-18'
keywords:
- comparative transcriptomics
- single-cell RNA-seq
- k-mer
- hashing
- MinHash
lang: en-US
title: 'INCOMPLETE DRAFT: Smashing single cells into $k$-mer sketches'
...






<small><em>
This manuscript
([permalink](https://czbiohub.github.io/orthology-free-comparative-transcriptomics-paper/v/1a7e25adc2204082bff3695b40d3b351fa4f510d/))
was automatically generated
from [czbiohub/orthology-free-comparative-transcriptomics-paper@1a7e25a](https://github.com/czbiohub/orthology-free-comparative-transcriptomics-paper/tree/1a7e25adc2204082bff3695b40d3b351fa4f510d)
on December 18, 2019.
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

+ **Saba Nafees**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-3292-7703](https://orcid.org/0000-0002-3292-7703)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [snafees](https://github.com/snafees)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [sabanafeesTTU](https://twitter.com/sabanafeesTTU)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub; Department of Biological Sciences, Texas Tech University; Department of Mathematics & Statistics, Texas Tech University
  </small>



## Abstract


Single-cell RNA-sequencing is a powerful technology for identifying novel and known cell types.
However, the task of identifying new and novel cell types across species is nontrivial, especially when one or more of the species have poorly annotated genomes.
Thus, there is an unmet need to quantitatively compare single-cell transcriptomes across species, without the need for a reference genome.
To this end, we have developed a genome-agnostic method to compare molecular profiles using a lossy encoding on $k$-mers from putative protein-coding RNA-seq reads.
We benchmark the annotation-agnostic methods on a bulk comparative transcriptomic dataset consisting of nine species and six tissues, showing that we can recapitulate the results as using only reads mapping to 1:1 orthologs of protein-coding genes, and we are able to resolve ... which can only be seen by using the reference-free $k$-mer method.
We then show that $k$-mers can also be used for comparing transcriptomes built from long read sequencing, by comparing the cell-cell similarity nearest neighbor graphs built on $k$-mers from short reads and long reads from the same cells in a primate brain organoid system.
We find that using $k$-mers on short reads has the advantage of resolving ... in comparison to using read counts from 1:1 gene orthologs, while long reads provide additional information in the form of ...
Using $k$-mers, we were able to resolve cell types X in the primate brain organoid dataset, which was hidden using read counts alone.
Thus, we have show the reference-free methods using the $k$-mers from single cells is a novel, annotation-agnostic method for comparing cells across species that is capable of identifying cell states unique to a particular organism, helping to build the cell type evolution tree of life.


## Introduction  {.page_break_before}

There are a predicted 8.7 million Eukaryotic species on earth [@OkFljXKC], yet only 14% (1,233,500) have been catalogued and 0.000002% (200/8,700,000 = 2.3e-08) have genomes present in ENSEMBL Assemblies (as of ENSEMBL 98 -- September 2019 release) [@1DzGnZnWP].
And yet, the genome sequence is not enough.
To truly understand the diversity of life on this planet, we need to determine not just the DNA blueprints of life, but understand the instantiation of the DNA, the cell types of the species.
While sequencing DNA gives a quantitative measure of the nucleotide differences, it does not inform the functional strategies that change from DNA modifications due to speciation events .
As new species can be defined by a new cell type.
For example, the existence of a single cell type, the stinging cell called a "Cnidocyte" [@6KNCoGHt], a single-celled biological weapon, defines the phylum Cnidaria.
Thus, entire clades, not only species, can be defined by the introduction of an additional cell type or state.
However, it is unclear how many examples there are of this, and how it is possible to find cell types that are unique to one species.
Thus, we aim to develop a computational method to compare cell types across species that is reference-agnostic and can find cell types that are novel and present in only one organism.

Organizations of existing cell states can also define novel organismal structures.
For example, different physical organizations of similar cell types generate different genitalia in amniotes when comparing mammals to reptiles [@rn7vCWvt]

Determining common gene ancestry ("orthology") is a difficult problem.

Many approaches exist, reviewed by [@LkrS4xXB; @4rmQKNc6; @4JPXrWM5].
Generally, the approaches are structured in this way: (1) find orthologous groups of genes, (2) build gene trees, (3) build species trees, and (4) assign orthologs, as described in a recent approach (Orthofinder) [@46R7aU4N].
In this approach, we are not interested in exactly reconstructing the species or gene trees, but rather inferring function based on cell type transcriptomes.
Instead of exactly building the gene trees, we subset the protein-coding sequences into peptide words, and re-encode to lossy peptide encodings.


Determining common ancestry of cell types ("orthologous cell types") [@ogAGO9KH; @wdzgXUGy] is an additional difficult problem.
Comparative transcriptomics begins with finding a common feature set for embedding molecular profiles across divergent species into a common space.
Many researchers take the approach of using one-to-one orthologous genes [@fBCZ87Cf; @lNBJZodk; @MaZsghuS, @OekvE5up; @3W4a486t; @B45xrKOO; @vxLmcytb, @ZVsAu3NP], others use clusters of orthologous groups [@1tMQTfnh], others map reads onto a common genome derived from whole-genome alignment [@2c3LiMz9; @mtOZyMZw], or map onto native genomes [@y7xGipW5] and re-annotate using a tool such as Comparative Annotation Toolkit [@1BnfHjbCA].

Annotating one dataset's cell types from another can be performed using random forest models trained on the original dataset [@dnJT32Dx], using correlation between cell gene expression profiles as in Cell BLAST [@m2Yvtcb8], locality-sensitive hashing of bit vectors of gene expression as in CellFishing.jl [@1CdDldcJr], or using a cell type hierarchy as in Garnett [@szbeiEEU] and OnClass [@dB7c447D].

$k$-mers have been proposed for comparing single cells [@wtk13QGK] as they are a fast, simple way to create cell-cell similarities.
$k$-mers have also been used for orthologous gene detection [@Rqlso7kk]
However, the work so far has focused on using annotated organisms and not cross-species analyses.

Reduced amino acid alphabets have been previously used to speed up database searches [@16Kv6RIe3; @sZoryWIB], protein fold prediction [@f5u3dDtc; @Aq7zYbOg], and homology recognition [@QMYjnr6l].
We aim to find "orthologous reads" across species' transcriptomes. 
By representing each species' transcriptome as the set of $k$-mers, we can unbiasedly compare transcriptomes in an orthologous space without the need for knowing the orthologous genes ahead of time, or even the need for a reference genome. 
Additionally, we do not need to reduce the signal to only the genes with a 1:1 orthologous match.


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

Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@LkrS4xXB].
Biorxiv example: [@46R7aU4N].
Multiple citations per line example: [@LkrS4xXB; @46R7aU4N].


## Results

### Figure 1 -- $k$-mers are sufficient to detect orthologous genes

To determine whether short segments of sequences could detect gene orthologues, we $k$-merized orthologous genes derived from the ENSEMBL version 97 [@lBlqrqAO] COMPARA database [@j0y6s0kf] (Figure [@fig:fig1]).
We compared human protein sequences to orthologous chimpanzee, mouse, (orangutan, bonobo, gorilla, macaque, opossum, platypus, chicken) protein sequences, as these are species used in [@fBCZ87Cf].
As a background, we randomly chose 10 non-orthologous genes relative to the human gene.
In addition to $k$-merizing the protein-coding sequence, we also re-encoded the protein-coding sequence into a six-letter Dayhoff alphabet [@66KDHtpG], a nine-letter encoding [@Rqlso7kk], and a two-letter hydrophobic-polar encodings [@1GiMcbPLs; @E2Kp7kA0], show in Table [@tbl:sequence-encodings].

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

$k$-mer size may be tuned to find an "optimal" length of protein domains across the tree of life. Protein domain lengths follow a power law distribution where proteins with more domains, have shorter domains, whereas proteins with fewer domains, have fewer but longer domains [@1pZXVQ7r; @cQaAUgCD].


![**A.** Overview of $k$-mer comparison of orthologous genes. The protein-coding sequence of each pair of known orthologs is $k$-merized, potentially encoded as Dayhoff or Hydrophobic polar, and then the Jaccard index (the intersection divided by the union) is computed on the $k$-mers. **B.** Jaccard similarity of orthologous genes in Dayhoff-encoded $k$-mer space relative to humans in eight species. $x$-axis, $k$-mer size; $y$-axis, Jaccard index. **C.** ](images/figure1.svg){#fig:fig1 width="100%"}

We found that, consistent with previous knowledge, that 1:1 orthologues had higher $k$-mer similarities as determined by the Jaccard Index. This approach is similar to SwiftOrtho [@Rqlso7kk], a k-mer based orthology relationship finder.

Additionally, more recently diverged genes had higher $k$-mer similarity as well.

#### Outline

- Kmers can approximate orthologies
  - Jaccard similarity of orthologues is higher than non-orthologues
  - Benchmarking using https://orthology.benchmarkservice.org/cgi-bin/gateway.pl
  - Finding orthologues
    - Gold standard
      - ENSEMBL COMPARA
      - Quest for Orthologs consortium, Altenhoff, A. M., Boeckmann, B., Capella-Gutierrez, S., Dalquen, D. A., DeLuca, T., et al. (2016). Standardized benchmarking in the quest for orthologs. Nature Methods, 13(5), 425–430. http://doi.org/10.1038/nmeth.3830 [@LkrS4xXB]
    - Orthologous groups/Conserved Domain Database [@bkF0801R]


### Figure 2 -- $k$-mers from lossily-encoded putative protein-coding reads faithfully pull out reads from protein-coding genes within amniotes

![Figure 2.](images/figure2.svg){#fig:fig2 width="100%"}

- Overview of kmermaid pipeline
  - Comparison of tissue across species
    - Partition reads to coding/noncoding bins
    - MinHash the Dayhoff-encoded coding sequences
    - Jaccard similarity on the MinHashes
- Which reads are found to have coding features but didn’t map to the genome?
- Do these features map to novel genes or gene fusions?
- Kmers can find correct reading from of RNA-seq reads
  - Human peptides → human, chimp, bonobo, orangutan, gorilla, macaque, mouse, opossum, playtpus, chicken RNAseq from Brawand2011 data
- Comparison to other methods: RNASamba [@AtPPptbH]

### Figure 3 -- $k$-mers can pull out only reads from transcription factors and Amniotes can be compared on the MinHashes of their protein-coding sequences

![Figure 3.](images/figure3.svg){#fig:fig3 width="100%"}

- Kmers can find only transcription factor reads of TFs from RNA-seq reads
  - Human peptides → human, chimp, bonobo, orangutan, gorilla, macaque, mouse, opossum, playtpus, chicken RNAseq from Brawand2011 data


### Figure 4 -- $k$-mers can compare short and long read datasets in primate brain organoids

![**A.** Overview of experimental system. Poly-A RNA molecules from single cells from primate brain organoids were captured using the Dolomite system, where molecule received a cell barcode and molecular barcode, was reverse transcribed and primed for full-length cDNA. Then the library was split for sequencing on the Illumina or PacBio platforms. For the Illumina platform, the library was first sheared to be compatible with the platform. **B**. UMAP of short read gene counts from Human (left), Chimp (middle), and Orangutan (right) organoids. **C.** UMAP of short read MinHashes with ksize=33, dayhoff encoding and a log2sketchsize=14. **D**. UMAP of long read MinHashes with ksize=33, dayhoff encoding, andl log2sketchsize=14. **E.** Examples of short reads with ambiguous coding sequence resolved by long reads. **F.** UMAP on short-read gene counts of 1:1 orthologous transcription factor genes across all species. **G.** UMAP on short-read MinHashes of all k-mers that match human transcription factor protein-coding peptide sequences. **H.** UMAP on long-read MinHashes of all k-mers that match human transcription factor protein-coding peptide sequences.](images/figure4.svg){#fig:fig4 width="100%"}


References for Primate Brain development

- Florio, M., Heide, M., Pinson, A., Brandl, H., Albert, M., Winkler, S., et al. (2018). Evolution and cell-type specificity of human-specific genes preferentially expressed in progenitors of fetal neocortex. eLife, 7, D635. http://doi.org/10.7554/eLife.32332 [@nbBjh1sL]
- Mazin, P. V., Jiang, X., Fu, N., Han, D., Guo, M., Gelfand, M. S., & Khaitovich, P. (2018). Conservation, evolution, and regulation of splicing during prefrontal cortex development in humans, chimpanzees, and macaques. Rna, 24(4), 585–596. http://doi.org/10.1261/rna.064931.117 [@G7TPi9Sb]
- Xiong, J., Jiang, X., Ditsiou, A., Gao, Y., Sun, J., Lowenstein, E. D., et al. (2018). Predominant patterns of splicing evolution on human, chimpanzee and macaque evolutionary lineages. Human Molecular Genetics, 27(8), 1474–1485. http://doi.org/10.1093/hmg/ddy058 [@n7a1Lgjf]


## Discussion

Conclusions and future directions go here.



### Some potential references

Gene expression evolution through duplications

- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@1DcTxE8Z3]
- Thornton, J. W., & DeSalle, R. (2000). Gene family evolution and homology: genomics meets phylogenetics. Annual Review of Genomics and Human Genetics, 1(1), 41–73. http://doi.org/10.1146/annurev.genom.1.1.41 [@uQLS9NYU]
- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@1DcTxE8Z3]

Taxa-restricted genes

- Human-specific genes in fetal neocortex
Florio, M., Heide, M., Pinson, A., Brandl, H., Albert, M., Winkler, S., et al. (2018). Evolution and cell-type specificity of human-specific genes preferentially expressed in progenitors of fetal neocortex. eLife, 7, D635. http://doi.org/10.7554/eLife.32332 [@nbBjh1sL]
- Insects -- Santos, M. E., Le Bouquin, A., Crumière, A. J. J., & Khila, A. (2017). Taxon-restricted genes at the origin of a novel trait allowing access to a new environment. Science, 358(6361), 386–390. http://doi.org/10.1126/science.aan2748 [@lJHQuvIH]


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


## Supplemental Methods




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


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
