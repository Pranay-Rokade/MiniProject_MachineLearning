# MiniProject_MachineLearning

This project compares the performance of various classification algorithms using the Heart Attack dataset. The analysis includes Exploratory Data Analysis (EDA), data preprocessing, and implementation of multiple classification techniques.

## Dataset

**Name**: Heart Attack Data Set  
**Source**: [Kaggle](https://www.kaggle.com/datasets/pritsheta/heart-attack)

## Problem Statement

To evaluate and compare the performance of various classification algorithms in predicting outcomes using the Heart Attack dataset.

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Visualized data trends and patterns.
   - Used histograms to analyze feature distributions.
   - Created a correlation matrix to identify feature relationships.

2. **Data Preprocessing**:
   - Split the dataset into training and testing sets.
   - Scaled features using `StandardScaler` for uniformity.

3. **Classification Models**:
   Implemented and evaluated the following algorithms:
   - Logistic Regression
   - Naive Bayes
   - K-Nearest Neighbors (KNN)
   - Decision Trees
   - Random Forest
   - KMeans (clustering for comparison)

4. **Performance Metrics**:
   - Generated classification reports including precision, recall, and F1-score.
   - Visualized confusion matrices for each model.
   - Compiled results into a comparison table.

## Results

| Model               | Accuracy  | Precision | Recall   | F1 Score |
|---------------------|-----------|-----------|----------|----------|
| Logistic Regression | 0.868852  | 0.852941  | 0.90625  | 0.878788 |
| Naive Bayes         | 0.885246  | 0.903226  | 0.87500  | 0.888889 |
| K-Nearest Neighbors | 0.852459  | 0.828571  | 0.90625  | 0.865672 |
| Decision Tree       | 0.786885  | 0.827586  | 0.75000  | 0.786885 |
| Random Forest       | 0.868852  | 0.900000  | 0.84375  | 0.870968 |
| KMeans              | 0.605960  | 0.723728  | 0.60596  | 0.656556 |

### Conclusion

- **Naive Bayes** achieved the highest performance in terms of accuracy and F1-score.
- **Logistic Regression** and **Random Forest** also showed strong results.
- **KMeans**, being a clustering algorithm, demonstrated lower performance for this classification task.

## Tools and Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
