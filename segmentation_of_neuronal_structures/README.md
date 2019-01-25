# [Segmentation of neuronal structures in EM stacks](http://brainiac2.mit.edu/isbi_challenge/)

## Description
In this challenge, a full stack of EM slices will be used to train machine learning algorithms for the purpose of automatic segmentation of neural structures. The images are representative of actual images in the real-world, containing some noise and small image alignment errors. None of these problems led to any difficulties in the manual labeling of each element in the image stack by an expert human neuroanatomist. The aim of the challenge is to compare and rank the different competing methods based on their pixel and object classification accuracy.

## Folder descriptions
`input` - contains the images and mask of train & test set
`model` - contrains the jupyter notebook which trains the model and also contain directories which stores the model files and submission files
