# Semisupervised Clustering

This repository contains the code for semi-supervised clustering developed for Master Thesis: "Automatic analysis of images from camera-traps" by Michal Nazarczuk from Imperial College London

The algorithm is inspired with DCEC method ([Deep Clustering with Convolutional Autoencoders](https://xifengguo.github.io/papers/ICONIP17-DCEC.pdf)). The main change adds "labelling" loss (cross-entropy between labelled examples and their predictions) as the loss component.

## Prerequisites

The following libraries are required to be installed for the proper code evaluation:

1. PyTorch 
2. NumPy
3. scikit-learn
4. [TensorboardX](https://github.com/lanpa/tensorboardX)

The code was written and tested on Python 3.4.1

## Installation and usage

### Installation

Just copy the repository to your local folder:
```
git clone https://github.com/michaal94/Semisupervised-Clustering
```

### Use of the algortihm

In order to test the basic version of the semi-supervised clustering just run it with your python distribution you installed libraries for (Anaconda, Virtualenv, etc.). In general type:

```
cd Semisupervised-Clustering
python3 semi_supervised.py
```
The example will run sample clustering with MNIST-train dataset.
