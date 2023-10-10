# Grad-CAM: Gradient-weighted Class Activation Mapping

![Grad-CAM](grad_cam.png)

## Introduction

Grad-CAM is a powerful technique used in the field of computer vision and deep learning for visualizing and understanding the regions in an image that are important for a deep neural network's prediction. It stands for "Gradient-weighted Class Activation Mapping" and provides insights into what regions of an image are most influential in the decision-making process of a convolutional neural network (CNN).

This repository provides an implementation and explanation of Grad-CAM, enabling you to apply this technique to your own deep learning projects.

## How It Works

Grad-CAM works by utilizing the gradients of the predicted class score with respect to the feature maps of the last convolutional layer. By backpropagating these gradients through the network, we can identify which parts of the input image were most influential in making the final prediction. This process generates a heatmap that highlights the important regions of the image.

## Key Features

- Easy-to-use Grad-CAM implementation for visualizing CNN predictions.
- Compatibility with popular deep learning frameworks such as TensorFlow and PyTorch.
- Customizable visualization options for overlaying heatmaps on input images.
- An informative example notebook to get you started.

## Example

Check out the example notebook [`GradCAM.ipynb`](grad_cam_example.ipynb) for a step-by-step guide on how to use Grad-CAM for visualizing CNN predictions.

## Acknowledgments

- This implementation is inspired by the original Grad-CAM paper: [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391).
