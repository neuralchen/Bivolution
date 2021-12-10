# Bi-volution: A Static and Dynamic Coupled Filter
### Accepted by AAAI2022

**The official repository with Pytorch**

We are working on the final version paper, and the code will be avaliable soon!

## Abstract

Dynamic convolution has achieved significant gain in performance and computational complexity, thanks to its powerful representation capability given limited filter number/layers.
However, SOTA dynamic convolution operators are sensitive to input noises (e.g., Gaussian noise, shot noise, e.t.c.) and lack sufficient spatial contextual information in filter generation.
To alleviate this inherent weakness, we propose a lightweight and heterogeneous-structure (i.e., static and dynamic) operator, named ***Bi-volution***.
On the one hand, Bi-volution is designed as a dual-branch structure to fully leverage complementary properties of static/dynamic convolution, which endows Bi-volution more robust properties and higher performance.
On the other hand, the Spatial Augmented Kernel Generation module is proposed to improve the dynamic convolution, realizing the learning of spatial context information with negligible additional computational complexity.
Extensive experiments illustrate that the ResNet-50 equipped with Bi-volution achieves a highly competitive boost in performance (***+2.8%***  top-1 accuracy on ImageNet classification, ***+2.4%*** box AP and ***+2.2%*** mask AP on COCO detection and instance segmentation) while maintaining extremely low FLOPs (i.e., ***ResNet50@2.7 GFLOPs***). Furthermore, our Bi-volution shows better robustness than dynamic convolution against various noise and input corruptions.



## Related Projects

***Please visit our popular face swapping project***

[![logo](./docs/img/simswap.png)](https://github.com/neuralchen/SimSwap)

***Please visit our high resolution face dataset VGGFace2-HQ***

[![logo](./docs/img/VGGFace2-HQ.png)](https://github.com/NNNNAI/VGGFace2-HQ)

***Please visit our another ACMMM2020 high-quality style transfer project***

[![logo](./docs/img/logo.png)](https://github.com/neuralchen/ASMAGAN)

[![title](/docs/img/title.png)](https://github.com/neuralchen/ASMAGAN)

***Please visit our AAAI2021 sketch based rendering project***

[![logo](./docs/img/girl2.gif)](https://github.com/TZYSJTU/Sketch-Generation-with-Drawing-Process-Guided-by-Vector-Flow-and-Grayscale)
[![title](/docs/img/girl2-RGB.png)](https://github.com/TZYSJTU/Sketch-Generation-with-Drawing-Process-Guided-by-Vector-Flow-and-Grayscale)





Learn about our other projects 

[[VGGFace2-HQ]](https://github.com/NNNNAI/VGGFace2-HQ);

[[RainNet]](https://neuralchen.github.io/RainNet);

[[Sketch Generation]](https://github.com/TZYSJTU/Sketch-Generation-with-Drawing-Process-Guided-by-Vector-Flow-and-Grayscale);

[[CooGAN]](https://github.com/neuralchen/CooGAN);

[[Knowledge Style Transfer]](https://github.com/AceSix/Knowledge_Transfer);

[[SimSwap]](https://github.com/neuralchen/SimSwap);

[[ASMA-GAN]](https://github.com/neuralchen/ASMAGAN);

[[SNGAN-Projection-pytorch]](https://github.com/neuralchen/SNGAN_Projection)

[[Pretrained_VGG19]](https://github.com/neuralchen/Pretrained_VGG19).

## Acknowledgements
