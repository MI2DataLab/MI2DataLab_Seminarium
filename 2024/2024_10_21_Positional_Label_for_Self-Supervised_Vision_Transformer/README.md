# Positional Label for Self-Supervised Vision Transformer

## Abstract

Self-attention, a central element of ViT architecture, is permutation-invariant. Hence, it does not capture the spatial arrangement of input by design. Thus, valuable information is lost, especially crucial in the case of computer vision tasks. To deal with that, a common approach is to add the positional information to the input embeddings (element-wise) or modify attention layers to account for that (attention score extended by the relative distance between the query and key). The authors of Positional Label for Self-Supervised Vision Transformer propose an alternative approach that does not explicitly add any positional information. Instead, the training process is extended by auxiliary task - image patches position classification. As a result, the positional information is somewhat implicitly added to the patches themselves. Both relative and absolute variants are proposed. They are plug-and-play with vanilla ViTs. The authors ensure that this solution increases the ViT performance. Moreover, this method can be used in self-supervised training, which enhances the training process.

## Source paper

[Positional Label for Self-Supervised Vision Transformer](https://dl.acm.org/doi/10.1609/aaai.v37i3.25461)