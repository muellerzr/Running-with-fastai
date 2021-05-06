# Running with fastai - Syllabus

10-12 Weeks, each week we implement and look at deeper aspects of the fastai library

Start date: TBD

Notebooks will be live both here and on [Walk with fastai](https://walkwithfastai.com)

## Debugging and Advanced Library Introduction
Week 1: Debugging fastai and understanding the source code, how to navigate bugs, and writing your first PR

Week 2: Raw torch and fastai, walking through the migration guide, and bringing torch code into fastai (direct 1:1 conversion)

Week 3: All about inference. fastai to torchscript, ONNX, etc. Converting what you were running in fastai to raw pytorch, raw PIL, and raw CV2, and understanding what needs to be changed and why things are incompatible

Week 4: Callback System and Loss Functions

Week 5: Optimizers and customizing the fastai training loop through Callbacks and Schedulers

## Implementations
Week 6: The MixedDL - two end-to-end scenarios

Week 7: Keypoint Heatmaps from "scratch" - paper/source code to implementation, go over the entire conversion process

Week 8: Intro to NLP and using Hooks to gather embeddings, showcase AdaptNLP and how we integrated in HuggingFace via fastai_minima

Week 9: Instance segmentation library, going through the implementation and the modifications to the fastai library needed

## Other Libraries and Guest Speakers
Week 10: The timm library, how I integrated it into fastai, and a special guest: Aman Arora

Week 11: UPIT with a special guest: Tanishq Abraham

Week 12: SimCLR and Self-Supervised Learning with special guest: Kerem Turgutlu
