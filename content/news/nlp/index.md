---
title: (02-12-25) Pilot workshop on Natural Language Processing by eScience Center Netherlands  
summary: I recently participated in the Natural Language Processing (NLP) Pilot Workshop organized by the Netherlands eScience Center. The workshop brought together researchers, practitioners, and domain experts interested in applying NLP techniques to real-world research problems ...

tags:
- academic life
- Assitant Professor
- Brightlands Future Farming Institute
- Maastricht University
- natural-language-processing
- literature mining
date: "2025-12-02"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: NLP
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/kumar_s_singh
url_code: ""
url_pdf: ""
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

## Fundamentals of Natural Language Processing (NLP) Pilot Workshop

**Organiser:** Netherlands eScience Center
**Format:** hands-on pilot workshop (2–3 December 2025)

I participated in the *Fundamentals of Natural Language Processing (NLP)* pilot workshop organised by the Netherlands eScience Center. The workshop combined short lectures with live coding, interactive exercises, and collaborative note-taking via a shared Carpentries-style document under a CC BY license, with an explicit Code of Conduct and clear procedures for getting help (e.g., “pink paper” for questions and “yellow paper” when finished). The programme was designed as a practical introduction to core NLP concepts and modern model architectures, moving from foundational text processing to embeddings and transformers, and concluding with applied examples using large language models (LLMs), evaluation, and discussion of limitations such as bias and hallucination.

**Day 1 (2 December 2025)** focused on establishing solid fundamentals. The morning covered an introduction to NLP, the idea of *language as data*, and how linguistic ambiguity and context shape meaning. A key takeaway was the importance of formalising the research question before selecting methods—understanding when a simple approach may be sufficient and how to validate results. Through hands-on exercises, we explored tokenization challenges (including non-whitespace languages such as Chinese), distinctions between *word types* and *word tokens*, and practical text processing using *spaCy*. Using the *Frankenstein* text as a working corpus, we practiced building basic pipelines: reading and cleaning text, tokenization, filtering (e.g., alphanumeric tokens), extracting verbs and sentences, and identifying named entities. The day also provided a primer on linguistics (pragmatics, semantics, syntax, morphology, phonology/phonetics), reinforcing why ambiguity is not an “edge case” but a structural property of language that affects downstream modelling. In the afternoon, the workshop transitioned to *word embeddings*, including conceptual understanding of Word2Vec, cosine similarity, and exploring pre-trained embeddings (e.g., Google News vectors). We also trained a small Word2Vec model on book text to understand the mechanics of training, parameter choices (window size, vector size), and practical limitations of small corpora. The day concluded with exercises that connected theory to real-world use (NLP tools we use daily), computing corpus statistics with spaCy (e.g., frequent verbs, entity counts), designing supervised task input/output pairs, and identifying ambiguity types in example sentences.

**Day 2 (3 December 2025)** introduced transformer-based NLP and modern workflows. We discussed limitations of Word2Vec (fixed vocabulary, one static vector per word, limited context sensitivity) and then moved to the *transformer* conceptually (encoder/decoder structure, attention, contextual representation). We explored *BERT* as an encoder model, including how tokenization affects model inputs (token IDs and subword tokens), how output representations are stored in *last hidden state*, and why contextual embeddings differ for the same word in different contexts (polysemy). Practical sessions included using Hugging Face *pipelines* for fill-mask tasks, sentiment classification, and rapid prototyping of text classification tasks. We also covered model evaluation using standard metrics (precision/recall/F1 and classification reports), and reflected on what performance numbers mean in practice (e.g., behaviour on neutral class). The workshop then expanded to LLM usage, including local LLM interaction concepts and the role of decoding hyperparameters (temperature, top-k, top-p), plus hands-on examples illustrating hallucination risks and social/representational bias. This day was particularly valuable for developing an intuition for what modern NLP models can and cannot do reliably, and how to design prompts and evaluation workflows that reduce failure modes.

From a professional perspective, the workshop aligns strongly with my ongoing interest in **AI-assisted knowledge extraction and literature mining**. The practical coverage of spaCy pipelines, named entity recognition concepts, and transformer-based classification connects directly to my work on building human-in-the-loop curation pipelines and structured knowledge representations (e.g., workflows similar in spirit to HARVEST/Text2Trait-style literature extraction). The emphasis on task formulation, supervised vs. unsupervised learning, evaluation, and known limitations (bias, hallucinations, outdated knowledge) provides a useful framework for designing robust NLP components in research software—especially when aiming to build trustworthy, reproducible pipelines for scientific text mining and evidence extraction.

The feedback collected during the workshop highlighted several strengths: strong instructor enthusiasm, a practical coding-first approach, well-paced afternoon sessions, the value of including linguistic theory, and the usefulness of collaborative documentation for staying on track. Common improvement suggestions included clearer pre-workshop guidance on required Python level, more robust environment support (especially for Windows and dependency management), providing notebooks or a reference notebook afterwards, and adding more in-line explanation of code rationale during exercises. Overall, the workshop provided a well-balanced introduction to NLP fundamentals and modern transformer workflows, with immediate applicability to research contexts that rely on scalable literature processing, classification, and structured information extraction.
