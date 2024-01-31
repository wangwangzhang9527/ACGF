# Deep Single Image Deraining using An Asymmetric Cycle Generative and Adversarial Framework
Wei Liu*, Caiwang Zhang,  Cheng Chen, Xiaoyu Huang, Minghui Li

> **Abstract:** In reality, rain and fog are often present at the same time, which can greatly reduce the clarity and quality of the scene image.
However, most unsupervised single image deraining methods primarily concentrate on removing rain streaks while disregarding the presence of fog, which often leads to low-quality deraining performance. 
In addition, these methods generate samples that are too similar and lack diversity, resulting in poor performance when dealing with complex rain scenes. 
To address the above issues, we propose a novel Asymmetric Cycle Generative and Adversarial Framework (ACGF) for single image deraining that trains on both synthetic and real rainy images while simultaneously capturing both rain streaks and fog features, which consists of a Rain-fog2Clean (R2C) transformation block and a Clean2Rain-fog (C2R) transformation block. 
To better characterize the rain-fog fusion feature of R2C, we propose an attention rain-fog feature extraction network (ARFE) to exploit the self-similarity of global and local rain-fog information by learning the spatial feature correlations.  
Furthermore, to improve the translational capacity of C2R and the diversity of models in synthetic rain conversion path, we design a rain-fog feature decoupling and reorganization network (RFDR) by embedding a rainy image degradation model and a mixed discriminator to preserve richer texture details.
Extensive experiments on benchmark rain-fog, rain and fog datasets show that ACGF outperforms state-of-the-art deraining methods. 
![image](https://github.com/wangwangzhang9527/ACGF/blob/main/figures/architecture.png)

## Our Rain-fog dataset
You can download our Rain-fog dataset from [here](https://pan.baidu.com/s/18z2LJbpnq4Ab89JytFli3g) (password:s265).
You can view a portion of the images [here](https://github.com/wangwangzhang9527/ACGF/blob/main/figures/dataset).

## Training and Evaluation

The complete code will be provided after the article is accepted.

## Acknowledgement
This code is inspired by [DerainCycleGAN](https://github.com/OaDsis/DerainCycleGAN).

## Citations
If our code helps your research or work, please consider citing our paper.
```
@inproceedings{Liu2023DeepSI,
  title={Deep Single Image Deraining using An Asymetric Cycle Generative and Adversarial Framework},
  author={Wei, Liu and Caiwang, Zhang and Cheng, Chen and Xiaoyu, Huang and Minghui, Li},
  year={2023},
  url={https://api.semanticscholar.org/CorpusID:258823257}
}
```

