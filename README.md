# Handling-Imbalanced-Data
In this repository I would be presenting some ways to handle the imbalanced data using the bank data.
### Dataset
Dataset is taken from 'Kaggle'. </br>
Link- https://www.kaggle.com/datasets/nimishsawant/bankfull

### Method for Handling Data
#### Undersampling
Undersampling can be defined as removing some observations of the majority class. This is done until the majority and minority class is balanced out.
#### Oversampling
Oversampling can be defined as adding more copies to the minority class. Oversampling can be a good choice when you don’t have a ton of data to work with.
#### Synthetic Minority Oversampling Technique (SMOTE)
SMOTE (Synthetic Minority Oversampling Technique) works by randomly picking a point from the minority class and computing the k-nearest neighbors for this point. The synthetic points are added between the chosen point and its neighbors.</br>

SMOTE algorithm works in 4 simple steps:

- Choose a minority class as the input vector.
- Find its k nearest neighbors (k_neighbors is specified as an argument in the SMOTE() function).
- Choose one of these neighbors and place a synthetic point anywhere on the line joining the point under consideration and its chosen neighbor.
- Repeat the steps until the data is balanced.</br></br>

Reference: 10 Techniques to Solve Imbalanced Classes in Machine Learning (Updated 2024), https://www.analyticsvidhya.com/blog/2020/07/10-techniques-to-deal-with-class-imbalance-in-machine-learning/
