# Kannada - MnistThis is a Machine Learning project using Classical machine learning algorithms with Scikit-learn(sklearn). More specifically, it is about a classification problem in regard to the recognition and prediction of the Kannada MNIST hand-written digits. 

## Source
The project uses part of data that was published in: Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language." arXiv preprint arXiv:1908.01242 (2019). 

It is about an alternative dataset with reference to the popular MNIST digits database, and the link to the ["dataset"](https://www.kaggle.com/competitions/Kannada-MNIST).

## Description
["Kannada"](https://en.wikipedia.org/wiki/Kannada) is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script. 

The format is similar to MNIST in terms of how the data is structured. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive, and each pixel column in the training set has a name like pixel{x}, where x is an integer between 0 and 783, inclusive. Overall, there are 10 classes since the handwritten digits range from 0 to 9.

## Workflow
Started by performing PCA to reduce the number of features from 728 to 10 , applied all the classification algorithms, and similarly repeated the same with 15,20,25, and 30 features using PCA.

## Purpose
The classification of the images of hand-written digits, and the prediction of those numbers. A range of deep neural network architectures and techniques were applied with the final goal of finding the optimal model for the digits' predictions.

## Observations
The models as expected were doing particularly better when the number of features was high indicating that there was less correlation among the features hence better performance.

## Environment
Jupyter notebook
