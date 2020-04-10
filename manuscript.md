---
author-meta:
- Olga Borisovna Botvinnik
- Venkata Naga Pranathi Vemuri
- N. Tessa Pierce
- Phoenix Aja Logan
- Saba Nafees
- Jim Karkanias
bibliography:
- content/manual-references.json
date-meta: '2020-04-10'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="INCOMPLETE DRAFT: Identification of *de novo* orthologous genes from comparative single-cell RNA-seq transcriptomics" />

  <meta name="citation_title" content="INCOMPLETE DRAFT: Identification of *de novo* orthologous genes from comparative single-cell RNA-seq transcriptomics" />

  <meta property="og:title" content="INCOMPLETE DRAFT: Identification of *de novo* orthologous genes from comparative single-cell RNA-seq transcriptomics" />

  <meta property="twitter:title" content="INCOMPLETE DRAFT: Identification of *de novo* orthologous genes from comparative single-cell RNA-seq transcriptomics" />

  <meta name="dc.date" content="2020-04-10" />

  <meta name="citation_publication_date" content="2020-04-10" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Olga Borisovna Botvinnik" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_orcid" content="0000-0003-4412-7970" />

  <meta name="twitter:creator" content="@olgabot" />

  <meta name="citation_author" content="Venkata Naga Pranathi Vemuri" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_orcid" content="0000-0002-5748-9594" />

  <meta name="twitter:creator" content="@pranuvemuri" />

  <meta name="citation_author" content="N. Tessa Pierce" />

  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />

  <meta name="citation_author_orcid" content="0000-0002-2942-5331" />

  <meta name="twitter:creator" content="@saltyscientist" />

  <meta name="citation_author" content="Phoenix Aja Logan" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_orcid" content="0000-0003-4581-0552" />

  <meta name="twitter:creator" content="@phoenixlogan" />

  <meta name="citation_author" content="Saba Nafees" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_institution" content="Department of Biological Sciences, Texas Tech University" />

  <meta name="citation_author_institution" content="Department of Mathematics &amp; Statistics, Texas Tech University" />

  <meta name="citation_author_orcid" content="0000-0002-3292-7703" />

  <meta name="twitter:creator" content="@sabanafeesTTU" />

  <meta name="citation_author" content="Jim Karkanias" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_orcid" content="0000-0002-8057-6055" />

  <meta name="twitter:creator" content="@jkarkanias" />

  <link rel="canonical" href="https://czbiohub.github.io/de-novo-orthology-paper/" />

  <meta property="og:url" content="https://czbiohub.github.io/de-novo-orthology-paper/" />

  <meta property="twitter:url" content="https://czbiohub.github.io/de-novo-orthology-paper/" />

  <meta name="citation_fulltext_html_url" content="https://czbiohub.github.io/de-novo-orthology-paper/" />

  <meta name="citation_pdf_url" content="https://czbiohub.github.io/de-novo-orthology-paper/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://czbiohub.github.io/de-novo-orthology-paper/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://czbiohub.github.io/de-novo-orthology-paper/v/b2fb17459a1242218c6a64de81fad411b9a60ae5/" />

  <meta name="manubot_html_url_versioned" content="https://czbiohub.github.io/de-novo-orthology-paper/v/b2fb17459a1242218c6a64de81fad411b9a60ae5/" />

  <meta name="manubot_pdf_url_versioned" content="https://czbiohub.github.io/de-novo-orthology-paper/v/b2fb17459a1242218c6a64de81fad411b9a60ae5/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- comparative transcriptomics
- single-cell RNA-seq
- k-mer
- hashing
- MinHash
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: 'INCOMPLETE DRAFT: Identification of *de novo* orthologous genes from comparative single-cell RNA-seq transcriptomics'
...






