---
layout: page
title: Capstone Project
permalink: /tad/
---

	
<h2>Tokenizer Analysis Dashboard (TAD)</h2>


The aim of this project is to develop a web-based interface for analysing and comparing LLM tokenisers, with a focus on South African languages. Tokenisation is a crucial preprocessing step in Natural Language Processing (NLP), where text is split into smaller units before being processed by a language model. Different tokenisers behave very differently across languages and this can affect LLM performance. In this project, students will develop an interactive dashboard that allows users to compare multiple tokenisers across a range of metrics, such as how many tokens are produced for a sentence, whether words are split into meaningful subword units, how consistently similar words are segmented, and how efficiently different languages are represented. The platform should focus on interactive visualisations of tokenisation behaviour across 9 South African languages (Afrikaans, English, isiXhosa, isiZulu, Sesotho, Sepedi, Setswana, siSwati, Xitsonga), to help users (who would be researchers or machine learning engineers) explore the strengths and weaknesses of different tokenisers. This project will provide students with hands-on experience in data visualisation, web development, NLP, and tokenisation, which is an important part of the LLM pipeline.


<h2>Resources</h2>

* [Week 1 slides: Introducing the project](https://drive.google.com/file/d/1pYvApuJGAedVSeoI3s7Zb9cJkjSQH9Z-/view?usp=sharing)
* [Hugging Face Tokenizers library](https://huggingface.co/docs/tokenizers/index)
* [Tokenizers example](https://drive.google.com/file/d/1L3XUcZo3BUm5MHoWjaw3ZcNDe8RG2pnb/view?usp=sharing)
* [Week 2 slides: Data and Morphological Metrics](https://drive.google.com/file/d/1LSvqZhAg3x-YyJbgfCp2j3y4lPOEKGKV/view?usp=sharing)

<h2>Datasets</h2>

(Links to be provided soon.)

* [**FLORES (dev set)**](https://drive.google.com/file/d/1pvF-h7-P34MsGO6hh54PrlchRBq1W1G_/view?usp=sharing) – used for efficiency metrics (token count, fertility, compression, token premium). The same 997 sentences translated into all 11 official South African languages.
* [**NCHLT**](https://github.com/darthskyy/morph_segment_extension/tree/main/.words_seg_gold) – used for linguistic metrics (morpheme boundary alignment). A corpus in which linguists have manually segmented every word into morphemes.

<h2>Example websites</h2>

* [OpenAI tokenizer demo](https://platform.openai.com/tokenizer)
* [Rugby data visualisation](https://grubbr.app/)
* [Configurable leaderboard example](https://huggingface.co/spaces/BabyLM-community/BabyLM-Leaderboard-2026)

<h2>Additional reading</h2>

The following academic papers describe metrics used by researchers to analyse tokenizers.

* [Paper: Do All Languages Cost the Same? Tokenization in the Era of Commercial Language Models](https://aclanthology.org/2023.emnlp-main.614.pdf)
* See Section 4.4 for linguistic metrics: [Paper: The Learning Dynamics of Subword Segmentation for Morphologically Diverse Languages](https://aclanthology.org/2025.ijcnlp-long.36.pdf)
* MorphScore metric: [Paper: Why do language models perform worse for morphologically complex languages?](https://aclanthology.org/2025.coling-main.441.pdf)


<h2>Contact</h2>

* Supervisor/Client: Francois Meyer \
  Email: francois.meyer@uct.ac.za \
  Office: Room 314.10, Computer Science Building

* Tutor: Tadiwa Nyakonda \
  Email: NYKTAD002@myuct.ac.za
