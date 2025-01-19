# TIME (Text-to-Image Models for Counterfactual Explanations)

Finding counterfactual explanations for image classification is a challenging task. The feature space of images is very sparse and multi-dimensional. Thus, to suffice the plausibility property of CEs, the method should produce images that are visually similar to the original, yet the modification should be human-understandable - adding random noise won't explain the model decision.
This task poses several challenging characteristics for image classification. It was commonly done before with diffusion models that were hinted at using the classifier's gradients or by taking advantage of the model's inner structure.

In next week's presentation, I will talk about the first black-box method of generating Counterfactual Explanations for image classification. TIME (Text-to-Image Models for Counterfactual Explanations) is a novel method that generates CEs using diffusion models combining two different ideas - textual inversion, and EDICT- which create an ingenious method of explaining the image classifiers

Presentation is based on [this paper](https://arxiv.org/pdf/2309.07944.pdf)
