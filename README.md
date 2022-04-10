# Weka3-IRIS-Data-Mining-Model

## Steps
1 - download Weka3 Stable version from the link below:

https://www.cs.waikato.ac.nz/ml/weka/

2 - Open the iris.arff located in data folder inside Weka3 folder

3 - Standardize it

4 - Create the model

## FAQ
Q1 : What's the logic behind choosing split value of petal width as 0.79..?

A1 : The split value is determined by the algorithm as the decision threshold that leads to a series of branches until a leaf node is reached that culminates in a decision of the final class label samples are classified as.

Q2 : Why standardize and not normalize ?

A2 : Both normalize and standardize can be used to scale the data. I prefer to use standardize as it scales the data to zero mean and unit variance (sd=1)
## Screenshots

![App Screenshot](https://raw.githubusercontent.com/AbidaNidhal/Weka3-IRIS-Data-Mining-Mode/main/IRIS-Data-Mining.png)
