---
title: Text2Trait-HARVEST
summary: A community effort to turn scientific literature into usable knowledge
tags:
- plant-functional-genomics
date: "2025-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Brightlands Campus Greenport Venlo
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/kumar_s_singh
url_code: ""
url_pdf: "./Poster/NWO-Groot/poster1.pdf"
url_slides: ""
url_video: ""

posters: 
  - 
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Abstract
Most biological knowledge is trapped in text and figures, scattered across journals, and hard to reuse. Current databases capture only a fraction of this vast knowledge base. Text2Trait unlocks this hidden knowledge to accelerate breeding, crop protection, and resilience. Built on an AI-assisted, Human-in-the-loop Actionable Research and Vocabulary Extraction Technology (HARVEST), it acts like a literature telescope. It reads at scale, extracts research knowledge, and assembles the results into a transparent knowledge graph that can be queried conversationally like a chat box. In agriculture systems, it becomes a genotype-to-phenotype accelerator by fusing diverse datasets with published evidence, prioritising targets for editing, and proposing assays that close knowledge gaps. Trained on a diverse, species-agnostic corpus of open-access plant literature, Text2Trait scales naturally to crops and powers decision support for breeders and farmers, where the knowledge model can be continuously fine-tuned based on measurable KPIs and community feedback.

## Objective
The research problem we tackle with Text2Trait and its underlying Human-in-the-loop Actionable
Research and Vocabulary Extraction Technology (HARVEST) is that how can we transform unstructured scientific literature including text, tables, and figures into a FAIR, provenance-rich KG that captures entities (genes, regulators, variants, metabolites, traits/QTLs, stresses) and typed relations (regulates/influences/part_of, negation/speculation etc.), at full-article scale, with verifiable evidence so that it can benefit downstream applications (Multi-omics integration, pathway inference, gene/metabolite annotations, GWAS)?

## Research Hypothesis
We hypothesize that a schema-guided, full-text gold-standard-trained extractor model will
yield a knowledge graph that significantly improves genotype-to-phenotype inference, compared to abstract-only and co-occurrence methods.
