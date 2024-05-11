# comparison-of-DCGAN-CGAN-On-Fashion-MNIST-Dataset

This repository contains code for comparison of DCGAN and CGAN On Fashion MNIST Dataset. Key components are:

- Fashion MNIST
- Preprocessing: Normalization, Resizing
- Traing of the discriminator and the generator of both models were trained for 100 epochs with a batch size of 128. Adam optimizer was used with a learning rate of 0.0002 and a beta value of 0.5. 
- Comparison in discriinator loss, generator loss and gan loss between both the Models

## Requirements

- Numpy
- keras
- Matplotlib

## Installation

1. **Keras:**
   - Install keras using pip:
     ```
     pip install keras
   
2. **Matplotlib:**
   - Install matplotlib using pip:
     ```
     pip install matplotlib
     ```

3. **NumPy:**
   - Install NumPy using pip:
     ```
     pip install numpy
     ```
  **Flanker Task**
  - Toy dataset obtained from keras.datasets. The Fashion MNIST dataset consists of 70,000 grayscale (single channel) images comprising of 60,000 training images and 10,000 testing images, each of size 28x28 pixels. These images are divided into 10 classes including T-shirts/tops, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.

## Usage
 
1. Navigate to the your_directory folder:
```
cd your_directory
```
2. Either train from scrach or use the .keras model to use our pretrained model.

## Team Members
1. Sohaib Nasir
2. Nauman Asif


