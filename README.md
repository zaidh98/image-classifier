
# Image Classifier

This repository contains a simple image classification project designed to distinguish between artworks by Pablo Picasso and Claude Monet. Using deep learning techniques and the fastai library, this project demonstrates how to build and train an image classifier from scratch.

## Project Overview

The goal of this project is to create a classifier that can identify whether a given image is a painting by Pablo Picasso or Claude Monet. The classifier is built using the fastai library, which provides a high-level interface for training deep learning models.

## Contents

- `Image Classifier.ipynb`: The Jupyter Notebook containing the code for the image classification project.
- `Monet.jpg`: Sample image of Claude Monet's artwork.
- `Picasso.jpg`: Sample image of Pablo Picasso's artwork.
- `picasso_or_monet/`: Directory containing additional images for classification.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/zaidh98/image-classifier.git
   ```

2. Navigate to the project directory:
   ```sh
   cd image-classifier
   ```

3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

2. Run the cells in `image_classifier.ipynb` to load the images, preprocess the data, train the model, and classify new images.
