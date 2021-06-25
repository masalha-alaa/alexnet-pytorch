# AlexNet

This is my own implementation of AlexNet, the winner of ImageNet 2012 (LSVRC-2012), which is described in the paper [ImageNet Classification with Deep Convolutional Neural Networks](https://www.cs.toronto.edu/~hinton/absps/imagenet.pdf).

I tried to be as precise as possible in the implementation, but I did end up leaving out 1 or 2 elements, such as the PCA data augmentation, which I talked more in detail about inside the notebook. However, this implementation is even more precise and thorough than [PyTorch's own implementation](https://pytorch.org/vision/stable/_modules/torchvision/models/alexnet.html#alexnet).

Please find the notebook [AlexNet_pytorch.ipynb](https://github.com/masalha-alaa/alexnet-pytorch/blob/master/AlexNet_pytorch.ipynb) under the root directory of this repo for a complete walkthrough of the code and architecture.

![AlexNet architecture, figure from https://www.cs.toronto.edu/~hinton/absps/imagenet.pdf](https://user-images.githubusercontent.com/78589884/123445027-2bd98b80-d5e0-11eb-8016-1e2da3f517f5.png)
*(figure from the cited paper)*
