# Machine Learning Model Comparison: Decision Trees vs Logistic Regression

## 📌 Overview
This project aims to compare the performance of two machine learning models that incorporate **implicit feature selection**: **Decision Trees** and **Logistic Regression**. The study evaluates the accuracy of both models and their ability to perform feature selection using different regularization techniques.

## 📊 Objective
The objective of this project is to:
- Assess and compare the generalization accuracy of **Decision Trees** and **Logistic Regression** models.
- Tune model hyperparameters using **grid search** for optimal performance.
- Analyze feature selection capability in both models.
- Compare the stability and consistency of selected features across multiple runs.

## 📂 Dataset
The dataset used for this project is **Student_Perf.csv**, derived from the original UCI dataset. It contains multiple features related to student academic performance. The feature descriptions and additional details can be found in the original dataset source.

## 📌 Tasks Performed
### 🔹 **Task 1: Model Accuracy Assessment**
- Implemented a **baseline** generalization accuracy assessment for both **Decision Trees** and **Logistic Regression** models.
- Conducted **hyperparameter tuning** using a **grid search** approach to optimize the complexity of the models.
- Applied **L1 regularization** to Logistic Regression to assess its impact on feature selection.
- Generated a **performance comparison chart** to illustrate accuracy differences.

### 🔹 **Task 2: Feature Selection Analysis**
- Identified which features were selected or ignored by both models.
- Examined the **stability** of feature selection across multiple runs.
- Analyzed the level of agreement between feature selection in **Logistic Regression** and **Decision Trees**.

## 📊 Results & Insights
- The **Decision Tree model** was tuned using depth and minimum samples split to optimize its performance.
- The **Logistic Regression model** utilized **L1 regularization** to enforce feature sparsity.
- The final **accuracy comparison chart** demonstrated the impact of regularization and hyperparameter tuning on generalization performance.
- Feature selection was analyzed, highlighting which features had the most predictive power.
