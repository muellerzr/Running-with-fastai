# Running with fastai - Syllabus

10-12 Weeks, each week we implement and look at deeper aspects of the fastai library

Start date: TBD

Notebooks will be live both here and on [Walk with fastai](https://walkwithfastai.com)

## Debugging and advanced library introduction
1. Debugging fastai and understanding the source code, how to navigate bugs, and writing your first PR
2. Raw torch and fastai, walking through the migration guide, and bringing torch code into fastai (direct 1:1 conversion)
3. All about inference. fastai to torchscript, ONNX, etc. Converting what you were running in fastai to raw pytorch, raw PIL, and raw CV2, and understanding what needs to be changed and why things are incompatible
3. Callback System and Loss Functions
4. Optimizers and customizing the fastai training loop through Callbacks and Schedulers

## Implementations
6. The MixedDL - two end-to-end scenarios
7. Keypoint Heatmaps from "scratch" - paper/source code to implementation, go over the entire conversion process
8. Intro to NLP and using Hooks to gather embeddings, showcase AdaptNLP and how we integrated in HuggingFace via fastai_minima
9. Instance segmentation library, going through the implementation and the modifications to the fastai library needed

## Other Libraries and Guest Speakers
9. The timm library, how I integrated it into fastai, and a special guest
10. UPIT with a special guest
11. SimCLR and Self-Supervised Learning with special guest
