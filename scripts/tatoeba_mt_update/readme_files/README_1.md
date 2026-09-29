
# Dataset Card for The Tatoeba Translation Challenge

**Please note that this dataset is intended strictly for evaluation and benchmarking purposes. Training models on this dataset, or including it in automatically collected web-scale training corpora, may lead to benchmark contamination and invalidate evaluation results.**

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Supported Tasks and Leaderboards](#supported-tasks-and-leaderboards)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-fields)
  - [Data Splits](#data-splits)
- [Dataset Creation](#dataset-creation)
  - [Curation Rationale](#curation-rationale)
  - [Source Data](#source-data)
  - [Annotations](#annotations)
  - [Personal and Sensitive Information](#personal-and-sensitive-information)
- [Considerations for Using the Data](#considerations-for-using-the-data)
  - [Social Impact of Dataset](#social-impact-of-dataset)
  - [Discussion of Biases](#discussion-of-biases)
  - [Other Known Limitations](#other-known-limitations)
- [Additional Information](#additional-information)
  - [Dataset Curators](#dataset-curators)
  - [Licensing Information](#licensing-information)
  - [Citation Information](#citation-information)
  - [Contributions](#contributions)

## Dataset Description

- **Homepage:** https://github.com/Helsinki-NLP/Tatoeba-Challenge/
- **Repository:** https://github.com/Helsinki-NLP/Tatoeba-Challenge/
- **Paper:** [The Tatoeba Translation Challenge – Realistic Data Sets for Low Resource and Multilingual MT](https://aclanthology.org/2020.wmt-1.139/)
- **Leaderboard:**
- **Point of Contact:** [Jörg Tiedemann](mailto:jorg.tiedemann@helsinki.fi)

### Dataset Summary

The Tatoeba Translation Challenge is a multilingual data set of machine translation benchmarks derived from user-contributed translations collected by [Tatoeba.org](https://tatoeba.org/) and provided as parallel corpus from [OPUS](https://opus.nlpl.eu/). This dataset includes test and development data sorted by language pair. It includes test sets for hundreds of language pairs and is continuously updated. Please, check the version number tag to refer to the release that your are using.

### Supported Tasks and Leaderboards

The translation task is described in detail in the [Tatoeba-Challenge repository](https://github.com/Helsinki-NLP/Tatoeba-Challenge) and covers various sub-tasks with different data coverage and resources. [Training data](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/data/README.md) is also available from the same repository and [results](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/results/tatoeba-results-all.md) are published and collected as well. [Models](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/results/tatoeba-models-all.md) are also released for public use and are also partially available from the [huggingface model hub](https://huggingface.co/Helsinki-NLP).


### Languages

The data set covers hundreds of languages and language pairs and are organized by ISO-639-3 languages. The current release covers the following languages:
