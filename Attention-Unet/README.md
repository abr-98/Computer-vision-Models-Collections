### Attention U-net

U-net is used for segmentation and so several modifications have been done to the basic structure of the U-Net backbone. In the paper "Attention U-Net: Learning Where to Look for the Pancreas", the authors proposed a modification.

#### Architecture:

![Arch](https://miro.medium.com/max/1560/1*PdYEf-OuUWkRsm2Lfrmy6A.png)

The architecture represents a 3D U-Net, i.e, it uses, 3D convolutional layers, in both its expansion and contraction limbs. Expansion limbs uses upsampling and convolutional layers as used in state of the art models.

Additionally, the authors have intoduced the idea of "attention gates". 

References:

1. https://arxiv.org/pdf/1804.03999.pdf
2. https://towardsdatascience.com/using-attention-for-medical-image-segmentation-dd78825eaac6 (Model 1)
3. https://sh-tsang.medium.com/review-attention-u-net-learning-where-to-look-for-the-pancreas-biomedical-image-segmentation-e5f4699daf9f

