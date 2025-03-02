# Relevance-aware Prompt-tuning Method for Multimodal Social Entity and Relation Extraction

**The code of this repository is constantly being updated...**


Our code consists of three crucial modules: 
  1. We propose a dynamic routing mechanism that allows each sample to adaptively select an appropriate feature extraction strategy, which makes the model more eﬀicient and mitigates the impact of modality noise;
  2. To evaluate the semantic consistency and alignment between the text and images in social media posts, we modeled the relevance representations between modalities and employ graph reasoning algorithm to calculate their alignment. Based on the calculated modality correlation, our model will weight the visual information to prevent irrelevant visual information from being considered.;
  3. We propose to apply prompt-tuning methods to MNER and MRE tasks, and calculate prompt vectors based on joint modality features to further mitigate the impact of modality noise on model decisions.


Please look forward to it!

## Introduction

This repository is used in our paper:

《Relevance-aware Prompt-tuning Method for Multimodal Social Entity and Relation Extraction》

Zhenbin Chen, Zhixin Li, Mingqi Liu, Canlong Zhang, Huifang Ma. 


Please cite our paper and kindly give a star for this repository if you use this code.


## Usage

### Twitter2015
```
sh run_twitter15.sh
```

### Twitter2017
```
sh run_twitter17.sh
```

### MNRE
```
sh run_re_task.sh
```


## Citation
```
coming soon...
```
