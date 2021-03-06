## STEM-NER 60K Dataset

#### This repository hosts data as a follow-up study to the following publications

D'Souza, J., Hoppe, A., Brack, A., Jaradeh, M., Auer, S., & Ewerth, R. (2020). [The STEM-ECR Dataset: Grounding Scientific Entity References in STEM Scholarly Content to Authoritative Encyclopedic and Lexicographic Sources.](https://aclanthology.org/2020.lrec-1.268/) In Proceedings of The 12th Language Resources and Evaluation Conference (pp. 2192–2203). European Language Resources Association.

Brack, A., D’Souza, J., Hoppe, A., Auer, S., Ewerth, R. (2020). [Domain-Independent Extraction of Scientific Concepts from Research Articles](https://doi.org/10.1007/978-3-030-45439-5_17). In: , et al. Advances in Information Retrieval. ECIR 2020. Lecture Notes in Computer Science(), vol 12035. Springer, Cham. https://doi.org/10.1007/978-3-030-45439-5_17

Supporting dataset link [https://data.uni-hannover.de/dataset/stem-ecr-v1-0](https://data.uni-hannover.de/dataset/stem-ecr-v1-0)

#### Description

Roughly 60,000 titles and abstracts of scholarly articles with the CC-BY redistributable license were downloaded from Elsevier. The articles spanned 10 STEM domains which were the most prolific on Elsevier viz., *Agriculture*, *Astronomy*, *Biology*, *Chemistry*, *Computer Science*, *Earth Science*, *Engineering*, *Material Science*, and *Mathematics*.
The STEM NER system reported in the publication above was applied on these articles. An automatically extracted dataset of 4 typed entities, viz., *Process*, *Method*, *Material*, and *Data* was created.

| Domain | Articles | process | method | material | data |
| --- | --- | --- | --- | --- | --- |
| Agriculture | 4,944 | 20,532 | 3,252 | 62,043 | 33,608 |
| Astronomy | 15,003 | 31,104 | 10,423 | 55,753 | 97,011 |
| Biology | 9,038 | 54,029 | 6,777 | 100,454 | 43,418 |
| Chemistry | 5,232 | 18,185 | 6,044 | 48,779 | 30,596 |
| Computer Science | 5,389 | 17,014 | 13,650 | 35,554 | 33,575 |
| Earth Science | 4,363 | 28,432 | 5,129 | 56,571 | 50,211 |
| Engineering | 2,441 | 12,705 | 3,293 | 24,633 | 24,238 |
| Materials Science | 2,144 | 10,102 | 2,437 | 23,054 | 16,981 |
| Mathematics | 1,765 | 8,002 | 1,941 | 11,381 | 15,631 |
| Medicine | **15,054** | **89,637** | **19,580** | **148,059** | **134,249** |
| -- | -- | -- | -- | -- | -- |
| Total | 59,984 | 272,728 | 58,876 | 530,727 | 445,943 |

#### What this repository contains?

Aggregated lists of *Process*, *Method*, *Material*, and *Data* entities with respective occurrence counts extracted from 59,984 scholarly publications organized per the 10 STEM domains considered.

Additionally, the list of Elsevier CC-BY articles used in this study are provided in the `raw-data` directory of the repository.

#### Contact

For the publication' Abstracts considered to make this dataset; otherwise for related questions, comments, feedback, and interests in collaborations, please contact me at: jennifer (dot) dsouza (at) tib (dot) eu