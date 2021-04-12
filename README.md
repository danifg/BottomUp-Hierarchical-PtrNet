# Left-to-Right Dependency Parsing with Bottom-up Hierarchical Pointer Networks
This repository includes the code of the left-to-right dependency parser with Bottom-up Hierarchical Pointer Networks described in ACL paper [Dependency Parsing with Bottom Hierarchical Pointer Networks](https://arxiv.org/abs/). The implementation is based on the dependency parser by Liu et al. (2019) (https://github.com/ntunlp/ptrnet-depparser) and reuses part of its code, including data preparation and evaluating scripts.


## Requirements
Python 2.7, PyTorch >=0.4.1, Gensim >= 0.12.0


## Experiments
1. Update `examples/run.sh` with the paths for data and embeddings. 
2. Run command `./examples/run.sh <log_name>`.


## Citation
``` 
    @inproceedings{fernandez-gonzalez-gomez-rodriguez-2019-left,
                title = "Left-to-Right Dependency Parsing with Pointer Networks",
		            author = "Fern{\'a}ndez-Gonz{\'a}lez, Daniel  and G{\'o}mez-Rodr{\'\i}guez, Carlos",
			                booktitle = "Proceedings of the 2019 Conference of the North {A}merican Chapter of the Association for Computational    Linguistics: Human Langua\
ge Technologies, Volume 1 (Long and Short Papers)",
            month = jun,
	                year = "2019",
			            address = "Minneapolis, Minnesota",
				                publisher = "Association for Computational Linguistics",
						            url = "https://www.aclweb.org/anthology/N19-1076",
							                doi = "10.18653/v1/N19-1076",
									            pages = "710--716"
										                }
```

## Acknowledgments

We acknowledge the European Research Council (ERC), which has funded this research under the European Union’s Horizon 2020 research and innovation programme (FASTPARSE, grant agreement No 714150), MINECO (ANSWER-ASAP, TIN2017-85160-C2- 1-R), Xunta de Galicia (ED431C 2020/11), and Centro de Investigación de Galicia ''CITIC'', funded by Xunta de Galicia and the European Union (ERDF - Galicia 2014-2020 Program), by grant ED431G 2019/01.
                                                                                                                                   