# Left-to-Right Dependency Parsing with Bottom-up Hierarchical Pointer Networks
This repository includes the code of the left-to-right dependency parser with Bottom-up Hierarchical Pointer Networks described in the paper [Dependency Parsing with Bottom Hierarchical Pointer Networks](https://arxiv.org/abs/2105.09611). The implementation is based on the dependency parser by Liu et al. (2019) (https://github.com/ntunlp/ptrnet-depparser) and reuses part of its code, including data preparation and evaluating scripts.


## Requirements
Python 2.7, PyTorch >=0.4.1, Gensim >= 0.12.0


## Experiments
1. Update `examples/run.sh` with the paths for data and embeddings. 
2. Run command `./examples/run.sh <log_name>`.


## Citation
``` 
@article{FERNANDEZGONZALEZ2023494,
title = {Dependency parsing with bottom-up Hierarchical Pointer Networks},
journal = {Information Fusion},
volume = {91},
pages = {494-503},
year = {2023},
issn = {1566-2535},
doi = {https://doi.org/10.1016/j.inffus.2022.10.023},
url = {https://www.sciencedirect.com/science/article/pii/S1566253522001993},
author = {Daniel Fernández-González and Carlos Gómez-Rodríguez},
keywords = {Natural language processing, Computational linguistics, Parsing, Dependency parsing, Neural network, Deep learning},
abstract = {Dependency parsing is a crucial step towards deep language understanding and, therefore, widely demanded by numerous Natural Language Processing applications. In particular, left-to-right and top-down transition-based algorithms that rely on Pointer Networks are among the most accurate approaches for performing dependency parsing. Additionally, it has been observed for the top-down algorithm that Pointer Networks’ sequential decoding can be improved by implementing a hierarchical variant, more adequate to model dependency structures. Considering all this, we develop a bottom-up oriented Hierarchical Pointer Network for the left-to-right parser and propose two novel transition-based alternatives: an approach that parses a sentence in right-to-left order and a variant that does so from the outside in. We empirically test the proposed neural architecture with the different algorithms on a wide variety of languages, outperforming the original approach in practically all of them and setting new state-of-the-art results on the English and Chinese Penn Treebanks for non-contextualized and BERT-based embeddings.}
}
```

## Acknowledgments

We acknowledge the European Research Council (ERC), which has funded this research under the European Union’s Horizon 2020 research and innovation programme (FASTPARSE, grant agreement No 714150), MINECO (ANSWER-ASAP, TIN2017-85160-C2- 1-R), Xunta de Galicia (ED431C 2020/11), and Centro de Investigación de Galicia ''CITIC'', funded by Xunta de Galicia and the European Union (ERDF - Galicia 2014-2020 Program), by grant ED431G 2019/01.
                                                                                                                                   
