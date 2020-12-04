---
author-meta:
- Olga Borisovna Botvinnik
- Venkata Naga Pranathi Vemuri
- N. Tessa Pierce
- Phoenix Aja Logan
- Saba Nafees
- C. Titus Brown
- Jim Karkanias
bibliography:
- content/manual-references.json
date-meta: '2020-12-04'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="$k$-mer homology is a transcriptome-first method enabling functional prediction of transcriptomic &#39;dark matter&#39; across species" />

  <meta name="citation_title" content="$k$-mer homology is a transcriptome-first method enabling functional prediction of transcriptomic &#39;dark matter&#39; across species" />

  <meta property="og:title" content="$k$-mer homology is a transcriptome-first method enabling functional prediction of transcriptomic &#39;dark matter&#39; across species" />

  <meta property="twitter:title" content="$k$-mer homology is a transcriptome-first method enabling functional prediction of transcriptomic &#39;dark matter&#39; across species" />

  <meta name="dc.date" content="2020-12-04" />

  <meta name="citation_publication_date" content="2020-12-04" />

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

  <meta name="citation_author" content="C. Titus Brown" />

  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />

  <meta name="citation_author_orcid" content="0000-0001-6001-2677" />

  <meta name="twitter:creator" content="@ctitusbrown" />

  <meta name="citation_author" content="Jim Karkanias" />

  <meta name="citation_author_institution" content="Data Sciences Platform, Chan Zuckerberg Biohub" />

  <meta name="citation_author_orcid" content="0000-0002-8057-6055" />

  <meta name="twitter:creator" content="@jkarkanias" />

  <link rel="canonical" href="https://czbiohub.github.io/kmer-homology-paper/" />

  <meta property="og:url" content="https://czbiohub.github.io/kmer-homology-paper/" />

  <meta property="twitter:url" content="https://czbiohub.github.io/kmer-homology-paper/" />

  <meta name="citation_fulltext_html_url" content="https://czbiohub.github.io/kmer-homology-paper/" />

  <meta name="citation_pdf_url" content="https://czbiohub.github.io/kmer-homology-paper/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://czbiohub.github.io/kmer-homology-paper/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://czbiohub.github.io/kmer-homology-paper/v/b98d97ab7215da70ce7c9dc863eb0b62daf5194f/" />

  <meta name="manubot_html_url_versioned" content="https://czbiohub.github.io/kmer-homology-paper/v/b98d97ab7215da70ce7c9dc863eb0b62daf5194f/" />

  <meta name="manubot_pdf_url_versioned" content="https://czbiohub.github.io/kmer-homology-paper/v/b98d97ab7215da70ce7c9dc863eb0b62daf5194f/manuscript.pdf" />

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
- gene orthology
- orthologous genes
- reduced amino acid alphabet
- degenerate amino acid alphabet
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: $k$-mer homology is a transcriptome-first method enabling functional prediction of transcriptomic 'dark matter' across species
...






