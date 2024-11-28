# Vision Transformers provably learn spatial structure

## Abstract

A key question in vision transformers (ViTs) is how they achieve performance comparable to CNNs without having built-in spatial inductive biases. The paper explains theoretically ViTs learn spatial structure through gradient descent optimization. The authors prove that ViTs implicitly learn to group related image patches (“patch association”) through a three-phase process while minimizing their training objective. This learned structure enables efficient transfer learning and explains ViTs’ practical success. Experiments on CIFAR-10/100, SVHN, and ImageNet demonstrate that ViTs can learn general spatial relationships even when image patches are randomly permuted, achieving competitive performance with a simplified positional attention mechanism (68.9% vs 71.9% accuracy on ImageNet).

## Source paper

[Vision Transformers provably learn spatial structure](https://arxiv.org/abs/2210.09221)
