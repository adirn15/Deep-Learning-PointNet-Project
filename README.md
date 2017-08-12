# Deep-Learning-PointNet-Project

Classification and Segmentation of the MNIST dataset given as a point set input.

Classification:
the program classifies hand written digits, given as a sample of 100 points in a 2 dimensional field. 
the architecture is based on a Stanford article of a PointNet which is especially efficient for 3D image classification.
the PointNet classification accuracy is 92.86%

Segmentation:
this is an extension to the classification net which can later define segments within the pointset.
the program receives an input of a handwritten digit, given as a sample of 200 points in a 2 dimensional field, where 100 of the points
are a sample of the digit itself, and the rest of the points are "background" points which are not part of the digit.
the program classifies each point into one of the 2 segments and returns if it is part of the digit or part of the background.
the PointNet segmentation accuracy is 97.65%



