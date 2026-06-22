# Car-Parts-Discovery-With-NMF
Applied Non-Negative Matrix Factorization (NMF) on 3352 car images to explore unsupervised feature extraction and discover common visual patterns in automobile images.


#Project Goal
The goal of this project is to explore how Non-Negative Matrix Factorization (NMF) can discover common visual patterns from car images without using labels.

# Dataset

Cars Image Dataset from Kaggle containing 3352 car images from multiple car brands and viewpoints.

#Preprocessing
Convert RGB to Grayscale
Resize Images to 64x64
Flatten Images into 4096 Features
Normalize Pixel Values

# NMF successfully extracted common visual patterns from car images. Unlike the face dataset used earlier, the car dataset contained multiple viewpoints, backgrounds, and vehicle styles, making it more difficult for NMF to discover clearly separated parts such as wheels or doors. The extracted components appeared as common car-related structures and lighting patterns rather than distinct object parts.
