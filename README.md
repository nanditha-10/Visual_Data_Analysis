#Visual Data Analysis in Python
A comprehensive exploration of data visualization techniques, from simple distributions to advanced dimensionality reduction methods.

#Overview
This project demonstrates various data visualization techniques using Python. It covers univariate, multivariate, and whole-dataset visualizations. The implementation utilizes popular libraries like matplotlib, seaborn, and scikit-learn for insightful data exploration and representation.

#Dataset
The dataset used for this project includes a mix of quantitative, categorical, and binary features. It is well-suited for demonstrating different types of visualizations.


1. Dataset

2. Univariate visualization

  2.1 Quantitative features
  
  > Histograms and density plots
    
  > Box plot
    
  > Violin plot
    
  > describe()

  2.2 Categorical and binary features

  > Frequency table

  > Bar plot

3. Multivariate visualization

    3.1 Quantitative vs. Quantitative

      > Correlation matrix
      
      > Scatter plot
      
      > Scatterplot matrix

3.2 Quantitative vs. Categorical

3.3 Categorical vs. Categorical

  > Contingency table

4. Whole dataset visualizations

    4.1 A naive approach

    4.2 Dimensionality reduction

    4.3 t-SNE


#Implemented Techniques : 

1. Univariate Visualization
===========================

  1.1 Quantitative Features
     > Visualized using histograms, boxplots, and density plots to understand distributions.
  1.2 Categorical and Binary Features
     > Bar charts and pie charts to represent counts and proportions.
     
2. Multivariate Visualization
=============================

  2.1 Quantitative vs. Quantitative
    > Scatter plots and correlation heatmaps to explore relationships.
  2.2 Quantitative vs. Categorical
    > Boxplots, violin plots, and strip plots for category-wise distributions.
  2.3 Categorical vs. Categorical
    > Heatmaps and stacked bar charts to show categorical interactions.

3. Whole-Dataset Visualization
=============================

  3.1 Naive Approach
    > Pair plots for quick inspection of relationships across features.
  3.2 Dimensionality Reduction
    > Applied PCA (Principal Component Analysis) to reduce dimensionality and visualize patterns.
  3.3 t-SNE
    > Used t-SNE (t-distributed Stochastic Neighbor Embedding) to represent high-dimensional data in 2D/3D space for clustering and insights.

Libraries:

> pandas
> matplotlib
> seaborn
> scikit-learn
