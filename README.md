# Left-to-Right Dependency Parsing with Bottom-up Hierarchical Pointer Networks
This repository includes the code of the left-to-right dependency parser with Bottom-up Hierarchical Pointer Networks described in the paper [Dependency Parsing with Bottom Hierarchical Pointer Networks](https://arxiv.org/abs/2105.09611). The implementation is based on the dependency parser by Liu et al. (2019) (https://github.com/ntunlp/ptrnet-depparser) and reuses part of its code, including data preparation and evaluating scripts.


## Requirements
Python 2.7, PyTorch >=0.4.1, Gensim >= 0.12.0


## Experiments
1. Update `examples/run.sh` with the paths for data and embeddings. 
2. Run command `./examples/run.sh <log_name>`.


## Citation
``` 
@misc{fernándezgonzález2021dependency,
      title={Dependency Parsing with Bottom-up Hierarchical Pointer Networks}, 
      author={Daniel Fernández-González and Carlos Gómez-Rodríguez},
      year={2021},
      eprint={2105.09611},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## Acknowledgments

We acknowledge the European Research Council (ERC), which has funded this research under the European Union’s Horizon 2020 research and innovation programme (FASTPARSE, grant agreement No 714150), MINECO (ANSWER-ASAP, TIN2017-85160-C2- 1-R), Xunta de Galicia (ED431C 2020/11), and Centro de Investigación de Galicia ''CITIC'', funded by Xunta de Galicia and the European Union (ERDF - Galicia 2014-2020 Program), by grant ED431G 2019/01.
                                                                                                                                   
