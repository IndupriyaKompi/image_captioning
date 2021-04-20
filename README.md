# Image Captioning

## Problem Statement
The objective is to develop an automatic image captioning model that generates the textual description for a given image.
The objective of this exercise is to build AI model that can automatically generate the textual sentences, describing the contents of a given image.

## Overview
Image Captioning is one of the complex models in Artificial Intelligence that requires the integration of recent advances in 
1.Computer Vision- to understand the contents of an image, and tranform into set of features 
and
2.Machine Translation- to turn these features into words in the right order
The propsed model is a typical encode-decoder model. You'll see CNN as an image “encoder”, by first pre-training it for an image classification task and using the last hidden layer as an input to the RNN decoder that generates sentences (see Fig. 1). We call this model the Neural Image Caption, or NIC.
Click [here](https://arxiv.org/pdf/1411.4555.pdf) to dive in.

