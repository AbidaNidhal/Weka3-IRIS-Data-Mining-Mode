# Weka3-IRIS-Data-Mining-Mode
download Weka3 Stable version
https://www.cs.waikato.ac.nz/ml/weka/
Open the iris.arff
Standardize it
Create the mo
What's the logic behind choosing split value of petal width as 0.79..?
The split value is determined by the algorithm as the decision threshold that leads to a series of branches until a leaf node is reached that culminates in a decision of the final class label samples are classified as.
Both normalize and standardize can be used to scale the data. I prefer to use standardize as it scales the data to zero mean and unit variance (sd=1)
