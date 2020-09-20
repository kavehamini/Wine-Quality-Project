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


## Checking the correlations among the features

Creating pairplots to check the correlations in red wine dataset.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_11.png">
</p>

Creating pairplots to check the correlations in white wine dataset.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_12.png">
</p>
The scatter plots in the pairplots above show the correlations and dependence of different features on each other.

## Visulization of features

#### Number of wines in each quality
Making a bar plot of the number of wines in each quality.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_13.png">
</p>
In the case of both datasets (red and white wines), we have the most number of wines with the qualities 5, 6 and 7.

#### Quality and alcohol
Making a bar plot of the quality of the wines versus their average alcohol content.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_14.png">
</p>
As observed in the graph above, the wines of qualities 3, 4, 5 and 6 in general have an average alcohol contect of around 10%, whereas higher quality wines (quality 7, 8 and 9) have higher alcohol content (11-12%).

#### Quality and pH
Making a bar plot of the quality of the wines versus their average pH.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_15.png">
</p>
The average pH of all wines appears to be between 3 and 3.5.

#### Quality and residual sugars
Making a bar plot of the quality of the wines versus their average residual sugar.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_16.png">
</p>
In general white wines have more residual sugars than red wines. Red wines all have similar residual sugars (around 2.5) however average residual sugar content of white wines varies between 4 and 7. The quality of wines however does not show much dependence on the residual sugars content.

#### Quality and citric acid
Making a bar plot of the quality of the wines versus their average citric acid.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_17.png">
</p>
For white wines, the citric acid does not seem to be playing a significant role in quality although white wines of quality 9 have higher citric acid content. However, in the case of red wines the higher the citric acid content, the higher the quality.

#### Quality and sulphates
Making a bar plot of the quality of the wines versus their average sulphates content.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_18.png">
</p>
All white wines have the same level of sulphates (around 5) however for red wines the higher the sulphate content of the wine, the higher its quality.

#### Quality and chlorides
Making a bar plot of the quality of the wines versus their average chloride content.
<p align="center">
<img src="https://github.com/kavehamini/Wine-Quality-Project/blob/master/figure_19.png">
</p>
In the case of both red and white wines the lower the chlorides content of the wine, the higher its quality. Also red wines have much higher chlorides content in comparison to white wines.
