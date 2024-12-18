# PersianIdioms and Fa-En Idiom Translation Parallel Datasets

This repository includes the official resources of [A Comparative Study of LLMs, NMT Models, and Their Combination in Persian-English Idiom Translation](https://arxiv.org/abs/2412.09993).

## Abstract
Large language models (LLMs) have shown superior capabilities in translating figurative language compared to neural machine translation (NMT) systems. However, the impact of different prompting methods and LLM-NMT combinations on idiom translation has yet to be thoroughly investigated. This paper introduces two parallel datasets of sentences containing idiomatic expressions for Persian→English and English→Persian translations, with Persian idioms sampled from our PersianIdioms resource, a collection of 2,200 idioms and their meanings. Using these datasets, we evaluate various open- and closed-source LLMs, NMT models, and their combinations. Translation quality is assessed through idiom translation accuracy and fluency. We also find that automatic evaluation methods like LLM-as-a-judge, BLEU and BERTScore are effective for comparing different aspects of model performance. Our experiments reveal that Claude-3.5-Sonnet delivers outstanding results in both translation directions. For English→Persian, combining weaker LLMs with Google Translate improves results, while Persian→English translations benefit from single prompts for simpler models and complex prompts for advanced ones.

## Datasets

PersianIdioms:
> A comprehesive dataset containing 2200 Persian idioms and their meaning, sourced from the online dictionary "Abadis", with 700 idioms further enriched with contextual examples.

Parallel Datasets:
> An En->Fa and Fa->En dataset each containing 200 sentences containing idiomatic expressions and their gold translation.

Evaluation Guide Provided to Human Annotators:
> Further instructions and examples provided to annotators are available in "Evaluation_Guide.pdf".
