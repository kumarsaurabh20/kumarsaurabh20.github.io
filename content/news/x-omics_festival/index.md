---
title: (15-04-22) X-omics Festival 2022 best scientific poster award
summary: We have presented a poster in the fourth edition of the X-omics festival “the future of multi-omics research is now!” on Monday April 11th 2022 https://x-omics.nl/festival/festival-2022. It was a great event and very well organized. Scientific poster session allowed us to network with others working with similar goals and our poster on MEANtools, Integrative omics for the discovery of biosynthetic pathways using MEANtools (MEtabolite ANticipation tools) was awarded the best poster prize of 2022. 

tags:
- omics
- X-omics
- data-integration
- pathway-discovery
date: "2022-04-014T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Scientific poster award
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/kumar_s_singh
url_code: ""
url_pdf: "/news/x-omics_festival/X-omics_2022_poster.pdf"
url_slides: ""
url_video: ""

posters: ""
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Authors
Kumar Saurabh Singh a,b, Hernando G. Suarez Duran a, Justin J. J. van der Hooft a, Saskia C. M. van Wees b, Marnix H. Medema a 

## Title
Integrative omics for the discovery of biosynthetic pathways using MEANtools (MEtabolite ANticipation tools) 

## Affiliation
Bioinformatics Group, Department of Plant Sciences, Wageningen University & Research, 6708 PB Wageningen, the Netherlands.
Plant-Microbe Interactions group, Utrecht University, 3584 CH Utrecht, the Netherlands. 

## Submission topic
Integrative omics (genomics, transcriptomics & metabolomics) 

## Abstract 

Single-omics-based studies have helped for a long time in elucidating crucial genes and metabolites in multiple biological systems. Genomics, transcriptomics, and metabolomics studies have enabled us to understand and measure, both qualitatively and quantitatively, the fluctuations in gene expression and abundance of diverse classes of molecules in a system-wide manner. Recently, transcriptomics and metabolomics have been used in combination to understand the complex architecture of plant biosynthetic pathways with a higher degree of precision. Identification of metabolites that control transcription factors in E. coli (Lempp et al. 2019), characterization of essential metabolic pathways involved in the tick response to A. phagocytophilum infection (Villar et al. 2015), identification of a gene cluster involved in falcarindiol biosynthesis (Jeon et al. 2020), etc., are some of the notable examples of results for which omics integration was crucial. However, such studies have thus far been limited to targeted analyses of specific microbial or plant pathways based on prior knowledge, while systematic/unsupervised and de novo pathway identification methods based on integrative omics are still largely lacking. To tackle this, novel opportunities can be found in strategies based on the prediction of metabolic pathways through simultaneous observations in multiple omics layers that are then used to generate a single hypothesis. However, no systematic, unsupervised method has been developed so far that integrates transcriptomic, metabolomic, and genomic data for untargeted specialized metabolic pathway discovery.  

Here, we present MEANtools, a python-based workflow that integrates genomic, transcriptomic, and metabolomic data with enzymatic reaction databases to predict metabolic pathways, by identifying mass differences between metabolites that are co-abundant with transcripts whose enzymatic products are capable of catalyzing biosynthetic reactions. MEANtools first identifies strongly correlated transcript-metabolite pairs and then annotates these pairs with reactions by querying the RetroRules database. The annotated pairs represent an enzyme-encoding transcript with a protein domain capable of catalyzing an enzymatic reaction that has a correlated metabolite as a substrate or product. To further expand the chemical transformation search space of MEANtools, the RetroRules database has been further expanded by including KEGG (Kyoto Encyclopedia of Genes and Genomes) orthology (Nakaya et al. 2013) and Rhea (Alcantara et al. 2012) reaction databases. MEANtools also allows fine-tuning of the enzymatic reactions that are retrieved from the database to generate more plausible or easier-to-validate metabolic pathway predictions, for example by retrieving only experimentally validated reactions, or by selecting taxa of origin.  

Reconstruction of co-expression modules using the transcriptomics data is essential to identify groups of genes involved in the same metabolic pathway. MEANtools identifies such co-expression clusters and allows users to select only genes present in co-expression modules which improves confidence in the overall biosynthetic pathway predictions. We further propose that prediction accuracy can be enhanced by integrating strategies that allow associating temporal and spatial gene expression levels, as represented in the gene regulatory networks (GRNs), with metabolite abundance levels across samples to identify potentially causal links. This will infer regulation of the different genes encoding enzymes in biosynthetic pathways. 

 


