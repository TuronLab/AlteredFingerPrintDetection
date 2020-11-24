# Description

Fingerprint alteration is a common practice of people who don't want to be identified. There are lots of different techniques to hide your identity behind the fingerprint, and this data uses to be private, and it's only accesible by police. That's the reason why Papi, S. et. al., in [*"On the Generation of Synthetic Fingerprint Alterations"*, (2016)](https://ieeexplore.ieee.org/document/7736930), propose some techniques to generate synthetic altered fingerprints. In this paper, authors focused in most common alterations encountered in real situations: burning obliteration, central rotation and Z-Cut.

![ExampleFingerprintAlteration](https://github.com/TuronLab/AlteredFingerPrintDetection/blob/main/FingerAlterationsExample.PNG)

For the development of Machine Learning algorithms, [Yahaya, I. S. et. al.](https://arxiv.org/abs/1807.10609) provided a big dataset of fingerprints with 6000 fingerprints from 600 African subjects. This dataset is available for download for free in [Kaggle](https://www.kaggle.com/ruizgara/socofing), where you can find unaltered fingerprints, and altered fingerprints in different levels.

So, in this repository, I propose some approaches to detect whether a fingerprint has been altered or not using CNN techniques, classifying the four categories, Real, Obliteration, Central Rotation, or Z-Cut. In this way, we have achieved an algorithm with 90% of accuracy in validation set.
