
## Automatic Data Augmentation by Learning the Deterministic Policy
---

### Introduction
This is the official implementation of 

[Automatic Data Augmentation by Learning the Deterministic Policy](https://arxiv.org/abs/1910.08343)

Yinghuan Shi, Tiexin Qin, Yong Liu, Jiwen Lu,  Gao Yang and Dinggang Shen.

The code shall be released once our paper has been accepted. You can download the *demo.mp4* file in this project to see the learned policy by our method in CUB-20.

<center>
<img src="./figs/fig_framework-eps-converted-to.png" width="100%" height="50%" />
</center>


### Abstract
Aiming to produce sufficient and diverse training samples, data augmentation has been demonstrated for its effectiveness in training deep models. Regarding that the criterion of the best augmentation is challenging to define, we in this paper present a novel learning-based augmentation method termed as DeepAugNet, which formulates the final augmented data as a collection of several sequentially augmented subsets. Specifically, the current augmented subset is required to maximize the performance improvement compared with the last augmented subset by learning the deterministic augmentation policy using deep reinforcement learning. By introducing an unified optimization goal, DeepAugNet intends to combine the data augmentation and the deep model training in an end-to-end training manner which is realized by simultaneously training a hybrid architecture of dueling deep Q-learning algorithm and a surrogate deep model. We extensively evaluated our proposed DeepAugNet on various benchmark datasets including Fashion MNIST, CUB, CIFAR-100 and WebCaricature. Compared with the current state-of-the-arts, our method can achieve a significant improvement in small-scale datasets, and a comparable performance in large-scale datasets. Code will be available soon.


### Demo
<video src="./figs/demo.mp4" width="520" height="400"
controls="controls"></video> 


### Citation    
    @inproceedings{Shi2019DeepAugNet,
    title={Automatic Data Augmentation by Learning the Deterministic Policy},
    author={Yinghuan Shi, Tiexin Qin, Yong Liu, Jiwen Lu,  Gao Yang and Dinggang Shen},
    booktitle={arxiv},
    year={2019}

