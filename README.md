# Semi-Supervised Deep Learning for Melanoma Detection
Live Project from Manning Publications. 
Task is to construct a model that would perform malignant vs. benign image classification on low resolution photos, typical of cellphone cameras. Data set contains 200 training images, 100 of which have been labeled as melanomas, and the other half as benign. In addition to a balanced test set composed of 600 images, there are also 7018 unlabeled images of moles, some of which may be malignant.

Using Pytorch, the machine learning task can be broken down into the following steps:
  - Setting up an image pre-processing pipeline that handles data augmentation and prepares data to be fed as input to a Pytorch model.
  - Training a fully supervised melanoma classifier on the labeled data and testing it to serve as a baseline.
  - Training a semi-supervised GAN model to make use of the unlabeled training data. Running the trained model on the test set and comparing its performance to the supervised baseline.
  
  Link to project website:
  https://liveproject.manning.com/module/146_1_3/semi-supervised-deep-learning-for-melanoma-detection/introduction/start-project?
