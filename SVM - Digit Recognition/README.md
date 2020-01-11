# Digit Recognition with Support Vector Machines

This Code will help you recognize handwritten digts with help of Suppor Vector Machine


# Objective
A classic problem in the field of pattern recognition is that of handwritten digit recognition. 
Suppose that you have images of handwritten digits ranging from 0-9 written by various people in boxes of a specific size - similar to the application forms in banks and universities.

The goal is to develop a model that can correctly identify the digit (between 0-9) written in an image. 

You are required to develop a model using Support Vector Machine which should correctly classify the handwritten digits from 0-9 based on the pixel values given as features. Thus, this is a 10-class classification problem

## Data Description
For this problem, we use the MNIST data which is a large database of handwritten digits. The 'pixel values' of each digit (image) comprise the features, and the actual number between 0-9 is the label. 

 

Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features. MNIST digit recognition is a well-studied problem in the ML community, and people have trained numerous models


# Libraries Used
 - sklearn
 - matplotlib
 - numpy
 - pandas
 - matplotlib
 - seaborn

# Steps

# Final Model
The non-linear RBF model with C=10 and gamma = 0.001 is best for our data

# Train Acuracy ~ 95%
## Test Acuracy ~ 92 to 94%