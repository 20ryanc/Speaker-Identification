# Speaker-Identification<a name="Speaker-Identification"></a>

## Overview<a name="Overview"></a>

Our objective for this project is to determine the speaker in an unconstrained environment with potential noise. We do so by examining the mel-spectrogram of an audio snippet and analyzing it through our various models. Our project seeks to build on baseline models to formulate more advanced models in helping us better determine the speaker. Our baseline models consist of Transformers and Confermers. We then build on our baseline model for our advanced models, which are Self-Attention Pooling and Additive Margin Softmax. Our best models were able to achieve 89 percent accuracy by only using audio files.

## Technical Details<a name="Technical Details"></a>

 - Training was done on Kaggle with GPU on a dataset from https://www.kaggle.com/datasets/sininghuang/cs4650dataset with only audio
 - Original dataset was obtained from https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html contains both audio and video
 - Conformer architecture was based off of this paper https://arxiv.org/abs/2005.08100 by google
