# KNN Algorithm from Scratch

## Project Overview
This project recreates the K-Nearest Neighbors algorithm from scratch using distance concepts like L-2 Norm(Euclidean Distance). It then compares it to the SKlearn KNN implementation. The custom model created can perform both regression and classification tasks. TThe dataset used for classification is the wine dataset. The dataset contains 178 samples with 13 continuous features and three classes corresponding to three different cultivars of wine. The code below uses the dataset API to import and split it into a train and test set. The dataset used for regression is the Auto MPG dataset. The dataset contains information about car fuel efficiency (miles per gallon) with 398 samples and features such as cylinders, displacement, horsepower and more. The code below uses the dataset API to import and split it into a train and test set.

Recreating the KNN algorithm provides insights into

* Underlying concepts of the algorithm
* Strenghts and Drawbacks of the algorithm
* Customization potential and Use cases for the algorithm

For a detailed explanation on the theory used for this computation, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/build-k-nearest-neighbors-knn-from-scratch-10dbc5b21254)

### Code
You can find the code for this project [here](https://github.com/ayoakin/KNN_From_Scratch/blob/main/KNN_From_Scratch.ipynb).

File overview:

* `KNN_From_Scratch.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Python packages
  * pandas
  * numpy
  * scikit-learn
  * Matplotlib

### Data

The datasets used for this implementation are
* the Wine dataset originally on [UCI.edu](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data).
* the Auto MPG dataset originally on [UCI.edu](https://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data).
