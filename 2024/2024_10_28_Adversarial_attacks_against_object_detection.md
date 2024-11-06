# Adversarial examples vs. context consistency defense for object detection

Slides: https://hbaniecki.com/mi2seminar2024

## Abstract

One defense strategy for detecting adversarial examples is to check for intrinsic context consistencies in the input data, where context refers to various relationships (e.g., object-to-object co-occurrence relationships) in images. I will present a paper showing that these context consistency checks don't work for properly crafted adversarial examples. ADC defines a joint optimization problem with two attack goals: (1) fooling the object detector and (2) evading the context consistency check system, at the same time. Experiments on PASCAL VOC and MS COCO datasets show that examples generated with ADC fool the object detector with a success rate of over 85%, and at the same time evade the recently proposed context consistency checks, with a “bypassing” rate of over 80%.

## Source papers

[Connecting the Dots: Detecting Adversarial Perturbations Using Context Inconsistency](https://arxiv.org/abs/2007.09763)

[ADC: Adversarial attacks against object Detection that evade Context consistency checks](https://arxiv.org/abs/2110.12321)