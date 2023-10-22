# Text Description Generation from Tabular Data

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project aims to transform tabular data into human-readable textual descriptions. Given a table of data, like biomedical test results, the goal is to summarize the information in a comprehensible textual format. For instance, given a table listing the names, party-affiliation, ordinal number, and date of birth of all American presidents, the objective is to generate a sentence such as "Barack Obama, born in 1961, was a democrat and became the 44th President of the United States".

## Overview

Utilizing a large dataset of tabular data [1], we explore text generation methodologies employing large language models like GPT2 [2] and LLaMA2 [3]. The project encompasses not only the training of text generation models but also the evaluation of the generated sentences employing various text comparison techniques.

## Directories

- `data/`: Contains the dataset files.
- `models/`: Holds the trained models.
- `notebooks/`: Jupyter notebooks for exploratory analysis and experimentation.
- `src/`: Source code for the project.

## References

- [1] [ToTTo Dataset](https://github.com/google-research-datasets/totto)
- [2] [Exploration of GPT Techniques](https://life-extension.github.io/2020/05/27/GPT%E6%8A%80%E6%9C%AF%E5%88%9D%E6%8E%A2/language-models.pdf)
- [3] [LLaMA2 Paper](https://arxiv.org/abs/2307.09288)

## Getting Started

(Add instructions for setting up and running the project here.)

## Contributors

(Add a list of contributors or maintainers here.)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
