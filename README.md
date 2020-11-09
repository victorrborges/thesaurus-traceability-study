# Using a Thesaurus in Traceability Recovery Between Bug Reports and Test Cases

Repository of my undergraduate thesis "Using a Thesaurus in Traceability Recovery Between Bug Reports and Test Cases"

## Abstract

The software development process generates several textual artifacts that are mostly written in natural language. Establishing connections between these artifacts can have a positive impact on performing a variety of tasks, including understanding and maintaining code. The use of Information Retrieval (IR) and Machine Learning (AM) techniques in order to recover the traceability between bug reports and test cases has already been proposed, however, the results indicate the need for improvements, especially to deal with the differences in vocabulary. In this paper, we created a Vocabulary Unifier using a thesaurus to expand the vocabulary encountered in bug reports, aiming to unify their terms in line with the terms from the test cases, observing  slight improvements in recall and precision rates.

This repository is organized as follows:

  - [figures] - all the figures used in the paper
  - [scenarios_output] - entire outputs for each scenario / sub scenario
  - [sheets] - sheets used to create tables displayed in the paper
  - [vocabulary_unifier] - the algorithm used to produce the expanded set of bug reports for each scenario

## Scenarios description

The scenarios are described as follows:

| Label | API | Expansion Approach | Sub Scenarios |
| ------ | ------ | ------ | ------ |
| SB | - | - | - |
| SW | Wordnet | - | SW-1 to SW-5 |
| SC | ConceptNet | - | SC-1 to SC-5 |
| SW-n | Wordnet | Nouns | SW-n-1 to SW-n-5 |
| SC-n | ConceptNet | Nouns | SC-n-1 to SC-n-5 |
| SW-s | Wordnet | Scope | SW-s-1 to SW-s-5 |
| SC-s | ConceptNet | Scope | SC-s-1 to SC-s-5 |
| SW-ns | Wordnet | Both | SW-ns-1 to SW-ns-5 |
| SC-ns | ConceptNet | Both | SC-ns-1 to SC-ns-5 |

[figures]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/figures>
[scenarios_output]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/scenarios_output>
[sheets]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/sheets>
[vocabulary_unifier]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/vocabulary_unifier>
