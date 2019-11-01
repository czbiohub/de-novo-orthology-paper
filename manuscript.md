---
author-meta:
- Olga Borisovna Botvinnik
date-meta: '2019-11-01'
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
([permalink](https://czbiohub.github.io/primate-brain-organoid-paper/v/4864d1443e78de81a70b87ae8e6f44bf2a962758/))
was automatically generated
from [czbiohub/primate-brain-organoid-paper@4864d14](https://github.com/czbiohub/primate-brain-organoid-paper/tree/4864d1443e78de81a70b87ae8e6f44bf2a962758)
on November 1, 2019.
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
Many approaches exist [@LkrS4xXB].

Determining common ancestry of cell types ("orthologous cell types") [@ogAGO9KH @wdzgXUGy] is an additional difficult problem.
Comparative transcriptomics begins with finding a common feature set for embedding molecular profiles across divergent species into a common space.
Many researchers take the approach of using one-to-one orthologous genes [Cite: brawand2011, CCA, LIGER, Scanorama, basically all the single cell "alignment" packages], others use clusters of orthologous groups [@1tMQTfnh], others map reads onto a common genome derived from whole-genome alignment [cite: recent primate brain paper from Barbara Treutlein], or map onto native genomes [@y7xGipW5] and re-annotate using a tool such as Comparative Annotation Toolkit [@1BnfHjbCA].

$k$-mers have been proposed for comparing single cells [@wtk13QGK] as they are a fast, simple way to create cell-cell similarities.
However, the work so far has focused on using annotated organisms and not cross-species analyses.


## Methods

Methods go here.


We used ENSEMBL version 97.


## Results

To determine whether short segments of sequences could detect gene orthologues, we $k$-merized orthologous genes derived from the ENSEMBL version 97 [@lBlqrqAO] COMPARA database [@j0y6s0kf] (Fig.~\ref{fig:fig1}).
We compared human protein sequences to orthologous chimpanzee, mouse, (orangutan, bonobo, gorilla, macaque, opossum, platypus, chicken) protein sequences, as these are species used in [@fBCZ87Cf].
As a background, we randomly chose 10 non-orthologous genes relative to the human gene.
In addition to $k$-merizing the protein-coding sequence, we also re-encoded the protein-coding sequence into Dayhoff [@66KDHtpG] and hydrophobic-polar encodings [@1GiMcbPLs], show in Table~\ref{tab:encodings}.


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
to `bbbdbfecdac`, and HP-encoded to `phpphhhpppp`. {#tbl:example-id}


![Figure 1.](images/figure1.svg){#fig:fig1}


We found that, consistent with previous knowledge, that 1:1 orthologues had higher $k$-mer similarities as determined by the Jaccard Index.


Additionally, more recently diverged genes had higher $k$-mer similarity as well.


![Figure 2.](images/figure2.svg){#fig:fig2}


## Discussion

Conclusions and future directions go here.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