<small><em>
This manuscript
([permalink](https://czbiohub.github.io/de-novo-orthology-paper/v/b2fb17459a1242218c6a64de81fad411b9a60ae5/))
was automatically generated
from [czbiohub/de-novo-orthology-paper@b2fb174](https://github.com/czbiohub/de-novo-orthology-paper/tree/b2fb17459a1242218c6a64de81fad411b9a60ae5)
on April 10, 2020.
</em></small>

## Authors



+ **Olga Borisovna Botvinnik** ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-4412-7970](https://orcid.org/0000-0003-4412-7970)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [olgabot](https://github.com/olgabot)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [olgabot](https://twitter.com/olgabot)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>

+ **Venkata Naga Pranathi Vemuri** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-5748-9594](https://orcid.org/0000-0002-5748-9594)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [pranathivemuri](https://github.com/pranathivemuri)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [pranuvemuri](https://twitter.com/pranuvemuri)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>

+ **N. Tessa Pierce** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-2942-5331](https://orcid.org/0000-0002-2942-5331)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [bluegenes](https://github.com/bluegenes)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [saltyscientist](https://twitter.com/saltyscientist)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
     · Funded by NSF 1711984
  </small>

+ **Phoenix Aja Logan** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-4581-0552](https://orcid.org/0000-0003-4581-0552)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [phoenixAja](https://github.com/phoenixAja)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [phoenixlogan](https://twitter.com/phoenixlogan)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>

+ **Saba Nafees** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-3292-7703](https://orcid.org/0000-0002-3292-7703)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [snafees](https://github.com/snafees)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [sabanafeesTTU](https://twitter.com/sabanafeesTTU)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub; Department of Biological Sciences, Texas Tech University; Department of Mathematics & Statistics, Texas Tech University
  </small>

+ **Jim Karkanias** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-8057-6055](https://orcid.org/0000-0002-8057-6055)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [jkensai](https://github.com/jkensai)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [jkarkanias](https://twitter.com/jkarkanias)<br>
  <small>
     Data Sciences Platform, Chan Zuckerberg Biohub
  </small>



## Abstract

We introduce `sencha`, a novel computational method for translating RNA-seq reads to putative protein sequence.
As the direct assignment of protein-coding sequence skips both traditional alignment and gene orthology assignment it can a) be applied to transcriptomes from organisms with no or poorly annotated genomes, and b) identify putative functions of protein sequences contributing to shared cell types.
Thus, we can identify orthologous cell types while discovering *de novo* orthologous genes across species.
For widespread accessibility and usage, we implemented `sencha` into two distinct Nextflow pipelines following software best practices such as testing and continuous integration: (1) `nf-core/kmermaid` to compare translated transcriptomes across divergent species, and (2) `czbiohub/nf-predictorthologs` to infer functions of translated sequences.
Using these pipelines, we were able to align transcriptomes and discover *de novo* homologous genes across species from a variety of divergence times: bulk RNA-seq transcriptomes across Amniotes (divergence ~312 millions of years ago), mouse single-cell RNA-seq with *Botryllus schlosseri* bulk RNA-seq, an early chordate (divergence ~684 millions of years ago), and Bilateria developmental atlases (divergence ~824 millions of years ago).
By enabling analyses across divergent species' transcriptomes in an orthology-, genome- and gene annotation-agnostic manner, `sencha` illustrates the potential of non-model organisms in building the cell type evolutionary tree of life.


## Introduction

Single-cell RNA-sequencing is a powerful technology for identifying cell types in a variety of species.
However, the task of identifying even known cell types in species with poorly annotated genomes is nontrivial, as 99.999% of the predicted 8.7 million Eukaryotic species on Earth have no submitted genome assembly [@doi:10.1371/journal.pbio.1001127; @url:https://www.ncbi.nlm.nih.gov/genome/browse#!/overview/] and identifying orthologous genes, which remains an open problem [@doi:10.1038/nrg.2016.127; @doi:10.1146/annurev-cellbio-100616-060818].
Thus, there is an unmet need to quantitatively compare single-cell transcriptomes across species, without the need for orthologous gene mapping, gene annotations, or a reference genome.
Short, $k$-long sequence substrings, or $k$-mers, have been proposed for clustering single cells [@url:https://doi.org/10.1101/723833] and here we implemented $k$-mers from putatitvely translated RNA-seq reads with reduced amino acid alphabets [@doi:10.1093/bioinformatics/btp164 @doi:10.1093/gigascience/giz118 @doi:10.1093/bioinformatics/10.4.453; @10.1186/1471-2105-12-159; @doi:10.1093/protein/13.3.149; @doi:10.1093/bioinformatics/btp164; @doi:10.1093/nar/gkh180], to find shared cell types across species, and further identify *de novo* orthologous genes by querying the predicted protein sequences to a reference database.
This method relies solely on divergence time between species, which we show can be estimated from RNA-seq nucleotide $k$-mers (Supplemental Figure [@sfig:sfig1]).

We benchmark the genome-agnostic method on the Quest for Orthologs Opisthokonta dataset, showing that $k$-mers from reduced amino acid alphabets are sufficient to estimate orthology.
Using human amino acid sequences, we show that one can extract putative protein-coding reads from 35 Opisthokonta species in Quest for Orthologs, and present the best $k$-mer size and alphabet for different divergence times.

We first apply this method on a bulk comparative transcriptomic dataset consisting of nine amniote species and six tissues [@doi:10.1038/nature10532], showing that we achieve similar clustering results as using only reads mapping to 1:1 orthologs or Hierarchical Orthologous Groups (HOGs) [@doi:10.1371/journal.pone.0053786; @doi:10.1093/bib/bbr034; @doi:10.1093/bioinformatics/btu492] of protein-coding genes, but are able to resolve ... which can only be seen by using the $k$-mer method.
We further demonstrate the utility of this method by comparing transcriptomes from organisms diverged by approximately 676 million years [@url:http://timetree.org/]:  a single-cell atlas of a model organism, mouse from *Tabula Muris Senis* [@url:https://www.biorxiv.org/content/10.1101/661728v2], and bulk RNA-seq from *Botryllus schlosseri* [@doi:10.1038/s41586-018-0783-x], a colonial tunicate which exhibits cell populations similar to the myeloid immune lineage.
Across this evolutionary distance, only XX 1:1 orthologous genes exist as found by ... and XX HOGs via orthologous matrix (OMA) [@doi:10.7717/peerj.6231; @doi:10.1093/bioinformatics/btx229]
We show that the myeloid-like cells from *B. schlosseri* not only cluster with the myeloid immune cells from *Tabula Muris Senis*, we also find *de novo* orthologous genes, such as ...
We find that using $k$-mers has the advantage of resolving ... in comparison to using read counts from 1:1 gene orthologs.
Using $k$-mers, we were able to resolve cell types ... , which was hidden using read counts alone.
Thus, we have shown the reference-free method using the $k$-mers from single cells is a novel, annotation-agnostic method for comparing cells across species that is capable of identifying cell states unique to a particular organism, helping to build the cell type evolutionary tree of life.


## Results

![
Figure 1.
**A.** Overview of `nf-core/kmermaid` pipeline to compare DNA/RNA/protein sequences on k-mer content.
1. If input is bam, extract per-cell sequences using `bam2fasta percell`.
2. Predict amino acid sequence of each RNA-seq read using `sencha translate`.
3. Randomly subsample amino acid k-mers via MinHash using `sourmash sketch`.
4. Compare all k-mer sketches to one another using `sourmash compare` to compute cell-cell Jaccard similarities.
5. Build sequence bloom tree using `sourmash index`.
6. Build k-nearest neighbor graph using sequence bloom tree.
7. Build UMAP off of KNN.
**B.** Overview of `czbiohub/nf-predictorthologs` pipeline to query putative function of protein sequences.
1. If input is bam, must also have a convert bam reads to raw fastq files using the `samtools fastq` subcommand (samtools version 1.9). If input is fastqs, go directly to second step.
2. Trim adapters, poly-A, polyG using the `fastp` tool.
3. Predict protein-coding sequence using khtools extract_coding, using conservative UniProt/SwissProt manually curated database as examples of known protein-coding sequences, for most stringent definition of protein-coding.
4. Query predicted protein in permissive NCBI RefSeq non-redundant protein database for most complete search query.
](images/SVG/figure1.svg){#fig:fig1 width="100%"}



To determine whether short segments of sequences could detect gene orthologues, we $k$-merized orthologous genes derived from the ENSEMBL version 97 [@doi:10.1093/nar/gkx1098] COMPARA database [@doi:10.1093/database/bav096] (Figure [@fig:fig1]).
We compared human protein sequences to orthologous chimpanzee, mouse, (orangutan, bonobo, gorilla, macaque, opossum, platypus, chicken) protein sequences, as these are species used in [@doi:10.1038/nature10532].
In addition to $k$-merizing the protein-coding sequence, we also re-encoded the protein-coding sequence into a six-letter Dayhoff alphabet [@raw:dayhoff1969atlas], a nine-letter encoding [@doi:10.1093/gigascience/giz118], and a two-letter hydrophobic-polar encodings [@raw:phillips2012physical; @doi:10.1021/bi00327a032], show in Table [@tbl:sequence-encodings].




<!-- We found that, consistent with previous knowledge, that 1:1 orthologues had higher $k$-mer similarities as determined by the Jaccard Index. This approach is similar to SwiftOrtho [@doi:10.1093/gigascience/giz118], a k-mer based orthology relationship finder.

Additionally, more recently diverged genes had higher $k$-mer similarity as well.

Across tissues of the same time from the Brawand 2011 [@doi:10.1038/nature10532] dataset, we extracted protein-coding sequences, generated dayhoff signatures of k-mer size length 12, extracted hashes and thus k-mers shared by samples from the same tissue, went back to the original protein sequence, and searched NCBI RefSeq NR for potential proteins.
For each sample, we observed that shared k-mers appeared in 1:1 orthologous genes XX% of the time 1:many orthologs YY% of the time, many:many orthologs ZZ% of the time, in genes not known to be orthologs AA% of the time, in unannotated regions AA% of the time, in multimapped reads BB% of the time, and in unmapped reads CC% of the time.
Overall, we observed XX de novo orthologs in each tissue.
We removed genes that were already known to be orthologous. -->

![Figure 2.](images/SVG/figure2.svg){#fig:fig2 width="100%"}


To identify novel orthologs among annotated species related by ~300 million years, we first applied these methods on a seminal comparative transcriptomics dataset of human,  chimpanzee, mouse, orangutan, bonobo, gorilla, macaque, opossum, platypus, and chicken [@doi:10.1038/nature10532]. We found ..

To identify common cell types from a known cell atlas to a less well-annotated species related by ~700 million years, we applied these methods to a mouse single-cell RNA-seq atlas, *Tabula Muris Senis* [@url:https://www.biorxiv.org/content/10.1101/661728v2], and bulk RNA-seq from *Botryllus schlosseri* [@doi:10.1038/s41586-018-0783-x]. We found that the signal for myeloid cell types is strongly conserved when using a protein k-mer size of XX and a XX amino acid encoding. We also find ..

To identify common developmental trajectories across >1000 million years of divergence, we merged transcriptomes from *Hydra* [@doi:10.1126/science.aav9314], zebrafish [@doi:10.1126/science.aar4362], and mouse [@doi:10.1038/s41586-019-0969-x]. We demonstrate that the transcriptional signal from ectoderm, mesoderm, and endoderm are conserved when using a protein k-mer size of XX and an XX amino acid encoding.



## Discussion

`kmermaid` implements the concept of lightweight orthology assignment using k-mers to the problem of cross-species RNA-seq analyses and achieves unprecedented speed of analysis. By removing the orthology inference step, `kmermaid` opens up the possibilty of finding shared and divergent tissue and cell types across a broad range of species, paving the way for evolutionary analyses of cell types across species. `kmermaid` can be used in *de novo* setting for non-model organisms, finding similar cell types within an organism, or finding similar cell types relative to a reference organism, without the need for a reference genome or transcriptome. The memory usage of `kmermaid` is quite low, using only 50MB for extracting coding sequences and 50MB for assigning protein k-mer signatures. As the number of RNA-seq datasets, especially single-cell RNA-seq datasets continues to grow, we expect `kmermaid` to be widely used for identifying cell types in non-model organisms.

In summary, we developed a method to identify both known cell types in a non-model organism using a reference atlas from another organism, without the need for a genome or gene annotation from the non-model organism.
This method can be used to combine single-cell cell atlases from well-annotated,  model organisms, with sequencing data from poorly annotated non-model organisms, to directly find homologous cell types and orthologous genes.
By eliminating read alignment and orthologous gene mapping, `kmermaid` enables comparison of transcriptomes of the remaining 99.999% Eukaryotic species on Earth without submitted genome assemblies, with the cell atlases of a handful of model organisms to identify shared and novel cell types, and *de novo* identify orthologous genes.
By identifying homologous cell types across a broad variety of species, we come closer to an understanding of the evolution of genes, cells, and thus life itself.

`kmermaid` is free and open-source software and is available as Supplementary Data and at http://github.com/czbiohub/kmermaid and as a scalable Nextflow workflow at http://github.com/nf-core/nf-kmermaid.


## Outline

- Kmers can approximate orthologies
  - Jaccard similarity of orthologues is higher than non-orthologues
  - Benchmarking using https://orthology.benchmarkservice.org/cgi-bin/gateway.pl
  - Finding orthologues
    - Gold standard
      - ENSEMBL COMPARA
      - Quest for Orthologs consortium, Altenhoff, A. M., Boeckmann, B., Capella-Gutierrez, S., Dalquen, D. A., DeLuca, T., et al. (2016). Standardized benchmarking in the quest for orthologs. Nature Methods, 13(5), 425–430. http://doi.org/10.1038/nmeth.3830 [@doi:10.1038/nmeth.3830]
    - Orthologous groups/Conserved Domain Database [@url:https://www.ebi.ac.uk/miriam/main/collections/MIR:00000119]


<!-- ## Figure 2 -- $k$-mers from lossily-encoded putative protein-coding reads faithfully pull out reads from protein-coding genes within amniotes -->


- Overview of kmermaid pipeline
  - Comparison of tissue across species
    - Partition reads to coding/noncoding bins
    - MinHash the Dayhoff-encoded coding sequences
    - Jaccard similarity on the MinHashes
- Which reads are found to have coding features but didn’t map to the genome?
- Do these features map to novel genes or gene fusions?
- Kmers can find correct reading from of RNA-seq reads
  - Human peptides → human, chimp, bonobo, orangutan, gorilla, macaque, mouse, opossum, playtpus, chicken RNAseq from Brawand2011 data
- Comparison to other methods: RNASamba [@doi:10.1101/620880]

<!-- ### Figure 3 -- $k$-mers can pull out only reads from transcription factors and Amniotes can be compared on the MinHashes of their protein-coding sequences -->

<!-- ![Figure 3.](images/figure3.svg){#fig:fig3 width="100%"} -->

- Kmers can find only transcription factor reads of TFs from RNA-seq reads
  - Human peptides → human, chimp, bonobo, orangutan, gorilla, macaque, mouse, opossum, playtpus, chicken RNAseq from Brawand2011 data

### Some potential references

Gene expression evolution through duplications

- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@doi:10.1093/molbev/msp242]
- Thornton, J. W., & DeSalle, R. (2000). Gene family evolution and homology: genomics meets phylogenetics. Annual Review of Genomics and Human Genetics, 1(1), 41–73. http://doi.org/10.1146/annurev.genom.1.1.41 [@doi:10.1146/annurev.genom.1.1.41]
- Farre, D., & Alba, M. M. (2010). Heterogeneous Patterns of Gene-Expression Diversification in Mammalian Gene Duplicates. Molecular Biology and Evolution, 27(2), 325–335. http://doi.org/10.1093/molbev/msp242 [@doi:10.1093/molbev/msp242]

Taxa-restricted genes

- Human-specific genes in fetal neocortex
Florio, M., Heide, M., Pinson, A., Brandl, H., Albert, M., Winkler, S., et al. (2018). Evolution and cell-type specificity of human-specific genes preferentially expressed in progenitors of fetal neocortex. eLife, 7, D635. http://doi.org/10.7554/eLife.32332 [@doi:10.7554/eLife.32332]
- Insects -- Santos, M. E., Le Bouquin, A., Crumière, A. J. J., & Khila, A. (2017). Taxon-restricted genes at the origin of a novel trait allowing access to a new environment. Science, 358(6361), 386–390. http://doi.org/10.1126/science.aan2748 [@doi:10.1126/science.aan2748]


Correlated evolution of celltypes?

- Liang, C., Musser, J. M., Cloutier, A., Prum, R. O., & Wagner, G. P. (2018). Pervasive Correlated Evolution in Gene Expression Shapes Cell and Tissue Type Transcriptomes. Genome Biology and Evolution, 10(2), 538–552. http://doi.org/10.1093/gbe/evy016 [@doi:10.1093/gbe/evy016]

Cell type homology

- Thornton, J. W., & DeSalle, R. (2000). Gene family evolution and homology: genomics meets phylogenetics. Annual Review of Genomics and Human Genetics, 1(1), 41–73. http://doi.org/10.1146/annurev.genom.1.1.41 [@doi:10.1146/annurev.genom.1.1.41]
- Tschopp, P., & Tabin, C. J. (2017). Deep homology in the age of next-generation sequencing. Philosophical Transactions of the Royal Society B: Biological Sciences, 372(1713), 20150475–8. http://doi.org/10.1098/rstb.2015.0475 [@doi:10.1098/rstb.2015.0475]
- Hejnol, A., & Lowe, C. J. (2015). Embracing the comparative approach: how robust phylogenies and broader developmental sampling impacts the understanding of nervous system evolution. Philosophical Transactions of the Royal Society B: Biological Sciences, 370(1684), 20150045–16. http://doi.org/10.1098/rstb.2015.0045 [@doi:10.1098/rstb.2015.0045]
- Santos, M. E., Le Bouquin, A., Crumière, A. J. J., & Khila, A. (2017). Taxon-restricted genes at the origin of a novel trait allowing access to a new environment. Science, 358(6361), 386–390. http://doi.org/10.1126/science.aan2748 [@doi:10.1126/science.aan2748]
- Mammalian decidual cell

Cell type evolution

- Erkenbrack, E. M., Maziarz, J. D., Griffith, O. W., Liang, C., Chavan, A. R., Nnamani, M. C., & Wagner, G. P. (2018). The mammalian decidual cell evolved from a cellular stress response. PLOS Biology, 16(8), e2005594–27. http://doi.org/10.1371/journal.pbio.2005594 [@doi:10.1371/journal.pbio.2005594]

<!-- # Discussion -->


## Online Methods

<!-- This is just a placeholder to separate the supplemental methods from the rest of the paper.
All remaining supplemental sections should fall under this, meaning they need to be formatted
with heading 3 with three hashes: `###` -->




### Implementation

#### Reduced alphabets

At the core of `sencha` is the ability to cheaply compare sequences using $k$-mers.
As $k$-mers are very brittle to substitutions and thus to compare across species, one must allow for minor base substitutions that still maintain similar chemical or structural properties.
A reduced alphabet can encode useful information into a smaller alphabet space, and enable sequence comparisons across a broader variety of species than the original alphabet alone.


##### Reduced amino acid alphabets

Reduced amino acid alphabets have been useful for over 50 years [@raw:dayhoff1969atlas] in finding related protein sequences [@doi:10.1093/bioinformatics/btp164; @doi:10.1093/bioinformatics/10.4.453; @doi:10.1186/1471-2105-12-159; @doi:10.1093/protein/13.3.149; @doi:10.1093/nar/gkh180].
Recently, a reduced amino acid alphabet (specifically, `aa9` below) combined with $k$-mers were used to find homologous protein-coding sequences [@doi:10.1093/gigascience/giz118].
We build on this concept by enabling prediction of protein-coding sequences from RNA-seq reads, and by enabling users to perform a parameter sweep in an all-by-all comparison to identify putative homologs using a variety of alphabet metrics.


###### Dayhoff and `HP` alphabets

| Amino acid              | Property              | Dayhoff | Hydrophobic-polar (HP)  |
|:------------------------|:----------------------|:--------|:------------------------|
| `C`                     | Sulfur polymerization | `a`     | `p`                     |
| `A`, `G`, `P`, `S`, `T` | Small                 | `b`     | `AGP`: `h`<br>`ST`: `p` |
| `D`, `E`, `N`, `Q`      | Acid and amide        | `c`     | `p`                     |
| `H`, `K`, `R`           | Basic                 | `d`     | `p`                     |
| `I`, `L`, `M`, `V`      | Hydrophobic           | `e`     | `h`                     |
| `F`, `W`, `Y`           | Aromatic              | `f`     | `h`                     |



Table: Dayhoff and hydrophobic-polar encodings are a reduced amino acid
alphabet allowing for permissive cross-species sequence comparisons. For
example, the amino acid sequence `SASHAFIERCE` would be Dayhoff-encoded
to `bbbdbfecdac`, and HP-encoded to `phpphhhpppp`, as below. {#tbl:sequence-encodings}


```
protein20: SASHAFIERCE
dayhoff6:  bbbdbfecdac
hp2:       phpphhhpppp
```


###### All implemented alphabets (with citations, not as nicely organized)
<!-- Copied this google spreadsheet https://docs.google.com/spreadsheets/d/1RDuQD0aRyv-FnQJbjRosHEJV85_9BNrzmmvgFRQSgN8/edit#gid=0 into https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/, reformatted with https://atom.io/packages/markdown-table-formatter -->

[NOTE: maybe this should go into the supplementary? The main alphabets that have been successful for me are dayhoff and HP]

| Citation                                                              | Alphabet   | Amino acid groups                                                               |
|:-----------------------------------------------------|:-------------------|:-----------------------------------------------------------------------------------------|
| Phillips, R., *et al*. (2012). [@raw:phillips2012physical]            | hp2        | `AFGILMPVWY` `CDEHKNQRST`                                                       |
| Peterson, E. L., *et al*. (2009) [@doi:10.1093/bioinformatics/btp164] | gbmr4      | `G` `ADKERNTSQ` `YFLIVMCWH` `P`                                                 |
| Dayhoff, M. O., & Eck, R. V. (1968). [@raw:dayhoff1969atlas]          | dayhoff6   | `AGPST` `HRK` `DENQ` `FWY` `ILMV` `C`                                           |
| This paper                                                            | botvinnik8 | `AG` `DE` `RK` `NQ` `ST` `FY` `LIV` `CMWHP`                                     |
| Hu, X., & Friedberg, I. (2019). [@doi:10.1093/gigascience/giz118]     | aa9        | `G` `AST` `KR` `EQ` `DN` `CFILMVY` `W` `H` `P`                                  |
| Peterson, E. L., *et al*. (2009) [@doi:10.1093/bioinformatics/btp164] | sdm12      | `G` `A` `D` `KER` `N` `TSQ` `YF` `LIVM` `C` `W` `H` `P`                         |
| Peterson, E. L., *et al*. (2009) [@doi:10.1093/bioinformatics/btp164] | hsdm17     | `G` `A` `D` `KE` `R` `N` `T` `S` `Q` `Y` `F` `LIV` `M` `C` `W` `H` `P`          |
| Dayhoff, M. O., & Eck, R. V. (1968). [@raw:dayhoff1969atlas]          | protein20  | `G` `A` `D` `E` `K` `R` `N` `T` `S` `Q` `Y` `F` `L` `I` `V` `M` `C` `W` `H` `P` |



##### Reduced nucleotide alphabets

The IUPAC degenerate nucleotide code [@url:https://www.qmul.ac.uk/sbcs/iubmb/misc/naseq.html] includes several two-letter codes for the original 4-letter nucleobase alphabet.
The first, Weak/Strong, indicates the strength of the hydrogen bond across the double strand.
The bond of adenine to thymine has two hydrogen bonds, making it weak; and the bond of guanine to cytosine has three hydrogen bonds, making it 50% stronger.
The second, Purine/Pyrimidine, encodes the ring size of the nucleobase, where Adenine and Guanine both have larger Purine double rings, while Cytosine and Thymine/Uracil have smaller Pyrimidine rings.
The third, Amino/Keto, designates the main functional group of the ring, where Adenine and Cytosine both have an Amino group, while Guanine and Thymine/Uracil both have a Keto group.

<!-- This spreadsheet:https://docs.google.com/spreadsheets/d/1RDuQD0aRyv-FnQJbjRosHEJV85_9BNrzmmvgFRQSgN8/edit#gid=104831627 was copied into this formatter: https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/ -->

| Nucleotide | Hydrogen Bonding | Ring type      | Ring functional group | Nucleobase chemical structure                                                                                                                                   |
|:-----------|:-----------------|:---------------|:----------------------|:------------------------------------------------|
| A          | Weak (W)         | Purine (R)     | Amino (M)             | ![Adenine chemical structure](https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Adenine.svg/120px-Adenine.svg.png)                                      |
| C          | Strong (S)       | Pyrimidine (Y) | Amino (M)             | ![Cytosine chemical structure](https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/Cytosine_chemical_structure.png/120px-Cytosine_chemical_structure.png) |
| G          | Strong (S)       | Purine (R)     | Keto (K)              | ![Guanine chemical structure](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Guanin.svg/150px-Guanin.svg.png)                                        |
| T          | Weak (W)         | Pyrimidine (Y) | Keto (K)              | ![Thymine chemical structure](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ab/Thymine_skeletal.svg/120px-Thymine_skeletal.svg.png)                    |
| U          | Weak (W)         | Pyrimidine (Y) | Keto (K)              | ![Uracil chemical structure](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Uracil.svg/120px-Uracil.svg.png)                                         |
Thus, the nucleotide string `GATTACA` would be re-encoded into the following:

```
Nucleotide:        GATTACA
Weak/Strong:       SWWWWSW
Purine/Pyrimidine: RRYYRYR
Functional group:  KMKKMMM
```

#### `sencha translate`


![Overview of `sencha translate` **A.** First, each read is translated into all six possible protein-coding translation frames. Next, reading frames with stop codons are eliminated. Each protein-coding frame is $k$-merized, then the fraction of $k$-mers which appear in the known protein-coding database is computed. Frames which contain a fraction of coding frames exceeding the threshold are inferred to be putatively protein-coding. **B.** Worked example of an RNA-seq read with a single putatitive reading frame. **C.** Worked example of an RNA-seq read with multiple reading frames, and a `UCSC` genome browser shot of the read showing that both reading frames are present in the annotation.](images/SVG/supplemental_figure1.svg){#sfig1:supplemental_figure1 tag="supplemental_figure1" width="100%"}


##### Set Jaccard threshold of `translate` by controlling false positive rate of protein-coding prediction

To set a threshold of the minimum Jaccard overlap between a translated read's frame and the reference proteome, the most statistically principled way is to control the false positive rate of predicing a protein-coding read.

###### Probability of random $k$-mers from a read

If $k$-mers from reads were independent, identically distributed (i.i.d.) variables, then a translated read of length $L_{\mathrm{translated}}$ drawing letters from the alphabet $\Sigma$, whose size is $|\Sigma|$, would contain

$$\left( \frac{1}{\left| \Sigma \right|^k} \right)^{L_{\mathrm{translated}} - k + 1}$$ {#eq:n_kmers_per_read_iid}

However, $k$-mers drawn from reads are not i.i.d.
Let's take a simple example.
If we have a two-letter alphabet, $\Sigma = \\{a, b\\},$, thus $|\Sigma| = 2$.
Let us use an example sequence $S = abbabba$.
If $k = 4$, then the first $k$-mer is $abba$.
The second $k$-mer is thus either $bbaa$ or $bbab$, with equal probability.
We can generalize this: Given the first $k$-mer, the first $k-1$ letters from the second $k$-mer are known, and thus the probability of guessing the next $k$-mer is $\frac{1}{\left|\Sigma\right|}$.

![Probability of future $k$-mers is influenced by the existence of previous $k$-mers.](images/abba_sequence_prob_future_kmers.png){#sfig:prob_kmers_in_read tag="prob_kmers_in_read" width="50%"}

Thus, the probability of a random $k$-mer from a sequencing read is completely dependent on the alphabet size $|\Sigma|$ and its translated sequence length, $L_{\mathrm{translated}}$:

$$
\begin{align}
\mathrm{Pr}(\mathrm{FPR}) &= \left(\frac{1}{|\Sigma|}\right)^k \times \left( \frac{1}{|\Sigma|} \right)^{L_{\mathrm{translated}} - k }\\
&=\frac{1}{| \Sigma |^k  \times |\Sigma|^{L_{\mathrm{translated} - k} }}\\
&= \frac{1}{| \Sigma|^{L_{\mathrm{translated}}}}
\end{align}
$$ {#eq:prob_kmers_in_read}

###### Bloom filter collision probability

The probability of error of the `khmer` bloom filter implementation [@doi:10.1371/journal.pone.0101271] used in `sencha`, given $N$ distinct $k$-mers counted, a hash table size of $H$, and $Z$ total number of hash tables, is

$$\mathrm{Pr}(\mathrm{FPR}_{\mathrm{bloom}}) = \left( 1 - \exp^{N/H}\right)^Z.$$ {#eq:bloom_filter_fpr}

Theoretically, the total number of $k$-mers is limited by the alphabet size and choice of $k$.
Empirically, the number of possible $k$-mers is limited by the $k$-mers which are compatible with life, and by $k=5$, the number of theoretical protein $k$-mers exceeds the number of observed protein $k$-mers.
Additionally, the mass of all possible $k$-mers of a certain size, exceeds the mass of the planet earth by $k = X$ [get the data for this].
The UniProtKB Opisthokonta manually reviewed dataset contains $4.8 \times 10^7$ $7$-mers in the protein alphabet.
Thus, we can give an upper bound to the number of theoretical $k$-mers to be $10^8$.
Therefore, the total number of $k$-mers in the bloom filter is,

$$N = \min\left( 10^8, |\Sigma|^k \right).$$ {#eq:n_proteome_kmers}

![Number of theoretical $k$-mers given alphabet size, compared to observed $k$-mers in ENSEMBL human translated proteome. The number of observed $k$-mers is distinct from the number of theoretical $k$-mers, as the total number of observed $k$-mers is limted by $k$-mers compatible with life. Rerun this with uniprot uniref data.](images/ksize_vs_n_kmers_theoretical_observed.png)

###### False positive rate of protein-coding prediction

Combining Equations @eq:prob_kmers_in_read, @eq:n_proteome_kmers, and @eq:bloom_filter_fpr, for an RNA-seq read of length $L$ where its translated length $L_{\mathrm{translated}} = \lfloor \frac{L}{3} \rfloor$, containing a possible six frames of translation, then the false-positive rate (FPR) protein-coding read is,

$$
\begin{align}
\mathrm{Pr}\left(\mathrm{FPR}\right) &=
6 \times \left( 1 - \exp^{\min\left( 10^8, |\Sigma|^k \right)} \right)^Z \times \frac{1}{\left| \Sigma \right|^{L_{\mathrm{translated}}}}.
\end{align}
$$  {#eq:fpr_protein_coding}

##### Similarity thresholds for percentage of matching $k$-mers

A single SNP in a read affects $k$ $k$-mers.

#### `sencha compare-kmer-content` performs all-by-all or pairwise k-mer similarity of protein or nucleotide sequences using reduced alphabets

![Overview of `sencha compare-kmer-content` **A.** Protein sequences are $k$-merized by converting into a bag of words using a sliding window of size $k$, potentially re-encoded to a lossy alphabet, and then their fraction of overlapping $k$-mers is computed into a Jaccard similarity. **B.** One option for `sencha compare-kmer-content` is to specify a pair of sequence files, and compute a background of $k$-mer similarty using randomly shuffled pairs. **C.** Another option for `sencha compare-kmer-content` is to do an all-by-all $k$-mer similarity comparison.](images/SVG/figure3.svg){#sfig:figure3 tag="figure3" width="100%"}


### Benchmarking

Methods go here.


#### Computational

![Supplemental Figure 2. **D.** Example of predicting protein-coding sequence using Brawand2011 RNA-seq data, and human proteome as the reference. x-axis, percentage of reads falling into that category, y-axis, the species which the reads are from.](images/SVG/supplemental_figure2.svg){#sfig:sfig2 tag="sfig2" width="100%"}

##### $k$-mer comparison of orthologous genes

We used ENSEMBL version 97.
We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@doi:10.1038/nmeth.3830].
Biorxiv example: [@url:https://doi.org/10.1101/466201].
Multiple citations per line example: [@doi:10.1038/nmeth.3830; @url:https://doi.org/10.1101/466201].

##### Extraction of putative coding reads from RNA-seq

We did things.
One sentence per line.
Prefer DOI for references, but for Biorxiv use the URL.
DOI example: [@doi:10.1038/nmeth.3830].
Biorxiv example: [@url:https://doi.org/10.1101/466201].
Multiple citations per line example: [@doi:10.1038/nmeth.3830; @url:https://doi.org/10.1101/466201].

#### Prediction of protein-coding sequences across a variety of species

We used `sencha translate` to obtain putative protein-coding sequences from a comaparative transcriptomic dataset spanning nine species and six tissues [@doi:10.1038/nature10532].

#### Read preprocessing

As the protein-coding score is assessed on the entire read, we recommend RNA-seq reads be removed of library artifacts to the best of the user's ability.
This means, the adapters should be trimmed, and if there was a negative insert size such that the R1 and R2 reads overlap, then the read pairs should be merged.


### Pipelines

<!-- ## Figure 3 -- Overview of `kmermaid` and `predictorthologs` pipelines -->

![**A.** Overview of the `kmermaid` pipeline. (**a**, **b**, **c**) `kmermaid` consists of a protein-coding prediction phase (**a**) that is invoked by the command `khtools extract_coding`, a k-mer sketch computation phase (**b**) invoked by the command `sourmash sketch`, a signature similarity comparison phase (**c**) invoked by the command `sourmash compare`, and an optional database-creation phase (**d**) invoked by the command `sourmash index`. The coding prediction phase has three components: (1) six-frame translation, removal of stop-codon frames, and subsequent $k$-merization of RNA-sequencing reads; (2) a degenerate protein alphabet which allows for protein-coding detection from a wide variety of species; (3) a bloom filter containing known protein-coding sequences from a well annotated organism; and (4) computation of the Jaccard index of translated RNA-seq reading frames. The sketch computation phase involves randomly subsetting the degenerate peptide $k$-mers using a MinHash algorithm. The sketch comparison phase consists of computing the Jaccard intersection of MinHashed degenerate peptide $k$-mers between all pairs of samples.](images/SVG/supplementary_figure3.svg){#fig:sfig3 width="100%"}




### Installation

`sencha` can be installed with the Anaconda package manager, `conda` (preferred),

```
# Note: not actually on bioconda yet ... this is aspirational
conda install --channel bioconda sencha
```

or from the Python Package Index (PyPI) with the Python package manager, `pip`,

```
# Note: not actually on PyPI yet ... this is aspirational
pip install sencha
```


### Usage


#### Creation of amino acid $k$-mer database with `sencha index`

Before predicting protein-coding sequences, `sencha` must create a database of known amino acid $k$-mers, which is stored in the form of a probabilistic set membership data structure known as a bloom filter.
`sencha` uses the bloom filter implementation in `khmer`/`oxli` [@doi:10.12688/f1000research.6924.1; @doi:10.1371/journal.pone.0101271], called a NodeGraph.
We created a dataset of known amino acid $k$-mers from the manually annotated UniProtKB/Swiss-Prot databases [@doi:10.1093/nar/gky1049; @doi:10.1007/978-1-4939-3167-5_2].
We used only protein sequences observed in *Opisthokont* species [@url:https://en.wikipedia.org/wiki/Opisthokont], previously known as a "Fungi/Metazoa" group that encompasseses "Fungus-like" *Holomycota* and "Animal-like" *Holozoa*. [NOTE: Does this need a figure/phylogenetic timetree?]

```
sencha index \
  --tablesize 100000000 \
  --molecule protein \
  --peptide-ksize 7 \
  --save-as uniprot-reviewed_yes+taxonomy_2759__molecule-protein_ksize-7.bloomfilter \
  uniprot-reviewed_yes+taxonomy_2759.fasta.gz
```

#### Prediction of protein-coding sequences with `sencha translate`

We then predicted protein coding reads using the created bloom filter using `sencha translate`.

```
sencha translate \
  --molecule protein \
  --coding-nucleotide-fasta SRR306800_GSM752653_ggo_br_F_1__coding_reads_nucleotides.fasta \
  --csv SRR306800_GSM752653_ggo_br_F_1__coding_scores.csv \
  --json-summary SRR306800_GSM752653_ggo_br_F_1__coding_summary.json \
  --jaccard-threshold 0.8 \
  --peptides-are-index \
  uniprot-reviewed_yes+taxonomy_2759__molecule-protein_ksize-7.bloomfilter \
  SRR306800_GSM752653_ggo_br_F_1_trimmed.fq.gz > SRR306800_GSM752653_ggo_br_F_1__coding_reads_peptides.fasta
```

![Applications of `sencha translate`. **A.** We simulated RNA-seq data using Opisthokonta species from the Quest for Orthologs dataset for true positive protein-coding RNAs, reads completely contained within intergenic, intronic, and UTR sequences as true positive noncoding RNAs, and reads partially overlapping a coding and noncoding region as an adversarial test set. We then predicted protein-coding sequences and computed false positive and false negative rates. False Positive coding reads were found to be ... False negative noncoding reads were found to be ... **B.** Number of putative protein-coding sequences per read. **C.** This method could also be used to extract only reads whose putative protein-coding sequences are transcription factors. **D.** We ran `sencha translate` on the five tissues and nine species from the Brawand 2011 dataset.](images/SVG/supplemental_figure2.svg){#sfig2:sfig2 tag="supplemental_figure2" width="100%"}


<!-- ### `sencha compare-kmer-content` is a simple method to identify homologs

![Applications of `sencha compare-kmer-content`. **A.** We used `sencha compare-kmer-content` on pairs of orthologous protein sequences between humans and the remaining Opisthokonta species in the Quest for Orthologs dataset. x-axis, $k$-mer size, y-axis, mean difference. **B.** False positive calls by `sencha compare-kmer-content` are either paralogs or read-through protein products. **C.** We applied `sencha compare-kmer-content` to ... to find putative orthologs. We found ... the accuracy was ...](images/SVG/figure4.svg){#sfig:figure4 tag="figure4" width="100%"} -->


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>


