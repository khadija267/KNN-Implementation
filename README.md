# KNN-Implementation
Implementing KNN Algorithm for classification iris dataset according to sepal length and sepal width.
## Iris Dataset:
the iris flower dataset. The dataset consists of 150 data points where each data point is a feature vector describing the attribute of a flower in the dataset, the four dimensions represent:

    sepal length in cm
    sepal width in cm
    petal length in cm
    petal width in cm
    
and the corresponding target y∈ℤ
describes the class of the flower. It uses the integers 0, 1 and 2
And we will deal with first 2 dimensions.

to represent the 3 classes of flowers in this dataset.

    Iris Setosa
    Iris Versicolour
    Iris Virginica
    
## How KNN works:
as any classification algorithm it takes input some data and use the data to determine which class (category) this piece of data belongs to.
The idea behind a KNN classifier is pretty simple: Given a training set X∈ℝN×D and y∈ℤN, we predict the label of a new point x∈ℝD as the label of the majority of its "K nearest neighbor" (hence the name KNN) by some distance measure (e.g the Euclidean distance). Here, N is the number of data points in the dataset, and D is the dimensionality of the data.
