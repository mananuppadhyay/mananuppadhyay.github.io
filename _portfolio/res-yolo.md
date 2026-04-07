---
title: "Object detection using Res-YoLo"
excerpt: "Applied the model architecture taken from the paper, onto an open source car detection Dataset."
collection: portfolio
---

Applied the model architecture taken from the [paper](https://www.sciencedirect.com/science/article/pii/S0031320318302000), onto an open source car detection Dataset.

* Uses a ResNet backbone as a feature Extracter, and uses a YoLo like architecture to detect cars.
* Fine-Tuned the architecture on a car detection dataset, by freezing the intial few ResNet layers and training the custom detector in a regression like fashion.
* Tech stack: Pytorch, numpy, matplotlib

[GitHub code](https://github.com/mananuppadhyay/ResYOLO)
