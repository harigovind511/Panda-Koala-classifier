# Panda-Koala-CNN Image Classifier
## Overview

Keras based CNN Deep Learning implementation to classify Giant Pandas and Koalas.

## Requirements

  * Keras = 2.x (TensorFlow backend)
  * Numpy = 1.x

## Usage

Training and Testing data are in Data and then Train & Test folders with Koala & Panda as sub folders,
```
./data/
  train/
    Koala/
      Koala1.jpg
      Koala2.jpg
      ...
    Panda/
      Panda1.jpg
      Panda2.jpg
      ...
  Test/
    Koala/
      Koala1.jpg
      Koala2.jpg
      ...
    Panda/
      Panda1.jpg
      Panda2.jpg
      ...
      ...
```

# Training Model

```
run train_model.ipynb
```

This will generate model in **Models** folder.

# Testing Model

```
run test_model.ipynb
```
In this file, we can pass image path for test images.

# Improving Model

1. Adding more training data.
2. Tweaking Hyper Parameters.
