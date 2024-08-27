# Wine_Quality-EDA

Wine Quality EDA

Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Wine Quality dataset to uncover patterns and relationships between various chemical properties of wine and its quality rating. The insights from this analysis aim to provide a deeper understanding of the factors that influence wine quality.

Dataset

Source: UCI Machine Learning Repository - Wine Quality Data Set

Description: The dataset includes chemical properties of red and white wine samples along with quality ratings on a scale from 0 to 10. Key features include:
Fixed Acidity,Volatile Acidity,Citric Acid,Residual Sugar,Chlorides,Free Sulfur Dioxide,Total Sulfur Dioxide,Density,pH,Sulphates,Alcohol,Quality (target variable)

Objectives

1:Perform data cleaning and preprocessing to ensure data quality.
2:Conduct EDA to understand the distribution of wine quality and the relationships between chemical properties and quality.
3:Identify key factors that most strongly correlate with wine quality.
4:Visualize trends and patterns using various data visualization techniques.

Tools and Libraries

* Python: Used for data analysis and visualization.
* Pandas: For data manipulation and cleaning.
* NumPy: For numerical computations.
* Matplotlib & Seaborn: For data visualization.
* Scikit-learn: For feature engineering and model preparation.

Key Steps in the Analysis

1)Data Cleaning:

Handled missing values and outliers.
Standardized and normalized data as needed.
Exploratory Data Analysis:
Analyzed the distribution of quality ratings.
Explored correlations between features such as alcohol, acidity, and quality.
Visualized the relationships using histograms, scatter plots, heatmaps, and box plots.

2)Insights:

Alcohol content and volatile acidity were identified as significant predictors of higher quality ratings.
Wines with lower residual sugar tended to have higher quality scores.
Correlation analysis revealed that certain features, like alcohol, had a positive impact on quality, while others, like volatile acidity, had a negative impact.
Conclusions
The EDA provided valuable insights into the factors that influence wine quality. These findings can help wine producers focus on optimizing specific chemical properties to improve their product's quality.

How to Run the Project

! Clone the repository: git clone [repository-link]
! Install the required libraries: pip install -r requirements.txt
! Run the analysis notebook: Open wine_quality_eda.ipynb in Jupyter Notebook.

Future Work
1.Apply machine learning models like Logistic Regression, Random Forest, or SVM to predict wine quality based on chemical properties.
2.Explore feature selection techniques to improve model performance.
3.Extend the analysis to include external data sources, such as climate data, to enhance predictions.
