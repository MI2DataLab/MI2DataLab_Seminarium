# Sparse Autoencoders Do Not Find Canonical Units of Analysis

This paper examines the limitations of Sparse Autoencoders (SAEs) as a method for finding interpretable features in neural networks, particularly challenging the idea that they can identify a “canonical set of units” (unique and complete atomic features). To showcase this problem, the authors propose Meta-SAEs - essentially applying SAEs to the decoder matrix of another SAE - demonstrating that supposedly atomic features can still be further decomposed. Additionally, the authors introduce feature stitching, a method where features from wider SAEs are inserted into narrower ones, revealing that narrower SAEs are incomplete in their feature representation.

The presentation is based on this [paper](https://openreview.net/forum?id=9ca9eHNrdH)
