# data_analytics_space
This analysis explores satellite orbital data collected from the CelesTrak website Using this data, we applied machine learning techniques to predict satellite inclination categories (Low, Medium, High) based on other orbital characteristics





## Table of Contents
- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Methodology](#methodology)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling and Algorithms](#modeling-and-algorithms)
- [Results and Evaluation](#results-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## Introduction
In an age where satellites play a major role in communications, navigation, and Earth observation, understanding their orbital characteristics is more important than ever. The project explores the fascinating world of satellite orbits by using machine learning to estimate a key orbital parameter, inclination. By analysing data from CelesTrak, a comprehensive collection of satellite orbital data, we aim to show that advanced techniques can help us better understand and predict the behavior of objects in Earth’s orbit.

## Dataset Description
Our project begins by collecting data from CelesTrak, a treasure trove of satellite data. We focus on satellites launched from 2000 to the present, and list key orbital parameters such as:

-Mean motion
-Eccentricity
-Inclination
-Right ascension of ascending node
-Argument of perigee
-Mean anomaly
This rich dataset provides a comprehensive view of modern satellite orbits and forms the basis of our analysis.

## Methodology
We used five different machine learning methods to estimate satellite inclination groups:

Random Forest: An integrated learning method for building multiple decision trees.
Gradient Boosting: Another ensemble technique that builds trees sequentially.
Support Vector Machine (SVM): A powerful algorithm for classification tasks.
Neural Network: A deep learning approach mimicking the human brain’s structure.
K-Nearest Neighbours (KNN): A simple yet effective algorithm based on proximity in feature space.

## Data Preprocessing
While raw data is important, it often needs refinement. We use a number of prioritization techniques to ensure the robustness of our analysis:

-Outlier Removal: We use the Z-score method to eliminate outliers that could distort our results.

-Standardization: Make sure all changes are the same.

-Categorization of Inclination: Simplify our guesswork by categorizing ideas into “low,” “medium,” and “high.”

## Exploratory Data Analysis (EDA)
Describe the exploratory analysis performed on the dataset. Highlight key insights, visualizations, and any patterns or trends observed.

## Modeling and Algorithms
Detail the different machine learning or statistical models applied to the data. For each model:
- Explain the rationale behind its selection
- Provide the implementation details
- Discuss any hyperparameter tuning performed

## Results and Evaluation
Results:

Our analysis yielded intriguing results:

- Random Forest emerged as the top performer with an impressive 94.02% accuracy.
  
- Gradient Boosting followed closely with 92.82% accuracy.
- 
- Neural Network and KNN showed moderate performance with accuracies of 85.17% and 83.25% respectively.
- 
- SVM, surprisingly, underperformed with 77.99% accuracy.

## Conclusion
-The project demonstrates the power of machine learning in understanding and predicting satellite orbits. By correctly classifying inclination groups, we are taking a step toward better control and utilization of Earth’s ever-expanding orbital space. As we continue to launch satellites, predictive capabilities will become even more important. The intersection of space technology and data science promises exciting advances as we explore the final frontier.

## Future Work
-This work also demonstrates the potential of machine learning in space science, opening the door to further applications in orbit prediction and location recognition.

