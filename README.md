# Image Captioning

## Problem Statement

The objective of this exercise is to develop a complex deep learning encoder-decoder model that automatically generates the human-readable textual descriptions for a given image. This involves the integration of computer-vision to understand the contents of the image and language model(NLP) to turn this understanding of images to texts. 

![Uploading image.png…]()


## Overview
Image Captioning is one of the complex models in Artificial Intelligence that requires the integration of recent advances in

a. Computer Vision: to understand the contents of an image, and tranform into set of features 
and

b. Machine Translation: to turn these features into words in the right order

The propsed model is a typical encode-decoder model. You'll see CNN as an image “encoder”, by first pre-training it for an image classification task and using the last hidden layer as an input to the RNN decoder that generates sentences (see Fig. 1). We call this model the Neural Image Caption, or NIC.

Click [here](https://arxiv.org/pdf/1411.4555.pdf) to dive in.

