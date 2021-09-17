# Classification of fashion mnist data :- 

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples.
Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in 
replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

# My Experiment :- 
Used 5000 images for the training set and 1500 images for the validation set and 10000 images for the test set.
500 images per class.
# Result : 
Trained the model from scratch and result are following:- 
1 - Achieved an accuracy of 88% in the test set with 4 CNN layer model and 1 dense layer only.
2-  Achieved an accuracy of 76% in the test set with 5 Dense layer only.

# Observation - key points for reducing overfitting.
Batchnorm layer, 
Droupout layer, 
Image generator of diff shape, rotation and shear, 
Simple model with fewer parameter
Random split of train and validation set

