# Deep-learning-Image-Classification.
This is a simple CNN traing model for hand writing digits classification/ Assignment 2 and Project of HKU ELEC4542
## Assignment 2: SimpleCNN
This code implements a simple CNN for hand-written digit classification
### Image Classification
- Train an image classification model on CIFAR dataset with ResNet-18.
-  Use different data augmentation techniques and different ways to avoid overfitting.
- Use class activation map to analyze the feature maps of the classification model.
- Train an image classification model on CIFAR dataset with Vision Transformers (ViT).
## Project: Image Classification
#### Train an image classification model on CIFAR dataset with ResNet-18. Report the classification accuracy on the test set.
- For this project, I use the CIFAR10 dataset. It consists of 60000 32x32 color images in 10 classes, with 6000 images per class. ResNet-18 is a convolutional neural network that is 18 layers deep.
#### Use different data augmentation techniques and different ways to avoid overfitting. Report the classification accuracy on the test set with different types of data augmentations.
- Data Augmentation is simply creating variations of training data to increases its size at the same time regularizes the network. Some common data augmentation techniques in image classification include
    - Random Flips and Rotations
    - Random Crop and Center Crop
    - Normalizing the image
    - ...
- The choice of data augmentation techniques depends on the specific characteristics of the dataset and the problem at hand. It’s often beneficial to experiment with different combinations of augmentation techniques to find the ones that work best.
#### Visualize the class activation maps of the trained models.