<small><em>
This manuscript
([permalink](https://czbiohub.github.io/kmer-homology-paper/v/b98d97ab7215da70ce7c9dc863eb0b62daf5194f/))
was automatically generated
from [czbiohub/kmer-homology-paper@b98d97a](https://github.com/czbiohub/kmer-homology-paper/tree/b98d97ab7215da70ce7c9dc863eb0b62daf5194f)
on December 4, 2020.
</em></small>

[ []{.fas .fa-info-circle .fa-lg} **This is an in progress manuscript.**]{.banner .lightred}

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

+ **C. Titus Brown** <br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-6001-2677](https://orcid.org/0000-0001-6001-2677)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [ctb](https://github.com/ctb)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [ctitusbrown](https://twitter.com/ctitusbrown)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
     · Funded by Moore Foundation GBMF4551
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



## Abstract {.page_break_before}

Animals spread pathogens to humans in zoonotic diseases, and many of these animals are asymptomatic, and we want to leverage single-cell transcriptomics to identify cell types enabling these organisms to survive without symptoms, and apply them to human therapeutics. However, 99.9% of animal species on the Earth do not have a reference genome, including many pathogen host animals.
Thus, there is an unmet need for transcriptome-first methods to interrogate single cell types that do not require reference genomes or gene annotations.
To this end, we introduce the concept of "$k$-mer homology," a method for lightweight detection of orthologous genes directly from transcriptomes without need for  a reference genome. Underpinning $k$-mer homology is the tool `leaftea`, a novel computational method for extracting high-confidence protein-coding sequences from RNA-seq data into non-coding reads and protein-coding reads which can then be manipulated to reduced amino acid alphabets which are directly comparable across large evolutionary distances.
As the direct assignment of protein-coding sequence skips both traditional alignment and gene orthology assignment it can a) be applied to transcriptomes from organisms with no or poorly annotated genomes, and b) identify putative functions of protein sequences contributing to shared cell types.
We applied these methods to the problem of understanding the unique ability of bats to harbor zoonotic diseases, especially coronaviruses such as SARS, MERS, SARS-CoV-2, an issue of fundamental importance to human health.
However, important immunological genes such as interferon pathway genes have not been adequately identified in the bat genome and thus that aspect of bat biology could not be identified.
With our methods, we were able to detect widespread expression of --- in immune tissues of the SARS reservoir species, and the purported SARS-CoV-2 species *Rhinolophus sinicus* (Chinese horseshoe bat) single-cell RNA-seq transcriptomes, as compared to human tissues.
The *R. sinicus* interferon genes were slightly different from human interferon genes [...]
By enabling analyses across divergent species' transcriptomes in a genome-, gene annotation-, and orthology-agnostic manner, `leaftea` illustrates the potential of non-model organisms in building the cell type evolutionary tree of life.


## Introduction {.page_break_before}

<!-- "---" indicates a number or result that is to be filled out -->

### Key sentence: To identify cell types of interest in host organisms, single-cell RNA-seq is a powerful tool, but it is not readily accessible to organisms without well-annotated reference genomes.

The current COVID-19 pandemic has exposed inabilities of understanding zoonotic diseases in wild animals such as bats, due to poorly annotated genomes.
However, the asymptomatic nature of infection in zoonotic host organisms and how it could be applied to humans is of immediate concern.
<!-- non-human host organisms such as the bat *Rhinolophus sinicus*. -->
Zoonoses such as SARS-CoV-1 and SARS-CoV-2 are often harbored in wild animals such as bats, that do not have well annotated genomes, but the asymptomatic nature of infection in those organisms and how it could be applied to humans is of immediate concern, due to the recent SARS, MERS, and Ebola outbreaks, and the current COVID-19 pandemic.
Identifying cell types in these host organisms enables studying the broad array of cell types available to living creatures, and can help understand human disease by seeing cell types that are "normal" in one animal, but resemble human disease cell types.
To identify cell types of interest in host organisms, single-cell RNA-seq is a powerful tool, but it is not readily accessible to organisms without well-annotated reference genomes, as 99.999% of the approximate 10 million animal species predicted to exist on Earth have no submitted genome assembly [@doi:10.1371/journal.pbio.1001127; @url:https://www.ncbi.nlm.nih.gov/genome/browse#!/overview/].
Current methods for identifying cell types use single-cell RNA-sequencing, however, require three things: (1) high-quality genome assembly, (2) high-quality predicted gene annotations and (3) high-quality orthologous gene mappings across species.
But, we can nonetheless generate single-cell RNA-seq data from these species with poorly annotated genomes, and if we can leverage the annotations from existing organisms, we can better understand why host animals are able to tolerate infection by a pathogen that is deadly in humans.

### key: The most common strategies for cross-species transcriptomics lose data due to unaligned sequences, unannotated genes, and unmatched genes across species.


There are many strategies for comparative transcriptomics for single cells [@doi:10.3389/fcell.2019.00175].
The most commonly used strategies for cross-species gene expression analyses lose data due to unaligned sequences, unannotated genes, and unmatched genes across species.

Unaligned sequences are largely due to errors in genome assembly, or
While high-quality end-to-end genome assemblies are now within reach with the recently published teleomere-to-telomere human genome assembly [@doi:10.1038/s41586-020-2547-7], and high-quality assemblies, including gene annotations, will soon be a possibility thanks to thhe efforts of the Vertebrate Genome Project [@https://doi.org/10.1101/2020.05.22.110833; @https://doi.org/10.1101/2020.06.30.177956].
While the genome assembly provides substantial informationa bout the genomic structure of a species, it does not yet have the matching genes across species.

### key: Matching genes across species is an open and unsolved problem.

One of the first fundamental step is creating a common gene expression matrix to compare the cell types.
Matching genes across species is perfolrmed via a process called orthologous gene mapping.
A group that is working on this is the Quest for Orthologs Consortium, which has established benchmarking  [@doi:10.1038/nmeth.3830; @doi:10.1093/nar/gkaa308; @doi:10.1093/bioinformatics/btu492; @doi:10.3389/fgene.2017.00165] services.
Another option besides using 1:1 orthologs is using orthogroups [@doi:10.1186/s13059-015-0721-2], aligning genes/reads to a common genome if the species are closely related, such as for primates [@doi:10.1038/s41586-019-1654-9].

and even fewer have gene predictions and orthologous gene mappings to human, which remains an open problem [@doi:10.1038/nrg.2016.127; @doi:10.1146/annurev-cellbio-100616-060818].
The most commonly used strategy is subsetting the matrix down to 1:1 orthologous genes, which already have been computed by a database such as ENSEMBL [@doi:10.1093/nar/gkz966; @doi:10.1093/nar/gkz966].
Comparative transcriptomics traditionally relies on orthologous gene mapping, which requires a genome.



Another strategy for more distantly related species is to only use transcription factor genes that are part of "core regulatory complex" (CoRC), which again subsets the data to only certain genes.
Not just at alignment, but at aligning to annotated genes, at subsetting to 1:1 orthologs -- these are all data lossy steps.
While the first two steps are dependent on the genome assembly and gene annotation quailty, the subsetting to 1:1 orthologs cannot be solved with improved assembly and gene annotation tools.
It can be solved with using other strategies for finding orthologous genes.
Another strategy is aligning reads to the native species' genome, and using a tool such as LiftOver to remap coordinates into a well annotated genome such as human, and use those genes.

For all of these tools, the problem with them is that they lose data at every step.
These tools are not available to the 99.9% of vertebrates that do not have a reference genome, but transcriptome work, single-cell RNA-seq data is now so easy to obtain, that people already want to do analyses with their single cell data even if their organism doesn' thave a great reference genome.
And that's what we are enabling.

Once the genomes of the species are obtained, the work is not over.
For each pariwise species comparison, the orthologous genes must be found.
There are many tools for this, such as OrthoFinder [@doi:10.1186/s13059-015-0721-2], eggNOG [@doi:10.1093/nar/gkv1248; @doi:10.1093/molbev/msx148], and highly curated databases such as ENSEMBL [citation].
The time to run these tools is a long time.
But that's not really the point... what we really care about is using the RNA-seq data directly and not losing data due to mismatched orthology, unannotated genes, or unaligned seuqences.




### key: A method of not losing data due to unaligned sequences or unannotated genes is using all the data in the form of subsampled $k$-mers.


$k$-mers from sequencing data for single cells have been used to show that they can identify single cell types as well as gene counts [@https://doi.org/10.1101/723833].
Recently, there has been literature to use subsampled $k$-mers to identify metagenomes within metagenomic data, but this uses subsampling of the data [@doi:10.1186/s13059-016-0997-x; @doi:10.21105/joss.00027; @doi:10.12688/f1000research.19675.1].
It turns out that $k$-mers are quite redundant and it is not necessary to use all of them for genome identification.
Specifically, it is possible to use a fractional subsampling of the original data to represent the data faithfully as if all $k$-mers were stored, as implemented in the Sourmash software [@doi:10.21105/joss.00027; @doi:10.12688/f1000research.19675.1].
$k$-mers or k-long substrings have a long history in bioinformatics [@isbn:9780990374633] and have been widely used for genome and transcriptome assembly problems. They were recently applied to metagenomics for taxonomic classification.

We show that we use a subsampled set of the $k$-mers to still identify cell types across and within species.

However, for applying to cell types across species, we add the layer of using reduced amino acid alphabet $k$-mers.

However, for applying to cell types across species, we add the layer of using protein $k$-mers.

### key: Protein sequence can be inferred from RNA-seq due to nullomers.

Nullomers are sequences that are not present in the genome annotation or protein sequences [@doi:10.1142/9789812772435_0034; @doi:10.1371/journal.pone.0164540; @https://doi.org/10.1101/2020.06.25.170431; @https://doi.org/10.1101/2020.03.02.972422] of a species.
While this seems like there are a contradiction between wanting to use all the data, and then only using the data that is present in the database annotation, we show we are able to predict protein coding reads using simulated data.
The signal of a non-protein coding sequence is very obvious -- the true coding frames have $k$-mers in common with the known database, and the non-true coding frames do not have $k$-mers in common.
There are only so many $k$-mers that are compatible with eukaryotic, or mammalian life.
There are amino acid combinations that are not seen in the natural world.
Whether nullomers are not present due to natural selection or due to CpG hypermutability [@doi:10.1371/journal.pone.0001022] remains under debate, there are this phenomena is real and can be exploited to identify putative protein-coding sequences.
By using the "negative space" of unobserved protein sequences, we can identify reading frames of RNA to protein-coding sequences that are unlikely.
Non-productive Reading frames of RNA-seq can be found in the nullomers.
Protein sequences that have been observed are inferred in the $k$-mers.

### key: Gene annotations can be inferred from RNA-sequencing data, which is easily obtained with commodity tools

What we can do with $k$-mers is use a peripherally related genome to align to, and then extract the protein-coding reads and $k$-mers that are present, then directly compare them.

Transcribed seqeunces in the form of RNA-seq data can be inferred to be transcribed genes for now.


### key: Reduced amino acid alphabets provide a lightweight method of identifying matching genes across species.

Not only do we use protein $k$-mers, but we use reduced amino acid alphabet $k$-mers.

Amino acids can be categorized into their biochemical properites.
Many times,a  protein can retain its same phsyical structure and function even with amino acid changes.
These amino acid changes may be retaining the phyiochemical properites of the amino acid.
The space of amino acid substituion was explored back in the 90s to find similarity searches for proteins.
The BLOSUM62, PAM substituion matrices were a method of assigning higher penalties for amino acids that changed their biochemical type.
Reduced amino acid alphabets are a method of reducing blame in changing of amino acid sequences, which is especially compatible with $k$-mers as if a single letter in a $k$-mer changes, then the whole $k$-mer no longer matches.

A method of quickly identifying potential orthologs is using reduced amino acid alphabets [@doi:10.1093/gigascience/giz118].
Reduced amino acid alphabets have been used for database searches of related protein sequences [@doi:10.1186/1471-2105-12-159] and for protein structure prediction
[@doi:10.1093/bioinformatics/btp164 @doi:10.1093/gigascience/giz118; @doi:10.1093/bioinformatics/10.4.453; @doi:10.1186/1471-2105-12-159; @doi:10.1093/protein/13.3.149; @doi:10.1093/bioinformatics/btp164; @doi:10.1093/nar/gkh180]


We combine the two concepts of $k$-mer subsampling and homology identification via reduced amino acid alphabets into what we term "$k$-mer homology."


### key: There is an unmet need to quantitatively compare single-cell transcriptomes across species, without the need for orthologous gene mapping, gene annotations, or a genome assembly.

We translate our protein sequences to protein.
We need to predict protein seuqnece, and turns out most reading frames of RNA don't need to be predicted -- they are already near zero.
They have stop codons.

Thus, there is an unmet need to quantitatively compare single-cell transcriptomes across species, without the need for orthologous gene mapping, gene annotations, or a reference genome.
Short, $k$-long sequence substrings, or $k$-mers, have been proposed for clustering single cells [@url:https://doi.org/10.1101/723833] and here we implemented $k$-mers from putatitvely translated RNA-seq reads with reduced amino acid alphabets [@doi:10.1093/bioinformatics/btp164 @doi:10.1093/gigascience/giz118; @doi:10.1093/bioinformatics/10.4.453; @doi:10.1186/1471-2105-12-159; @doi:10.1093/protein/13.3.149; @doi:10.1093/bioinformatics/btp164; @doi:10.1093/nar/gkh180], to find shared cell types across species, and further identify *de novo* orthologous genes by querying the predicted protein sequences to a reference database.
This method relies solely on divergence time between species, which we show can be estimated from RNA-seq nucleotide $k$-mers (Supplemental Figure [@sfig:sfig1]).
As the direct assignment of protein-coding sequence skips both traditional alignment and gene orthology assignment it can a) be applied to transcriptomes from organisms with no or poorly annotated genomes, and b) identify putative functions of protein sequences contributing to shared cell types.

We benchmark the prediction of protein-coding sequence using simulated human RNA-seq data from single-copy genes present across all clades of mammals [@doi:10.1093/bioinformatics/btv351].
We show that one can extract putative protein-coding reads from --- mammalian species in BUSCO, and present the best parameters for different divergence times.

<!-- We first apply this method on a bulk comparative transcriptomic dataset consisting of nine amniote species and six tissues [@doi:10.1038/nature10532], showing that we achieve similar clustering results as using only reads mapping to 1:1 orthologs or Hierarchical Orthologous Groups (HOGs) [@doi:10.1371/journal.pone.0053786; @doi:10.1093/bib/bbr034; @doi:10.1093/bioinformatics/btu492] of protein-coding genes, but are able to resolve ... which can only be seen by using the $k$-mer method. -->
We first demonstrate the utility of this method by comparing lung tissue transcriptomes from organisms diverged by approximately 100 million years ago (MYA) [@url:http://timetree.org/]: mouse from *Tabula Muris Senis* [@doi:10.1038/s41586-020-2496-1],
Across this evolutionary distance, only --- 1:1 orthologous genes exist as found by ...
<!-- and XX HOGs via orthologous matrix (OMA) [@doi:10.7717/peerj.6231; @doi:10.1093/bioinformatics/btx229] -->
We then add single-cell lung data from *Rhinolophus sinicus*, Chinese greater horseshoe bat, whose single-cell transcriptome was recently published [@https://doi.org/10.1101/2020.06.30.175778]..
Using the $k$-mer homology method, we are able to distinguish the subtypes of T cells in the *R. sinicus* which were hidden using read counts alone, due to $k$-mers from genes not present in the genome assembly.
We then show the ability to find cell type enriched sequences that are absent from the reference genome, in particular interferon pathway genes and natural killer receptor genes.


### key: $k$-mer homology is a transcriptome-first method for cross-species analyses implementing via $k$-mers and reduced amino acid alphabets

Thus, we have shown the reference-free method using the $k$-mers from single cells is a novel, annotation-agnostic method for comparing cells across species that is capable of identifying cell states unique to a particular organism, helping to build the cell type evolutionary tree of life.

Similar to $k$-mer based approaches for transcript quantification [@doi:10.1038/nbt.2862; @doi:10.1038/nbt.3519; @doi:10.1038/nmeth.4197], we implemented $k$-mer based gene expression analyses across species, but instead of using DNA $k$-mers, our critical innovation was using translated protein $k$-mers.
We utilized sequence bloom trees (SBTs) [@doi:10.1038/nbt.3442] using a bottom-up approach to build them similar to previous work [@doi:10.1089/cmb.2017.0265; @doi:10.1089/cmb.2017.0258] to ensure localization of new datasets, meaning, if two leaves share a parent, they are guaranteed to be more similar than two leaves that do not share a parent.

For widespread accessibility and usage, we implemented `leaftea` into two distinct Nextflow pipelines following software best practices such as testing and continuous integration: (1) `nf-core/kmermaid` to compare translated transcriptomes across divergent species, and (2) `czbiohub/nf-predictorthologs` to infer functions of translated sequences.

![
**A.** Overview of single-cell RNA-seq lung tissue datasets from three species: *Homo sapiens* (human), *Rhinolophus sinicus* (Chinese horseshoe bat), and *Mus musculus*.
**B.** Overview of $k$-mer homology method. First, RNA-seq reads are translated to protein via the leaftea tool, then a cell type database is built from $k$-mers from the putative protein-coding sequence, given a query cell of a new species, the best matching cell from the model organism database is found, and the cell label is returned.
<!-- **B.** Overview of computational method. First, in the `kmermaid` pipeline, RNA-seq reads are translated to protein via the leaftea tool, then converted to a reduced amino acid alphabet, decomposed into $k$-mers, and then those $k$-mers are subsampled. Next, the `nf-predictorthologs` pipeline performs differential $k$-mer expression, much like differential gene expression, to find $k$-mers that are enriched in a population, and queries for those differential $k$-mers in databases to identify them. -->
](images/SVG/figure1.svg){#fig:fig1 width="100%"}



## Results



### Reliable identification of putative protein-coding sequence with `leatea translate` across ~150 million years of evolution

| Amino acid              | Property              | Dayhoff |
|:------------------------|:----------------------|:--------|
| `C`                     | Sulfur polymerization | `a`     |
| `A`, `G`, `P`, `S`, `T` | Small                 | `b`     |
| `D`, `E`, `N`, `Q`      | Acid and amide        | `c`     |
| `H`, `K`, `R`           | Basic                 | `d`     |
| `I`, `L`, `M`, `V`      | Hydrophobic           | `e`     |
| `F`, `W`, `Y`           | Aromatic              | `f`     |
Table: Dayhoff encoding of amino acids by categories of biochemical properties, into a six-letter alphabet. Adapted from [@doi:10.1186/1471-2105-9-367]. For example, the protein sequence `LIVING` would become `eeeecb`. {#tbl:dayhoff-alphabet}

![
Application of $k$-mer homology to mammalian lung cell type identification recapitulates known biology and identifies enriched genes not present in reference genome assembly.
**A.** Overview of `leaftea translate` method. First, each read is translated into all six possible protein-coding translation frames. Next, reading frames with stop codons are eliminated. Each protein-coding frame is $k$-merized, then the fraction of $k$-mers which appear in the known protein-coding database is computed. Reading frames containing 5% or more $k$-mers matching the reference proteome are inferred to be putatively protein-coding.
**B.** Experimental set up to identify best $k$-mer sizes for translating protein-coding sequence, given a reference proteome of divergent organism. First, human RNA-seq reads were simulated from genes present in all extant mammals. Next, we used highly curated reference proteomes from BUSCO Mammalia, representing almost 200 million years of evolution, across a wide range of mammalian species. Using `leaftea`, we partition the reads into protein-coding and noncoding using a variety of amino acid alphabets and $k$-mer sizes, and then compute classification metrics.
**C.** Predictive power of detecting protein-coding sequence across ~200 million years of evolution, using simulated human RNA-seq reads and mammalian reference proteomes. x-axis, $k$-mer size used to translate the RNA sequence; y-axis, receiver operating characteristic area under the curve (ROC AUC) of protein-coding prediction at that $k$-mer size. Dotted vertical lines indicate $k$-mer size producing maximum ROC AUC for each divergence time.
**D.** Classification metrics of protein-coding prediction with both protein and Dayhoff alphabets, using best-performing $k$-mer sizes for each alphabet from (**C**). Left, precision; middle, recall; right, $F_{1/2}$ score. x-axis, Estimated divergence time of reference proteome relative to human, from timetree.org; y-axis, value of classification metric.
](images/SVG/figure2.svg){#fig:fig2 width="100%"}

To extract putative protein coding sequences from RNA-seq reads, we first established whether we could predict protein-coding sequences from simulated human RNA-seq data.
We reliably identified putative protein-coding reads using our tool, `leaftea`.
`leaftea` works by performing six frame translation of RNAs, discarding reading frames with stop codons, and decomposing each frame into amino acid $k$-mers, and checking for the $k$-mer present in the reference proteome (Fig. {@fig:fig1}A).
In detecting putative protein coding sequence, there many be small amino acid changes that do not change the overall function of the protein, and to accommodate this, we offer the option to translate using either the original 20-letter amino acid alphabet, or a six-letter reduced amino acid alphabet, the Dayhoff encoding [@tbl:dayhoff-alphabet].
As many organisms of interest are not annotated, but a different organism with a related ancestor is, we wanted to understand the limits of protein-coding detection when the best-annotated organism in the database is divergent with up to approximately 200 million years.
To test this, we simulated human RNA-seq data from genes present in all extant mammals as determined by BUSCO [@doi:10.1007/978-1-4939-9173-0_14], and used reference proteomes from eighteen mammals, ranging in divergence from 0 to almost 200 MYA [@url:timetree.org] (Fig. {@fig:fig1}B).
We found that we were able maximize classification power, measured via receiver operating characteristic area under the curve (ROC AUC), for most divergence times for a protein alphabet with a $k$-mer size of 8, and a $k$-mer size of 17 for a Dayhoff encoding (Fig. {@fig:fig1}C, left and middle).
Across all mammals tested, it was clear that some were better annotated than others based on the ROC AUC curves (Supplemental Fig. {@fig:sfig1}).
For example, hedgehog (*Erinaceus europaeus*) had more successful protein-prediction than species with similar divergence times from human such as rhino (*Ceratotherium simum simum*), even though both are members of Boroeutheria, a mangnorder of mammals with a most recent common ancestor at an estimated 96 MYA of one another [@url:timetree.org], containing the superorders Euarchontoglires (includes rodents and primates) and Laurasiatheria (includes bat, hedgehog, hooved animals, cats, and dogs).
We found that a protein alphabet with a $k$-mer size of 8 was most productive in translating the sequences for closely related species, within Boroeutheria, with a mean ROC AUC of 0.873898 among well-annotated reference proteomes.
For more distantly related species such as platypus (*Ornithorhynchus anatinus*), a the Dayhoff alphabet had a ROC AUC of 0.547203.
<!-- , however, the precision of rejecting non-coding reads remained quite high across distantly related species (Fig. {@fig:fig1}D, left). -->
Interested in understanding whether `leaftea`'s strength lies in detecting true protein-coding reads, or eliminating non-coding reads, we computed the precision and recall of protein-coding classification (Fig. {@fig:fig1D}, left and middle).
Our precision to remove non-coding reads is quite high, especially with the Dayhoff alphabet, which retains a high precision even for the platypus proteome, which is approximately 177 MYA diverged from human.
As this metric performs better in precision, we used an $F_{\beta}$ score, where $\beta = 1/2$, to indicate a 2x preference for precision over recall (Fig. {@fig:fig1}D, right).
<!-- Interested in understanding whether `leaftea`'s strength lies in detecting true protein-coding reads, or eliminating non-coding reads, we computed the precision and recall of protein-coding classification (Fig. {@fig:fig1D}).
We found that
Using the reference proteomes from different animals represents extracting protein-coding reads from an organisms whose closely related species in the reference database is 10, 50, etc million years diverged.
Using the reference proteomes, we found that a small fraction of overlapping $k$-mers in the putative protein-coding read were required to identify the read as putatively protein-coding. Our sensitivity to remove non-coding reads is quite high.
We chose a minimum containment threshold of 0.05 as this maximized the number of putative protein coding reads while successfully discarding non-coding reads. -->
This shows that while it is possible to detect putative protein-coding sequence, reliably rejecting non-coding sequences, even when the best annotated organism in the database almost 200 million years diverged from the query organism.


<!-- Putative protein-coding reads from simulated Human RNA-seq data can be identified across the mammalian lineage -->

### Degenerate amino acid alphabet $k$-mers identify common cell types across species and finds genes absent from even well-annotated genomes





![
**A.** Experimental set up to validate effectiveness of building a cell type database from one species, to label cells from another species. First, we build a cell type database using sequence bloom trees (SBTs) from mouse cells, then search using a human cell for the best matching mouse cell.
**B.** Mean of classification metrics across mouse:human cell type lookup experiments, highlighting the $k$-mer size that maximizes the mean for each metric and alphabet. Vertical lines, standard deviation of the mean. x-axis, $k$-mer size in DNA space, i.e. a $k$-mer size of 21 corresponds to a an amino acid length of 7. y-axis, value of classification metric. Left, adjusted rand score; right, F1 score.
**C.** Molecules and $k$-mer sizes maximizing classification metrics from (**E**).
**D.** Confusion matrices of classification using Dayhoff encoding and $k$-mer size of ---, the best performing metrics from (**E**). x-axis, predicted cell label; y-axis, ground truth cell label.
](images/SVG/figure3.svg){#fig:fig3 width="100%"}


#### key: Dayhoff-encoded $k$-mers reliably predict cell types within species

To test identification of cell types using $k$-mers, we first tested the method within species, with three main questions: Do the parameters change when the cell type lookup is within the same individual, across individual of the same sex, and across individuals of different sex?
<!-- Previous work has used $k$-mers from protein-coding genes of single-cell RNA-seq data within one individual of a species to distinguish cell types [@https://doi.org/10.1101/723833], and we are interested in first comparing effectiveness of $k$-mers to identify cell types across individuals of different species. -->
To test this, we built cell type databases from $k$-mer signatures using sequence bloom trees (SBTs) [@doi:10.1038/nbt.3442] using the `sourmash` software tool [@doi:10.12688/f1000research.19675.1; @doi:10.21105/joss.00027].
Using the Tabula Muris Senis data, we built a cell type database from one mouse, and queried its own cells (Supplementary Fig. {@fig:sfig2}A).
We first manually unified cell ontology class names into broader groups to encompass larger cell type labels.
We then created $k$-mer signatures at many $k$-mer sizes, from 21 to 90, using the raw nucleotide sequence from the RNA-seq reads, the `leaftea`-translated protein sequence, or a Dayhoff-encoded version of the `leaftea` translated sequences.
To reduce batch effects, we removed $k$-mers from technical artifact genes, such as ribosomal and mitochondrial genes, and genes associated with single-cell dissociation [@doi:10.1038/s41467-017-02772-x; @doi:10.1016/j.celrep.2017.10.037; @doi:10.1038/nmeth.4437; @doi:10.1186/s13059-020-02032-0; @https://doi.org/10.1101/2020.06.30.178673].
Similar to previous work [@https://doi.org/10.1101/723833], we find that using DNA from coding nucleotides successfully distinguishes cell types within individuals of the same species.
However, we see that even within an individual using the `leaftea`-translated protein sequences re-encoded into the Dayhoff alphabet outperforms using the DNA alphabet (Supplementary Fig. {@fig:sfig2}D,E), suggesting that there are enough differences in amplification or sequencing errors to warrant a degenerate protein alphabet, even within individuals of the same species.
<!-- We found that a $k$-mer size of --- with DNA had the best [F1 score / Adjusted Rand Index (ARI)] of --- cell type classification within one male mouse. -->
Interested in how the genomic differences across individuals affect DNA-based cell type classification, we built a cell type database from one male mouse, and queried a cell and returned its most similar matching cell (Supplementary Fig. {@fig:sfig2}B), and again the protein and Dayhoff alphabets outperformed the DNA alphabets (Supplementary Fig. {@fig:sfig2}D-F).<!-- We found that across mice, the DNA was still able to identify cell types, but the protein $k$-mers had a higher F1 score of ---. -->
Finally, we also tested a male-female comparison (Supplementary Fig. {@fig:sfig2}C), where the cell database was built from male cells, and the query was female cells, and found again that the Dayhoff alphabet outperformed all other alphabets (Supplementary Fig. {@fig:sfig2}D,G).
To compare across the three experiments, we averaged the adjusted rand and F1 scores (Supplementary Fig. {@fig:sfig2}H) and found that a Dayhoff encoding with a $k$-mer size of 39, corresponding to a peptide length of 13, maximized the F1 scores to 0.799 (Supplementary Fig. {@fig:sfig2}I).<!-- We were able to identify cell types across mice by using DNA $k$-mers of size --- and protein $k$-mers of size --- and Dayhoff $k$-mers of size ---. -->
Curious which cell types were most commonly mis-categorized, we created confusion matrices (Supplementary Fig. {@fig:sfig2}J-L) and found that the most often misclassified cell type was Natural Killer T cells, which were classified to T cells by our method.
Within cell compartments of epithelial, endothelial, myeloid and lymphoid, we had the fewest misclassifications with a --- alphabet and k-mer size of ---.
As these cell types are often difficult to distinguish, we felt this was sufficient to show the utility of Dayhoff-encoded amino acid $k$-mers to identify cell types within a species.
Thus, we find that Dayhoff-encoded `leaftea`-translated $k$-mers with a DNA $k$-mer size of 39 works well to "soften the rough edges" introduced by individual genomic variation for cell types and can be used to identify similar cell types within and across individuals of the same species.



#### key: Human cell types can be predicted from mouse cells using $k$-mers from reduced amino acid alphabets

<!-- Given putative protein-coding sequences from RNA-seq reads, we now use reduced amino acid alphabets as a lightweight substitute for homology across species. -->
To recapitulate known biology in the mammalian lung, we compared lung cell atlases from species related within the mammalian suborder Euarchontoglires, whose most recent common ancestor is between 85 to 95 million years ago, we applied these methods to a mouse single-cell RNA-seq atlas, *Tabula Muris Senis* [@doi:10.1038/s41586-020-2496-1], to a human
lung cell atlas [@doi:10.1038/s41586-020-2922-4].
Next, we show that we can identify cell types in human RNA-seq data from mouse cell type databases.
We built a cell type database from the 18-month old mouse Lung tissue in Tabula Muris Senis, and queried with human lung cells (Fig. {@fig:fig2}A).
<!-- Maybe this is for the supplemental text? -->
<!-- Across human-to-mouse, we found that DNA $k$-mers which vary quite greatly across species, were too variable to use to identify cell types. -->
<!-- Instead, we found that even protein $k$-mers cannot reliably identify cell types across species.
We turned to reduced amino acid alphabets such as Dayhoff (Fig. {@fig:fig2}A). -->
We found that a Dayhoff encoding with a minimum $k$-mer size of 36 maximized the Adjusted Rand index (0.300) and the F1-scores (0.565) for classification of cell types across human and mouse (Fig. {@fig:fig2}B-C).
Curious what the common misclassifications were, we plotted confusion matrices of the ground truth of human cells, compared to what they were predicted by the mouse cell type database (Fig. {@fig:fig2}D).



<!-- Comparison to other methods?? -->

To compare the performance of $k$-mer homology to traditional cross-species methods, we used --- tools to compare label propagation across species using 1:1 orthologous gene datasets.
We found that using 1:1 orthologs was not good and resulted in a classification adjusted rand index score of --- which was not good.
This enables finding expression of genes that may not be defined in the genome, and certainly genes that do not appear, are excluded by, subsetting to 1:1 orthologs, which is a common strategy for cross-species transcriptome comparisons.



#### key: Reduced amino acid alphabet $k$-mers enable identifying cell type enriched sequences that may not be present in gene annotation, genome assembly, or orthologous gene mappings

Once we identified common cell types across species, we then dug into genes that are enriched in the cell types that may not be present even in the annotated genome, or present in the orthologous gene mapping (Fig. {@fig:fig2}E).
To find expression of genes that many not be in the genome, we took two approaches.
First, we used differential $k$-mer expression to enrich for particular sequences that were highly expressed in a cell type.
We found that the overlap between differential gene expression 1:1 orthologs, and the differential $k$-mer expression and orthogroup expression, we found --- % overlap between al three, which had a --- p-value of significance using a chi-squared or hypergeometric test of enrichment.
Additionally, we identified --- genes that were enriched in molecular cell types that are not present in the genomes of human and mouse.
Specifically, we found an unannotated *pulmonary surfactant-associated protein A* gene in the Alveolar Type 2 cells, which makes sense since they express many surfactants.
We found that compared to gene expression, we had a ---% overlap with the genes that are known to be enriched by gene expression of 1:1 orthologs, and we found --- genes that were enriched in the cell types but were not 1:1 orthologs, and thus would have been missed by traditional methods.
Second, we used $k$-mers from orthogroups, orthologous groups of genes, defined at the mammalian clade, of genes with common function across species [cite orthogroups paper], computed signatures for the last 100aa of each amino acid sequence of orthogroups to get a relative gene expression (Fig. {@fig:fig2}F) using containment search [@url:https://github.com/dib-lab/2020-paper-sourmash-gather].
However, with the $k$-mers, we were able to find genes such as ---, --- and --- which are enriched in the cell type ---, but are not a 1:1 ortholog, and are instead a --- ortholog.
Some of these were even not present in the genome assembly, for example --- is present in the human genome assembly but not in the mouse assembly.
Thus, using $k$-mers, we are able to identify genes that are enriched in cell types but are not present in the genome assembly, in unannotated genes, or not 1:1 orthologs.




### Reduced amino acid $k$-mers from transcriptomes enabled identification of unannotated immune genes in Chinese horseshoe bat suggesting immune adaptations

We refined the lung cell type annotation from the Chinese horseshoe bat using our $k$-mer based cell type label propagation method. Using these refined labels, we found that --- in the bat cell types were more similar to --- classical monocytes --- in mouse and human than they tended to be to their original cell types (Fig. {@fig:fig3}A).
This led us to then perform differential expression to find the genes that may be enriched in the bat cell types overall.
Using both logistic regression on the $k$-mer abundances, and expression of orthogroups containment in the cells, we found --- genes were broadly expressed in the bat, as compared to mouse and human (Fig. {@fig:fig3}B).
We then dug into the genes that are expressed, but not found in the aligned genome or the gene annotation, and found that --- gene was a key contributor to --- natural killer cell --- type identity.

- Mouse:bat
  - celltype mapping
- mouse:bat:human
  - Identify gene expression for genes missing in genome


To identify molecular cell types unique to the Chinese horseshoe bat within mammals, we added a multi-organ, whole organism single-cell RNA-seq atlas of *R. sinicus*. We found expression of interferon genes, which have not been identified in the bat genome, but we were able to detect them in the transcriptome. In the bat scrnaseq paper, they performed qPCR to show expression of interferon genes, even though they weren't identified in the genome, to show those genes do truly exist.

To apply the method to a novel biological problem and create insights into previously unknown biology, we applied the $k$-mer homology method to a recently published cell atlas of the Chinese horseshoe bat, *R. sinicus* [@https://doi.org/10.1101/2020.06.30.175778].



## Discussion

### key: Single-cell atlases need to be made accessible to the 99% of non-model organisms


<!-- The increasing accessibility of single-cell RNA-seq data  provides a  -->
The availability of single-cell whole organism atlases [cite: tabula muris, tabula muris senis, MCA, HCA papers] enables rapid cell type identification in new datasets.
However, this cell type identification is not readily accessible to the 99.99% of animal species without a reference genome [cite vertebrate genome paper].
Indeed, 99.99% of the planet's rapidly decreasing number of animal species [cite climate change, extinction papers] are unable to directly benefit from the cell typing efforts due to a combination of both lack of a reference genome, and understudied organisms that do not readily have gene mappings across species annotated.
Thus, there is an urgent need for methods that leverage model organism cell atlases for understudied animals.
It's not just about the genome. The annotation and the orthology of gene annotations mapping across species is the really critical thing for cross-species analyses.
We developed a method to address the gap between model organisms cell atlases and the understudied organisms that may provide with novel cures for disease.

### key: Putative protein-coding sequence can be detected across ~150 million years of evolution

First, we extracted putative protein-coding sequence from an understudied animal, the Chinese horseshoe bat, *R. sinicus*.
First, we demonstrated the ability to discard unlikely protein-coding frames from RNA-seq data using our tool, `leaftea`.
Our precision is high, meaning we are able to discard true non-coding frames very easily.
Even for species that are distantly related, ~150 million years between human and the distantly related platypus species, we were able to reject ---% of the known non-coding frames from the simulated human data.
The most distantly related organism, platypus, with an estimated divergence time from human ranging from 167-192 MYA (@url:timetree.org), was able to identify true protein-coding sequence in human ---% of the time.
<!-- This indicates that even if the organism is approximately 200 MYA from the most closely related organism in the database, it is still possible to recover putative protein-coding. -->
Thus, we are able to recover the putative protein coding sequences, even when the most recent ancestor of the closest related organism in the database is within ~150 million years, meaning this method can open up the possibilities for annotating cell types in single-cell RNA-seq atlases for any mammal.
<!-- Thus, this opens up the possibility of studying nearly ---% of organisms on the planet, as most are related within 150 million years of annotated organisms. [Olga: Ask Erich Schwarz for help on how to compute this] -->

<!-- With the increasing accessibility of single-cell RNA-seq, it is more and more challenging to organize existing data.
 but the analysis of said data is more and more difficult if the organism is not well anotated in the databses. -->

<!-- [What iss the average distance between unknown/unannotated organisms and annotated organisms? Can this be quantified?]
We used RNA-seq data directly due to the fact that we can extract putative protein-coding sequences from the RNA-seq data. -->




### key: Cell type databases built on protein $k$-mers can assign cell types across individuals within species

We showed that we can identify cell types across individuals, within species.
Interestingly, we found that even within species and within an individual, re-encoding the predicted protein sequenced found by `leaftea` into the Dayhoff degenerate amino acid alphabet  with an amino acid $k$-mer length of 13 was most successful in detecting cell types.
Importantly, we also needed to remove genes associated with single-cell dissociation to enable cell:cell type labeling.
This suggests that due to differences in single-cell capture, molecular amplification, and sequencing errors, the nucleotide sequences are different enough that using nucleotide $k$-mers alone misses some cell types.

### key: Reduced amino acid alphabet $k$-mers enable lighweight orthology assignment

We showed that we can identify cell types across species using $k$-mers from a degenerate amino acid alphabet.
Across species, the Dayhoff alphabet was again the most successful in identifying cell types across species, specifically at an amino acid $k$-mer size of 12.
We then looked into the genes that were enriched in cells across species.

### key: Cell type databases built on reduced amino acid alphabet protein $k$-mers can assign cell types across species


### key: Lightweight orthology assignment using $k$-mers enabled reference-independent cross-species RNA-seq analyses and achieved insight into unannotated genes and genes absent from the genome assembly.

We implemented the concept of lightweight orthology assignment using $k$-mers to the problem of cross-species RNA-seq analyses and achieved insight into unannotated genes and genes absent from the genome assembly.
By removing the orthology inference step, `kmermaid` opens up the possibility of finding shared and divergent tissue and cell types across a broad range of species, paving the way for evolutionary analyses of cell types across species.
`kmermaid` can be used in *de novo* setting for non-model organisms, finding similar cell types within an organism, or finding similar cell types relative to a reference organism, without the need for a reference genome or transcriptome.
The memory usage of `kmermaid` is quite low, using only --- MB for extracting coding sequences and 50MB for assigning protein $k$-mer signatures.
As the number of RNA-seq datasets, especially single-cell RNA-seq datasets continues to grow, we expect `kmermaid` to be widely used for identifying cell types in non-model organisms.


### key: Reduced amino acid alphabet $k$-mer enrichment allowed for inserting /identifying genes that were not present in the genome assembly or gene annotation, or gene orthology

We were able to identify putative homologs across species by finding genes that were enriched in common cell types

### key: We built an orthologous gene tree and were able to identify genes in cells across all species
<!-- Is this a separate paper? -->
Using orthogroups, we built a signature tree database of orthologous genes.
We then were able to quantify gene expression
We were able to detect genes that were not present in the genome, but were present in the orthologous genes databases.
We were thus able to directly compare cell types across species with a common set of orthologous genes.
We used sourmash gather to identify genes that were expressed across multiple cell types

### In summary, we developed a method to identify cell types in a non-model organism using a reference atlas from another organism, without the need for a genome or gene annotation from the non-model organism.

In summary, we developed a method to identify both known cell types in a non-model organism using a reference atlas from another organism, without the need for a genome or gene annotation from the non-model organism.
This method can be used to combine single-cell cell atlases from well-annotated,  model organisms, with sequencing data from poorly annotated non-model organisms, to directly find homologous cell types and orthologous genes.
By eliminating read alignment and orthologous gene mapping, `kmermaid` enables comparison of transcriptomes of the remaining 99.999% Eukaryotic species on Earth without submitted genome assemblies, with the cell atlases of a handful of model organisms to identify shared and novel cell types, and *de novo* identify orthologous genes.
By identifying homologous cell types across a broad variety of species, we come closer to an understanding of the evolution of genes, cells, and thus life itself.

`kmermaid` is free and open-source software and is available as Supplementary Data and at http://github.com/czbiohub/kmermaid and as a scalable Nextflow workflow at http://github.com/nf-core/nf-kmermaid.

We have provided pre-built cell type databases of *Tabula Muris Senis* at ---.




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

<!--
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


<!--
##### Reduced nucleotide alphabets

The IUPAC degenerate nucleotide code [@url:https://www.qmul.ac.uk/sbcs/iubmb/misc/naseq.html] includes several two-letter codes for the original 4-letter nucleobase alphabet.
The first, Weak/Strong, indicates the strength of the hydrogen bond across the double strand.
The bond of adenine to thymine has two hydrogen bonds, making it weak; and the bond of guanine to cytosine has three hydrogen bonds, making it 50% stronger.
The second, Purine/Pyrimidine, encodes the ring size of the nucleobase, where Adenine and Guanine both have larger Purine double rings, while Cytosine and Thymine/Uracil have smaller Pyrimidine rings.
The third, Amino/Keto, designates the main functional group of the ring, where Adenine and Cytosine both have an Amino group, while Guanine and Thymine/Uracil both have a Keto group. -->

<!-- This spreadsheet:https://docs.google.com/spreadsheets/d/1RDuQD0aRyv-FnQJbjRosHEJV85_9BNrzmmvgFRQSgN8/edit#gid=104831627 was copied into this formatter: https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/ -->

<!-- | Nucleotide | Hydrogen Bonding | Ring type      | Ring functional group | Nucleobase chemical structure                                                                                                                                   |
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
-->

#### `sencha translate`


![
Supplemental Figure 1: Receiver operating characteristic curves for predicting protein-coding sequence of human RNA-seq data, using mammalian species' reference proteomes.
**A.** Prediction of protein-coding sequence using protein alphabet.
**B.** Prediction of protein-coding sequence using Dayhoff alphabet.
](images/SVG/supplemental_figure1.svg){#sfig1:supplemental_figure1 tag="supplemental_figure1" width="100%"}


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


Probability of a random $k$-mer being present in a perfect protein index
$$
\frac{N}{\left| \Sigma \right| ^k}
$$  {#eq:prob_kmer_in_index}

Probability of *all* $L - k + 1$ $k$-mers of a read being present in a perfect protein index
$$
\left( \frac{N}{\left| \Sigma \right| ^k} \right) ^ { L - k + 1 }
$$  {#eq:prob_kmer_in_index}

Probability of a random $k$-mer being present in an *imperfect* protein bloom filter with false positive rate or "collision rate" $p_{\mathrm{collision}}$
$$
\frac{N}{p_{\mathrm{collision}} * \left| \Sigma \right| ^k}
$$  {#eq:prob_kmer_in_index}

Probability of *all* $L - k + 1$ $k$-mers of a read being present in an *imperfect* protein bloom filter with false positive rate or "collision rate" $p_{\mathrm{collision}}$
$$
\left( \frac{N}{p_{\mathrm{collision}} * \left| \Sigma \right| ^k} \right) ^ { L - k + 1 }
$$  {#eq:prob_kmer_in_index}


##### Similarity thresholds for percentage of matching $k$-mers

A single SNP in a read affects $k$ $k$-mers.

#### `sencha compare-kmer-content` performs all-by-all or pairwise $k$-mer similarity of protein or nucleotide sequences using reduced alphabets

![Overview of `sencha compare-kmer-content` **A.** Protein sequences are $k$-merized by converting into a bag of words using a sliding window of size $k$, potentially re-encoded to a lossy alphabet, and then their fraction of overlapping $k$-mers is computed into a Jaccard similarity. **B.** One option for `sencha compare-kmer-content` is to specify a pair of sequence files, and compute a background of $k$-mer similarty using randomly shuffled pairs. **C.** Another option for `sencha compare-kmer-content` is to do an all-by-all $k$-mer similarity comparison.](images/SVG/figure3.svg){#sfig:figure3 tag="figure3" width="100%"}


### Cell type predictions

![
Supplemental Figure 2: Cell databases built from degenerate protein alphabet $k$-mers can reliably identify cell types within species, across individuals.
**A.** Experimental set up of testing self:self lookup of cell types within the same organism. Build a cell type sequence bloom tree (SBT) database from a male mouse, then query with cells from the same male mouse, and return the top non-identical hit cell.
**B.** Experimental set up of testing male:male lookup of cell types within the same species, different individuals and same sex. Build a cell type (SBT) database from a male mouse, then query with cells from a different male mouse, and return the most similar cell.
**C.** Experimental set up of testing male:female lookup of cell types within the same species, different individuals and different sex. Build a cell type (SBT) database from a male mouse, then query with cells from a female mouse, and return the most similar cell.
**D.** Mean of dlassification metrics for self:self (left column), male:male (middle column), male:female (right column) cell type lookup, using different molecule types and $k$-mer sizes, highlighting the $k$-mer size that maximizes the mean for each metric and alphabet. x-axis, $k$-mer size in DNA space, i.e. a $k$-mer size of 21 corresponds to a an amino acid length of 7. y-axis, value of classification metric. Top row, adjusted rand score; bottom row, F1 score.
**E-G.** Heatmap of classification metrics for alphabets and $k$-mer sizes maximizing classification ability from (**D**), for each mouse:mouse experiment.
**H.** Mean of classification metrics across all three mouse:mouse experiments, highlighting the $k$-mer size that maximizes the mean for each metric and alphabet. Vertical lines, standard deviation of the mean. x-axis, $k$-mer size in DNA space. y-axis, value of classification metric. Left, adjusted rand score; right, F1 score.
**I.** Heatmap of classification metrics for alphabets and $k$-mer sizes maximizing classification ability from (**H**).
**J-L.** Confusion matrices of classification with best performing parameters from (**I**). x-axis, predicted cell label; y-axis, ground truth cell label.
**J.** DNA alphabet with $k$-mer size of 42.
**K.** Protein 20-letter alphabet with $k$-mer size of 27.
**L.** Dayhoff 6-letter amino acid encoding with $k$-mer size of 39.
](images/SVG/supplemental_figure2.svg){#sfig2:sfig2 tag="supplemental_figure2" width="100%"}


![Supplemental Figure 3: Cell databases built from degenerate protein alphabet $k$-mers can reliably identify cell types within species, across individuals.
**A.** Experimental set up of testing human:human lookup of cell types within species, across individuals. Build a cell type (SBT) database from one patient mouse, then query with cells from a different patient, and return the most similar cell.
**B.** Mean of classification metrics across human:human experiments, highlighting the $k$-mer size that maximizes the mean for each metric and alphabet. Vertical lines, standard deviation of the mean. x-axis, $k$-mer size in DNA space, i.e. a $k$-mer size of 21 corresponds to a an amino acid length of 7. y-axis, value of classification metric. Left, adjusted rand score; right, F1 score.
**C.** Molecules and $k$-mer sizes maximizing classification metrics from (**K**).
**D-F.** Confusion matrices of classification with best performing parameters from **E**. x-axis, predicted cell label; y-axis, ground truth cell label.
**D.** DNA alphabet with $k$-mer size of ---.
**E.** Protein 20-letter alphabet with $k$-mer size of ---.
**F.** Dayhoff 6-letter amino acid encoding with $k$-mer size of ---.
](images/SVG/supplemental_figure3.svg){#sfig3:sfig3 tag="supplemental_figure3" width="100%"}


### Benchmarking

Methods go here.


#### Computational



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

![**A.** Overview of the `kmermaid` pipeline. (**a**, **b**, **c**) `kmermaid` consists of a protein-coding prediction phase (**a**) that is invoked by the command `sencha translate`, a $k$-mer sketch computation phase (**b**) invoked by the command `sourmash sketch`, a signature similarity comparison phase (**c**) invoked by the command `sourmash compare`, and an optional database-creation phase (**d**) invoked by the command `sourmash index`. The coding prediction phase has three components: (1) six-frame translation, removal of stop-codon frames, and subsequent $k$-merization of RNA-sequencing reads; (2) a degenerate protein alphabet which allows for protein-coding detection from a wide variety of species; (3) a bloom filter containing known protein-coding sequences from a well annotated organism; and (4) computation of the Jaccard index of translated RNA-seq reading frames. The sketch computation phase involves randomly subsetting the degenerate peptide $k$-mers using a MinHash algorithm. The sketch comparison phase consists of computing the Jaccard intersection of MinHashed degenerate peptide $k$-mers between all pairs of samples.](images/SVG/supplementary_figure3.svg){#fig:sfig3 width="100%"}


![
Supplemental Figure X.
**A.** Overview of `nf-core/kmermaid` pipeline to compare DNA/RNA/protein sequences on $k$-mer content.
1. If input is bam, extract per-cell sequences using `bam2fasta percell`.
2. Predict amino acid sequence of each RNA-seq read using `sencha translate`.
3. Randomly subsample amino acid $k$-mers via MinHash using `sourmash sketch`.
4. Compare all $k$-mer sketches to one another using `sourmash compare` to compute cell-cell Jaccard similarities.
5. Build sequence bloom tree using `sourmash index`.
6. Build k-nearest neighbor graph using sequence bloom tree.
7. Build UMAP off of KNN.
](images/SVG/kmermaid_workflow.svg){#fig:kmermaid width="100%"}



![
Supplemental Figure X.
**B.** Overview of `czbiohub/nf-predictorthologs` pipeline to query putative function of protein sequences.
1. If input is bam, must also have a convert bam reads to raw fastq files using the `samtools fastq` subcommand (samtools version 1.9). If input is fastqs, go directly to second step.
2. Trim adapters, poly-A, polyG using the `fastp` tool.
3. Predict protein-coding sequence using khtools extract_coding, using conservative UniProt/SwissProt manually curated database as examples of known protein-coding sequences, for most stringent definition of protein-coding.
4. Query predicted protein in permissive NCBI RefSeq non-redundant protein database for most complete search query.
](images/SVG/predictorthologs_workflow.svg){#fig:predictorthologs width="100%"}




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










<!--

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


<!-- - Overview of kmermaid pipeline
  - Comparison of tissue across species
    - Partition reads to coding/noncoding bins
    - MinHash the Dayhoff-encoded coding sequences
    - Jaccard similarity on the MinHashes
- Which reads are found to have coding features but didn’t map to the genome?
- Do these features map to novel genes or gene fusions?
- Kmers can find correct reading from of RNA-seq reads
  - Human peptides → human, chimp, bonobo, orangutan, gorilla, macaque, mouse, opossum, playtpus, chicken RNAseq from Brawand2011 data
- Comparison to other methods: RNASamba [@doi:10.1101/620880] -->

<!-- ### Figure 3 -- $k$-mers can pull out only reads from transcription factors and Amniotes can be compared on the MinHashes of their protein-coding sequences -->

<!-- ![Figure 3.](images/figure3.svg){#fig:fig3 width="100%"} -->


<!-- ### Some potential references

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

- Erkenbrack, E. M., Maziarz, J. D., Griffith, O. W., Liang, C., Chavan, A. R., Nnamani, M. C., & Wagner, G. P. (2018). The mammalian decidual cell evolved from a cellular stress response. PLOS Biology, 16(8), e2005594–27. http://doi.org/10.1371/journal.pbio.2005594 [@doi:10.1371/journal.pbio.2005594] -->

<!-- # Discussion --> -->
