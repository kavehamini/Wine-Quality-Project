# Wine Quality Project
 
## This project is in progress
 
 
## Introduction

In this project, a dataset on wine quality from the UCI website (https://archive.ics.uci.edu/ml/datasets/wine+quality) is analyzed, visualized and investigated and also regression and classification models are employed to predict the quality of wines on the basis of their features.

## Data Visulalization

Checking for null values in the columns using a heatmap

<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_1.png">
</p>

<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_2.png">
</p>
In the columns in any of the red wine or white wine datasets we do not have any null values. In case there was any null value there would be a different shade of blue for that perticular value.

Checking the correlation bertween the features in red wine dataset.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_3.png">
</p>

<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_4.png">
</p>

Among the features in the red wine dataset, citric acid and fixed acidity (0.67), density and fixed acidity (0.67) and total sulfure dioxide and free sulfure dioxide (0.67) have the highest positive correlations and citric acid and volatile acidity (-0.55), citric acid and pH (-0.54), alcohol and density (-0.5) and fixed acidity and pH (-0.68) have the highest negative correlations.

In red wine dataset, 'alcohol', 'sulphates' and 'citric acid' have the highest positive correlations with the quality and 'volatile acidity', 'total sulfure dioxide' and 'density' have the highest negative correlation with the quality.

Checking the correlation bertween the features in white wine dataset
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_5.png">
</p>

<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_6.png">
</p>

Among the features in the white wine dataset, density and residual sugars (0.84), density and total sulfure oxide (0.51) and total sulfure dioxide and free sulfure dioxide (0.62) have the highest positive correlations. On the other hand alcohol and density (-0.78) have the highest negative correlation.

In white wine dataset, 'alcohol', 'pH' and 'sulphates' have the highest positive correlations with the quality and 'density', 'chlorides' and 'volatile acidity' have the highest negative correlation with the quality.

Plotting out distributions for the variables in red wine dataset to check the normality of the data.
https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_7.png


