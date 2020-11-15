# Using a Thesaurus in Traceability Recovery Between Bug Reports and Test Cases

Repository of my undergraduate thesis "Using a Thesaurus in Traceability Recovery Between Bug Reports and Test Cases".

## Abstract

The software development process generates several textual artifacts that are mostly written in natural language. Establishing connections between these artifacts can have a positive impact on performing a variety of tasks, including code understanding and maintaining. The use of Information Retrieval (IR) and Machine Learning (ML) techniques in order to recover the traceability between bug reports and test cases has already been proposed, however, the results indicated the need for improvements, especially to deal with the differences in vocabulary. In this paper, we created a Vocabulary Unifier using a thesaurus to expand the vocabulary encountered in bug reports, aiming to unify their terms in line with the terms from the test cases. We evaluated the techniques comparing its recall, precision and f2-score rates with those reached by previous works, observing slight improvements in its values.

## Repository map

This repository is organized as follows:

  - [figures] - all the figures used in the paper
  - [scenarios_output] - entire outputs for each scenario / sub scenario
  - [sheets] - sheets used to create tables displayed in the paper
  - [vocabulary_unifier] - the algorithm used to produce the expanded set of bug reports for each scenario

## Scenarios description

The scenarios are described as follows:

| Expansion Technique | API | Expansion Approach | Scenarios |
| ------ | ------ | ------ | ------ |
| BASE | - | - | - |
| WFE | Wordnet | - | WFE-1 to WFE-5 |
| CFE | ConceptNet | - | CFE-1 to CFE-5 |
| WNE | Wordnet | Nouns | WNE-1 to WNE-5 |
| CNE | ConceptNet | Nouns | CNE-1 to CNE-5 |
| WSE | Wordnet | Scope | WSE-1 to WSE-5 |
| CSE | ConceptNet | Scope | CSE-1 to CSE-5 |
| WNSE | Wordnet | Nouns and Scope | WNSE-1 to WNSE-5 |
| CNSE | ConceptNet | Nouns and Scope | CNSE-1 to CNSE-5 |

[figures]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/figures>
[scenarios_output]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/scenarios_output>
[sheets]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/sheets>
[vocabulary_unifier]: <https://github.com/victorrborges/thesaurus-traceability-study/tree/main/vocabulary_unifier>
