# Ayna-Unet-Model-coloured-polygon
**->** Importnat points to consider
1-the dataset used in this project is uploaded in the repo and in case you run this file kindly provide the zip file it will automatically unzip it
2-the API key is also written in comment in case u need it for the W&B
3-the model that is exported is uploaded in the drive and link is submitted in the form
solution of assesment
**->** Polygon Colorizer using UNet
This project presents a deep learning-based solution for automatically colorizing polygon shapes using a modified UNet architecture. Given an input polygon image (e.g., triangle, star, hexagon) and a target color name (e.g., red, blue, cyan), the model generates a colored version of the shape.

**->** Features
Accepts grayscale polygon images and color name as input

Uses a 6-channel UNet to generate colorized output images

Built with PyTorch and trained using MSE loss

Interactive inference using ipywidgets for shape and color selection

Tracked experiments using Weights & Biases

Model checkpoint (.pth) included for reuse

**->** Model Architecture
The model is based on the UNet architecture and modified to accept a 6-channel input:

3 channels for the polygon image (RGB)

3 channels for the target color, broadcasted spatially

The network outputs a 3-channel RGB image representing the colored polygon.

