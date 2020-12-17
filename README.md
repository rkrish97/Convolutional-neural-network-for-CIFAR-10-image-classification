# Convolutional-neural-network-for-CIFAR-10-image-classification
## Using CNN for CIFAR-10 Image Classification

CIFAR-10 dataset contains 32x32 color images from 10 classes: __airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck__:

![cifar10](https://drive.google.com/uc?export=view&id=1u85vm3NcizRvOm-KjagrGl66PkahPt1n)

## 1. Prepare data 

We need to normalize inputs like this: $$x_{norm} = \frac{x}{255} - 0.5$$

We need to convert class labels to one-hot encoded vectors. Use __keras.utils.to_categorical__.

## 2. Define the architecture you want to train your model with

## 3. Train your model
The model was trained for 10 epochs

## 4. ## Evaluate model

The model is evaluated on the test set. The confusion matrix is printed. In the confusion matrix, the brighter the colour of the cell indicates a high value in that cell. Ideally, the diagonals of the matrix should be of high values indicating that the model is correctly predicting the true labels.

## 5. Visualize Class Activiation Map

The following code prints the image under consideration, it's corresponding activation map and the activation map overlayed on the image. This helps us finding out the high level features that helped the network make the prediction/classification that it made.
