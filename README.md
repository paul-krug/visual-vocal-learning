# Artificial Vocal Learning Guided by Phoneme Recognition and Visual Information

This repository contains the supplementary materials to the paper:

["Artificial Vocal Learning Guided by Phoneme Recognition and Visual Information"](https://doi.org/10.36227/techrxiv.20502114.v1) by ``Krug et al.``

# Content

This repository contains audio samples and visualizations, for the actual Python implementation of the artificial vocal learning framework, see [https://github.com/paul-krug/artificial-vocal-learning](https://github.com/paul-krug/artificial-vocal-learning)

This repository contains the following files and folders:
- ``Articulatory_Distributions`` Contains plots of distributions of articulatory parameter corresponding to states related to specific phoneme categories.
- ```Stimuli``` Contains the audio samples used in the perceptual experiment as described in the paper.

  ```└─── Manual``` Contains manually selected speech samples (highest quality achievable with the vocal learning framework).
  
  ```└─── Q_0.0``` Contains automatically selected samples (samples corresponding to the lowest total loss).
  
  ```└─── Q_0.25``` Contains automatically selected samples (samples corresponding to the total loss 25% quantile).
  
  ```└─── Q_0.5``` Contains automatically selected samples (samples corresponding to the median total loss).
  
  ```└─── Q_0.75``` Contains automatically selected samples (samples corresponding to the total loss 75% quantile).
  
  ```└─── Q_1.0``` Contains automatically selected samples (samples corresponding to the highest total loss).
  
  ```└─── VTL``` Contains VocalTractLab baseline samples (samples generated with MRI based predefined shapes).
