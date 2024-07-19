# Sentiment Analysis using Support Vector Machine (SVM)

## Overview
This project involves implementing the Support Vector Machine (SVM) algorithm for sentiment analysis. The objective is to determine the emotional tone or sentiment expressed in text data, such as reviews, social media posts, or comments. The goal is to categorize the text as positive, negative, or neutral, providing insights into public opinion and user sentiments, specifically focusing on the challenges faced by each major U.S. airline.

## Dataset
The designated dataset involves US Airline tweets, capturing sentiments associated with each major U.S. airline. This Twitter data, collected since February 2015, includes initial classification into positive, negative, and neutral categories. Contributors also categorized negative sentiments by identifying reasons such as 'late flight' or 'rude service.'

## Implementation Steps

### 1. Data Loading and Preprocessing
- **Objective**: Load the US Airline tweets dataset.
- **Tasks**:
  - Address missing values.
  - Drop features with more than 90% missing values.
  - Explain the importance of these steps in ensuring dataset quality.

### 2. Exploratory Data Analysis (EDA)
- **Objective**: Visualize and understand the dataset.
- **Tasks**:
  - Create a bar chart depicting different reasons for negative emotions about airports, categorized by each airline.
  - Identify the top three reasons contributing to negative sentiments over all airlines, and create another bar chart.
  - Generate word clouds for negative and positive reviews to highlight the most frequent words.

### 3. Text Processing
- **Objective**: Prepare text data for SVM modeling.
- **Tasks**:
  - Eliminate neutral opinions.
  - Remove stop words and create a separate copy of the data without stop words for comparison.
  - Compare the impact of this processing on classification accuracy.

### 4. Data Splitting
- **Objective**: Split the data for training and testing.
- **Tasks**:
  - Allocate 80% of the data to training and 20% to testing.
  - Create a validation subset within the training data for further cross-validation.

### 5. SVM Model Creation, Grid Search, and Cross-Validation
- **Objective**: Train and optimize SVM models for sentiment classification.
- **Tasks**:
  - Implement SVM models using Radial Basis Function (RBF), Polynomial, and Linear kernels.
  - Perform grid search with 5-fold cross-validation to identify optimal parameters.
  - Report the best model based on accuracy and present the confusion matrix for evaluation.
  - Discuss the models' performance, highlighting any signs of overfitting and comparing results.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, wordcloud

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter notebook or Python scripts provided for each implementation step.

## Results
- Quality and insights from data preprocessing and EDA.
- Classification accuracy and error rates for different SVM models.
- Impact of text processing steps on model performance.
- Optimal parameters and performance comparison for different SVM kernels.

## Conclusion
This project demonstrates the implementation of SVM for sentiment analysis, providing insights into the challenges faced by U.S. airlines based on Twitter data. The use of grid search and cross-validation ensures optimal model performance, with a thorough comparison of results.


