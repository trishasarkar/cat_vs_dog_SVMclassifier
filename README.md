# Cat vs Dog Classifier

A machine learning model that can identify between cat and dog images is a classic example  of applications in the space of Machine Learning. The first thought of creating a classifier would be ConvNets, however this project is an attempt to use only ML Algorithms to solve the problem using a basic feature extraction technique.

## Prerequisites

Dataset Used: Extracted 302 images (equal number of dog and cat images) from the dataset [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/rules) 

Source: Kaggle

This project was made using [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true).

## Procedure

Algorithm used: Ensemble Methods - Decision Tree, Support Vector Machine, K Nearest Neighbour
* Pre-process: Store the image labels by stripping off parts that are not needed from image name.
* Logic: All the images are converted to feature vectors with  raw pixel intensities by flattening them into a 1D array.
The dataset is split into training and testing data and fed to the 2 models created.
* Evaluation: Accuracy of the models are calculated. A heat map is used to visualise the confusion matrix.

## Inference & Use Cases

* The output using ensemble methods is slightly better and crosses the 60% marking.

## Contributors

* [Trisha Sarkar](https://github.com/trishasarkar)

## Points to be Noted

* The accuracy of the model is not very high due to the following reasons -
  1. Use of raw pixel values for feature extraction - they could be influenced by intensity values.
  2. An algorithm like CNN would yield better results with this kind of data.
  3. Better training of the model needed.
