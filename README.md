# Image Compression and Comparison: SVD dimension reduction VS linear regression.

## Overview
- This project focuses on image compression techniques, specifically comparing Singular Value Decomposition (SVD). The goal is to assess the effectiveness of reducing image size while preserving essential information.
- SVD dimension reduction VS linear regression for ML. The goal is to find the difference between linear interpolation methods.

## Features img compression
- **Image Compression**: Implement image compression using SVD .
- **Dimensionality Reduction**: Reduce image dimensions to achieve compression.
- **Visualization**: Visualize original and compressed images to assess the quality of compression.

## Features linear interpolation
- **SVD dim reduction VS linearRegression** For ML, The difference between linear interpolation methods.



## Requirements
- Python 3
- Libraries: numpy, matplotlib, scikit-learn, Pillow (PIL)

## Usage
1. Clone this repository.
2. Ensure you have the required dependencies installed.
3. Run the provided Python script to compress images and compare SVD with Linear Regression.
4. Analyze the visual outputs to evaluate the effectiveness of each technique.

## How It Works
- **Singular Value Decomposition (SVD)**: Decomposes the image matrix into three matrices: U, S, and V^T, where U and V^T represent the basis of the image space, and S contains singular values. By truncating these matrices, dimensionality reduction and compression are achieved.
- **Linear Regression**: Fits a linear model to the pixel intensities of the image. The model is then used to predict pixel intensities for compression.

Feel free to contribute or provide feedback to enhance this project.
