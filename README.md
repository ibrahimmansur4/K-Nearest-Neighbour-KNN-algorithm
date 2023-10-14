# K-Nearest Neighbors (KNN) Image Classification

This project focuses on the implementation of the K-Nearest Neighbors (KNN) algorithm for image classification. The main objective is to identify actors or actresses that closely resemble a provided test image. The dataset used in this project consists of 50 32x32 color images of actors, with 5 images per actor.

## Project Structure

- **KNN.ipynb**: Jupyter Notebook script that steps through the KNN algorithm implementation.
- **data.mat**: The dataset containing 50 32x32 color images of actors.
- **test.jpg**: The test image used to find the closest matching images in the dataset.

## Implementation Overview

The project involves the following key steps:

1. Loading the dataset of images and corresponding labels.
2. Preprocessing the test image to match the dimensions and format of the dataset images.
3. Calculating the Euclidean distance between the test image and each image in the dataset.
4. Implementing the KNN approach to identify the closest images based on the computed distances.

## Results and Analysis

Upon running the KNN algorithm, the results revealed images closely resembling the test image, with a bias towards actors with similar skin tones and attire. The limitations encountered include the need for manual adjustments and potential issues with larger datasets. To enhance the algorithm's performance, suggestions include optimizing the code for efficiency, exploring alternative distance metrics, and refining preprocessing steps for improved feature extraction.

## Instructions for Usage

1. Clone the repository to your local machine.
2. Set up the necessary environment with Python and required libraries.
3. Open and run the `KNN.ipynb` notebook using Jupyter or any compatible platform.
4. Follow the step-by-step guide to understand the implementation and results.

## Further Improvements

The project's potential future improvements include the exploration of advanced distance metrics, incorporation of deep learning techniques for feature extraction, and the development of a more interactive user interface for practical applications.

Feel free to explore the code and share any feedback or suggestions for enhancements.

