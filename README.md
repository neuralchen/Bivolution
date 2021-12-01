# Bi-volution: A Static and Dynamic Coupled Filter
Accepted by AAAI2022

## Abstract

Dynamic convolution has achieved significant gain in performance and computational complexity, thanks to its powerful representation capability given limited filter number/layers.
However, SOTA dynamic convolution operators are sensitive to input noises (e.g., Gaussian noise, shot noise, e.t.c.) and lack sufficient spatial contextual information in filter generation.
To alleviate this inherent weakness, we propose a lightweight and heterogeneous-structure (i.e., static and dynamic) operator, named ***Bi-volution***.
On the one hand, Bi-volution is designed as a dual-branch structure to fully leverage complementary properties of static/dynamic convolution, which endows Bi-volution more robust properties and higher performance.
On the other hand, the Spatial Augmented Kernel Generation module is proposed to improve the dynamic convolution, realizing the learning of spatial context information with negligible additional computational complexity.
Extensive experiments illustrate that the ResNet-50 equipped with Bi-volution achieves a highly competitive boost in performance (***+2.8%***  top-1 accuracy on ImageNet classification, ***+2.4%*** box AP and ***+2.2%*** mask AP on COCO detection and instance segmentation) while maintaining extremely low FLOPs (i.e., ***ResNet50@2.7 GFLOPs***). Furthermore, our Bi-volution shows better robustness than dynamic convolution against various noise and input corruptions.

