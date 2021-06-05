### Double U-Net

This network predicts the masks using two different U Net structure. The first U-Net structure use VGG-encoder block, and the input to the second U-Net is element wise product of the input image and the output mask of the first network.

#### Architecture

![Arch](https://raw.githubusercontent.com/DebeshJha/2020-CBMS-DoubleU-Net/master/img/DoubleU-Net.png)

References:

1. https://arxiv.org/pdf/2006.04868.pdf
2. https://github.com/DebeshJha/2020-CBMS-DoubleU-Net
