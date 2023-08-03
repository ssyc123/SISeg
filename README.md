
# Training-Free Instance Segmentation from Semantic Image Segmentation Masks

This repository contains the official PyTorch implementation of the following paper:

**Training-Free Instance Segmentation from Semantic Image Segmentation Masks**

Yuchen Shen, Dong Zhang, Yuhui Zheng, Zechao, Li, _Senior Member, IEEE_, Liyong Fu, Qiaolin Ye, _Member, IEEE_

https://arxiv.org/abs/2308.00949

## Abstract
<p align="justify">
In recent years, the development of instance segmentation has garnered significant attention in a wide range of applications. However, the training of a fully-supervised instance segmentation model requires costly both instance-level and pixel-level annotations. In contrast, weakly-supervised instance segmentation methods (i.e., with image-level class labels or point labels) struggle to satisfy the accuracy and recall requirements of practical scenarios. In this paper, we propose a novel paradigm for instance segmentation called training-free instance segmentation (TFISeg), which achieves instance segmentation results from image masks predicted using off-the-shelf semantic segmentation models. TFISeg does not require training a semantic or/and instance segmentation model and avoids the need for instance-level image annotations. Therefore, it is highly efficient. Specifically, we first obtain a semantic segmentation mask of the input image via a trained semantic segmentation model. Then, we calculate a displacement field vector for each pixel based on the segmentation mask, which can indicate representations belonging to the same class but different instances, i.e., obtaining the instance-level object information. Finally, instance segmentation results are obtained after being refined by a learnable category-agnostic object boundary branch. Extensive experimental results on two challenging datasets and representative semantic segmentation baselines (including CNNs and Transformers) demonstrate that TFISeg can achieve competitive results compared to the state-of-the-art fully-supervised instance segmentation methods without the need for additional human resources or increased computational costs.

## The code will be published when the paper is accepted.

## Citing
If you use our work, please consider citing:
```
@article{shen2023trainingfree,
  title={Training-Free Instance Segmentation from Semantic Image Segmentation Masks},
  author={Yuchen Shen and Dong Zhang and Yuhui Zheng and Zechao Li and Liyong Fu and Qiaolin Ye},
  journal={arXiv preprint arXiv:2308.00949},
  year={2023}
}







