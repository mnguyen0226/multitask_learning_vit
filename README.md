# Multi-task Learning with Vision Transformers
Image classification is a fundamental task in computer vision, with many practical applications. However, achieving high accuracy on complex datasets like Cifar-10 and Cifar-100 can be challenging, particularly when working with limited computational resources. In this study, we evaluate the performance of Multi-Task Learning (MTL) on two common image classification tasks: class and super-class classification. Specifically, we investigate the efficiency of MTL using the Vision Transformers (ViT) architecture on these datasets, shedding light on its comparative performance against the Single-Task Learning (STL) approach and traditional convolution-based models. Our results demonstrate that MTL using the ViT architecture outperforms the STL approach on both classification tasks, achieving higher accuracy with fewer parameters. Additionally, we find that ViT and ResNet-152 perform similarly on these tasks, highlighting the potential of ViT for MTL scenarios. These findings have important implications for the development of efficient and effective image classification models, particularly in scenarios where multiple classification tasks need to be performed simultaneously.

![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/vit.png)

## Results

### ViT: Single-Task Learning on CIFAR 10 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_vit_1.PNG)

### ViT: Single-Task Learning on CIFAR 10 with 20 epochs (superclass)
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_vit_2.PNG)

### ViT: Single-Task Learning on CIFAR 100 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_vit_3.PNG)

### ViT: Single-Task Learning on CIFAR 100 with 20 epochs (superclass)
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_vit_4.PNG)

### ViT: Multi-Task Learning on CIFAR 10 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/mtl_vit_1.PNG)

### ViT: Multi-Task Learning on CIFAR 100 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/mtl_vit_2.PNG)

### ResNet-152: Single-Task Learning on CIFAR 10 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_resnet_1.PNG)

### ResNet-152: Single-Task Learning on CIFAR 10 with 20 epochs (superclass)
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_resnet_2.PNG)

### ResNet-152: Single-Task Learning on CIFAR 100 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_resnet_3.PNG)

### ResNet-152: Single-Task Learning on CIFAR 100 with 20 epochs (superclass)
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/stl_resnet_4.PNG)

### ResNet-152: Multi-Task Learning on CIFAR 10 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/mtl_resnet_1.PNG)

### ResNet-152: Multi-Task Learning on CIFAR 100 with 20 epochs
![](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/mtl_resnet_2.PNG)

## Report
[Experimental Result Summary](https://github.com/mnguyen0226/multitask_learning_vit/blob/main/docs/results_tables_report.pdf).

[Report]().
