# Adult Income Classification

This project predicts whether an individual's income exceeds $50K/year based on demographic and employment-related attributes using the UCI Adult Census Income dataset.

#Dataset

- **Source**: UCI Machine Learning Repository
- **Records**: 48,842
- **Features**: 14 (Age, Education, Workclass, Hours-per-week, Capital-gain/loss, etc.)
- **Target**: Income (<=50K or >50K)

##Workflow Summary

1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Standardized continuous features

2. **Exploratory Data Analysis (EDA)**
   - Class imbalance (~75% <=50K, ~25% >50K)
   - Correlation heatmaps
   - Feature distributions

3. **PCA (Dimensionality Reduction)**
   - First 3 components explained ~33.2% variance

4. **Model Training & Evaluation**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Naive Bayes
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Neural Network (MLPClassifier)

5. **Metrics Used**
   - Accuracy, Precision, Recall, F1-Score
   - ROC Curves & AUC (emphasis on F1 & AUC due to class imbalance)

## Best Model

- **Random Forest**
  - Accuracy: 85.2%
  - Precision: 74.2%
  - Recall: 63.5%
  - F1 Score: 68.5%
  - AUC: 0.905

## Project Files

- `FDS_PROJECT_UPDATED.ipynb`: Jupyter notebook with full code and results
- `Adult
