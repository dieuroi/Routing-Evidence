# Routing Evidence

## 
[![Paper](https://img.shields.io/badge/cs.CV-Paper-b31b1b?logo=arxiv&logoColor=red)](https://github.com/dieuroi/Routing-Evidence)

Routing Evidence for Unseen Actions in Video Moment Retrieval

the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**ACM SIGKDD**), 2024

### Abstract
> Video moment retrieval (VMR) is a cutting-edge vision-language task locating a segment in a video according to the query. Though the methods have achieved significant performance, they assume that training and testing samples share the same action types, hindering real-world application. In this paper, we specifically consider a new problem: video moment retrieval by queries with unseen actions. We propose a plug-and-play structure, Routing Evidence (RE), with multiple evidence-learning heads and dynamically route one to locate a sentence with an unseen action. Each evidence-learning head estimates the uncertainty while regressing timestamps. We formulate the evidence distribution by a Normal-Inverse Gamma function and design a router to select the most appropriate distribution for a sample. Empirically, we study the efficacy of RE on three updated databases where training and testing samples contain different action types. We find that RE outperforms other state-of-the-art methods with a more robust predictor.

### Dataset

We propose the annotations of our reconstructed datasets in [annos](./annos):
- [**TACoS**](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/tacos-multi-level-corpus)
- [**Charades-STA**](https://prior.allenai.org/projects/charades)
- [**ActivityNet Captions**](http://activity-net.org/download.html)

Please refer to [DATASET.md in CVMR](https://github.com/Xun-Yang/Causal_Video_Moment_Retrieval/blob/main/DATASET.md) to get the visual features and prepare datasets.


## :fire: Updates

- [08/2024] Data annotations is released.