# Mushroom Classification using Machine Learning 🍄

## 📌 Project Overview
This project focuses on predicting whether a mushroom is edible or poisonous based on its physical characteristics using various Machine Learning algorithms.

## 📊 Dataset
* **Source:** UCI Machine Learning Repository
* **Dataset Name:** Mushroom Dataset
* **Instances:** 8,124 rows of data

## ⚙️ Models and Techniques Evaluated
To find the most accurate prediction algorithm, our group evaluated the following classification models:
1. Decision Tree (IT25103896)
2. Logistic Regression (IT25103919)
3. K-Nearest Neighbors - KNN (IT25103942)
4. Random Forest (IT25103909)
5. Support Vector Machine - SVM (IT25103870)
6. Multi-Layer Perceptron - MLP/ANN (IT25103931)

**Validation Technique:** 
To ensure the models' reliability and to avoid overfitting, **Stratified 5-Fold Cross Validation** was strictly utilized during the evaluation phase. GridSearchCV was also used for hyperparameter tuning.

## 📈 Results and Visualizations

### Model Accuracies
*(The chart below illustrates the comparison of accuracies across all evaluated models)*

![Model Accuracies](results/accuracy_chart.png)

### Confusion Matrices
*(Example Confusion Matrix from the evaluation)*

![Confusion Matrix](results/confusion_matrix.png)

## 💻 Source Code
The complete code implementation, including data preprocessing, model training, and evaluation, is provided in the **[Group_pipeline.ipynb](Group_pipeline.ipynb)** file in this repository.
