<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: Reproducibility Study for Span Type Characteristics

This project aims to reproduce the metrics reported by the paper,
*Dissecting Span Identification Tasks with Performance Prediction* (Papay, et
*al, 2020) with a few changes:

- I will only reproduce the span characteristics (length, distinctiveness,
  etc.) to check if the span analyzer is working as intended.
- I will add a few datasets to increase the breadth of this study. In particular, I'll
  be checking some of the nested NER datasets from Yu, et al's work (2020) on
  *Named Entity Recognition as Dependency Parsing*.


## 📋 project.yml

The [`project.yml`](project.yml) defines the data assets required by the
project, as well as the available commands and workflows. For details, see the
[spaCy projects documentation](https://spacy.io/usage/projects).

### ⏯ Commands

The following commands are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run).
Commands are only re-run if their inputs have changed.

| Command | Description |
| --- | --- |
| `install` | Install dependencies |
| `parse-riqua` | Parse the RiQuA (Rich Quotation Analysis) quotation dataset into the spaCy format. |
| `analyze-riqua` | Get span analysis for the RiQuA quotation dataset. |
| `parse-parc` | Parse the PARC (Penn Attribution Relation Corpus) dataset into the spaCy format. |

### ⏭ Workflows

The following workflows are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run)
and will run the specified commands in order. Commands are only re-run if their
inputs have changed.

| Workflow | Steps |
| --- | --- |
| `parse-all` | `parse-riqua` |

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->