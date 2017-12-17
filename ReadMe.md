# Unsupervised Image Clustering using ConvNets and KMeans algorithms

This is my capstone project for [Udacity's Machine Learing Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009 "Udacity Machine Learning Engineer Nanodegree").

- For a full description of the project proposal, please see [proposal.pdf](proposal.pdf).

- For a full report and discussion of the project and its results, please see [Report.pdf](Report.pdf).

- Project code is in [capstone.ipynb](capstone.ipynb)

## Brief Description

I theorised that we can use KMeans clustering to seperate unlabelled images of different entitites after using ConvNets to transform them into a more meaningful representation. 

I use the convolutional layers of Keras's VGGNet model with ImageNet weights to transform cat and dog images. I then use Principal Component Analysis (PCA) for dimensionality reduction, before passing the new representation to a KMeans clustering algorithm for seperation (labelling).

This is implemented in [capstone.ipynb](capstone.ipynb) where you can find more details about what the code is achieving.

Results have been successful with up to 97.7% accuracy achieved.

## Libraries you will need
#### All code is in Python 3.6.

- cv2
- keras
- matplotlib
- numpy
- pandas
- sklearn
- tensorflow