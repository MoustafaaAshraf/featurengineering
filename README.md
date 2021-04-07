## featurengineering
Package for automating preparing features for machine learning modelling.


--------------
So far, The package is equiped by three main functionalities:
1. EDA: Printing info about dataframe.
2. EDA: Printing percentages of missing values in each column in the dataframe.
3. EDA: Creating different categories lists for features, either continuous, catgorical or discrete.
4. EDA: Showing a Heatmap based on correlation between continuous and discrete features in the dataframe.
5. Linear Model Assumptions: plotting kde, boxplot, and distribution plots
        Aimed at disgnosing 
        1. skewed/not normal distributions
        2. Outliers
6. Feature Engineering: Encoding Rare labels as 'Other' based on a threshhold given by user.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scipy

## Installation
pip install featurengineering==1.0

