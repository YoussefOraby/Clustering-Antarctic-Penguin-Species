# Clustering-Antarctic-Penguin-Species

This project applies unsupervised machine learning to identify possible penguin species groups based on physical measurements.

## Problem

Researchers collected penguin measurements in Antarctica but did not record the species of each penguin.  
However, they know that at least three species exist in the region:

Adelie  
Chinstrap  
Gentoo

The objective is to identify natural groups in the dataset using clustering.

## Dataset

Columns included in the dataset:

culmen_length_mm  
culmen_depth_mm  
flipper_length_mm  
body_mass_g  
sex

## Method

K-Means clustering is used to group penguins based on their physical characteristics.

Steps:

1 Load dataset  
2 Remove missing values  
3 Normalize features using StandardScaler  
4 Apply K-Means clustering  
5 Identify clusters representing possible species groups

Number of clusters: 3

## Libraries

pandas  
scikit-learn  
matplotlib

Run the script

python src/penguin_clustering.py
