## Bank Note Classification

**Objective** : Perform Active, Passive Learning and Monte Carlo Simulation on Bank Note Classification problem

- Active Learning : Incremental Learning by adding the most uncertain data points wrt to current model to the training pool.
- Passive Learning : Incremental Learning by randomly adding more data points to the training pool.
- Monte Carlo Simulation : A different model is trained hundreds of times by randomly picked data points and repeated over a number of iterations, then their average error is used represent the error. 

**Data** : Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

**Source** : [link](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)

**Results** : 99% Accuracy with SVC with L1 regularization

Language : python

IDE: ipython notebook

Author: Tanay Shankar

2018

