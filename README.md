# pta_forecasts
<!--[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jeffreyhazboun/pta_forecasts/master)-->
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1TvgfOk61pMaq0RHSKUEczftLJyf6TFuc?usp=sharing)

These notebooks reproduce the PTA forecasts from `Xin, Mingarelli and Hazboun, 2020. "Multimessenger pulsar timing array constraints on supermassive black hole binaries traced by periodic light curves"` 
https://arxiv.org/abs/2009.11865

They use the Python package [`Hasasia`](https://hasasia.readthedocs.io/en/latest/) developed to produce sensitivity curves and skymaps for pulsar timing arrays. The notebook that makes the various forecasted PTA products can be accessed in Google Colab, via the badge above. 

The simulated PTAs are made by pulling parameters from various empirical distributions based on current and forecasted PTA propertires, hence they are realization dependent. The exact versions used in the paper are included in the repo, except for the largest which can be downloaded via this [link](https://drive.google.com/file/d/1QBKYSyhh1dRWp9qm-K5Mk2JBX3PIP92z/view?usp=sharing).
