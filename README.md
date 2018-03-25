# **Project: Semantic Segmentation**
[![Udacity - Self-Driving Car Engineer NanoDegree Program](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## Overview
This repository contains all the codes and final result inference images that required for completing project. The goal of this project is to label the pixels of a road in images using a Fully Convolutional Network (FCN).

Build instruction and dependency of this project is identical to [upstream repository](https://github.com/udacity/CarND-Semantic-Segmentation) which is the starter code repository of udacity.

## Result

[//]: # (Image References)

[result]: ./runs/1521970050.2572997/umm_000033.png "an example of inference image"
[loss]: ./runs/loss_e100_1521970050.2572997.png  "loss plot"

This is one of example from the most recent run.

![alt text][result]

### Hyper-parameters
- epochs = 100
- lr = 0.0001
- dropout_keep_prob = 0.5
- batch_size = 16
- l2 regularization scale = 1e-3

### Loss after 100 epochs
- Loss = 0.24974

![alt text][loss]