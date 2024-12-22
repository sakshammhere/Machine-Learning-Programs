# Machine-Learning-Programs
Iris flower classification
Introduction : 
This repository contains a machine learning program that classifies iris flowers into different species based on their features.
The program uses a Random Forest classifier to predict the class of flowers from the Iris dataset.
--------------------------------------------------------------------------------------------------------------------------------
Dataset: 
The Iris dataset consists of 150 samples of iris flowers, each with the following features:
Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)
The target variable is the species of the iris flower, which can be one of the following classes:   Setosa (labelled as 0)
                                                                                                    Versicolor (labelled as 1)
                                                                                                    Virginica (labelled as 2)
--------------------------------------------------------------------------------------------------------------------------------                                                                                                    
Description:
Preprocessing the data : 
X = iris_data.drop(columns=['flower_class'])
y = iris_data['flower_class']
I have dropped the flower class because there is no use case to train the data over the flower_class, the data is only trained on septal and petal (length and width).

                                                                                                    
                                                                                                    
