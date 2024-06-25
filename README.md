# Multi-Objective-Optimal-Threshold-Selection-for-Similarity-Functions-in-Siamese-Networks
Code accompaniment for the research work submitted by Sparcus Technologies Limited on Multi-Objective Optimal Threshold Selection for Similarity Functions in Siamese Networks for Semantic Textual Similarity Tasks.<br>
Preprint can be found here: Not available yet <br>

# Abstract <br>
This paper presents a comparative study of fundamental similarity functions for Siamese networks in semantic textual similarity (STS) tasks. We evaluate various similarity functions using the STS Benchmark dataset, analyzing their performance and stability. Additionally, we introduce a novel multi-objective approach for optimal threshold selection. Our findings provide insights into the effectiveness of different similarity functions and offer a straightforward method for threshold selection optimization, contributing to the advancement of Siamese network architectures in STS applications.

# Data <br>
STS Benchmark Dataset, HuggingFace profile: https://huggingface.co/datasets/mteb/stsbenchmark-sts <br>
Benchmarks and Papers: https://paperswithcode.com/dataset/sts-benchmark <br>

 # Repository Structure <br>
_trainer1.py: Contains the code for model 1 training. <br>
_trainer2.py: Contains the code for model 2 training. <br>
_trainer3.py: Contains the code for model 3 training. <br>
_predictor1.py: Contains the code for model 1 prediction with multicrop. <br>
_predictor2.py: Contains the code for model 2 prediction with multicrop. <br>
_predictor3.py: Contains the code for model 3 prediction with multicrop. <br>
_predictor_finalizer.py: Contains the code for performing prediction ensembling at test time. <br>
README.md: This file, containing an overview of the repository. <br>
LICENSE: Apache 2.0 License. <br>
