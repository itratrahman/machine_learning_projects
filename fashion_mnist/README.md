# [FASHION MNIST](https://github.com/zalandoresearch/fashion-mnist)

## OVERVIEW
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Fashion-MNIST is intended to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

## WHY FASHION MNIST WAS CREATED?
The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

## PROBLEMS WITH MNIST
- MNIST is too easy. Convolutional nets can achieve 99.7% on MNIST. Classic machine learning algorithms can also achieve 97% easily. Check out our side-by-side benchmark for Fashion-MNIST vs. MNIST, and read "Most pairs of MNIST digits can be distinguished pretty well by just one pixel."
- MNIST is overused. In this April 2017 Twitter thread, Google Brain research scientist and deep learning expert Ian Goodfellow calls for people to move away from MNIST.
- MNIST can not represent modern CV tasks, as noted in this April 2017 Twitter thread, deep learning expert/Keras author François Chollet.

## DATASET
Original dataset can be downloaded from https://github.com/zalandoresearch/fashion-mnist

## FOLDER DESCRIPTION
- `input` - contains the train and test dataset in csv files.
- `models` - contains jupyter notebook that trains CNN model for classification 

## Reference
"Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms", Han Xiao et al. (2017)
