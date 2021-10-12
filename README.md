# Breast-Cancer-Summer-project

Breast Cancer Prediction using SVM
1. Project Requirements or Dependencies
Anaconda Python (to get ML Libraries)

2. Required Dataset
Dataset can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

ID number

Diagnosis (M = malignant, B = benign)

(3 – 32) Ten real-valued features are computed for each cell nucleus:

radius (mean of distances from center to points on the perimeter)
texture (standard deviation of gray-scale values)

perimeter

area

smoothness (local variation in radius lengths)

compactness (perimeter^2 / area - 1.0)

concavity (severity of concave portions of the contour)

concave points (number of concave portions of the contour)

symmetry

fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

3.Build and Train model to predict using SVM

Using SVM (Support Vector Machines) we build and train a model using human cell records, and classify cells to predict whether the samples are benign or malignant


Breast Cancer Wisconsin (Diagnostic) Original Data Set

Attribute Information:

Sample code number: ID number
Clump Thickness:1-10

Uniformity of Cell size:1-10


Uniformity of Cell shape:1-10

Marginal Adhesion:1-10

Single Epithelial Cell Size:1-10

Bare Nuclei:1-10

Bland Chromatin:1-10

Normal Nucleoli:1-10

Mitoses:1-10

Class: (2 for Benign, 4 for Malignant)
