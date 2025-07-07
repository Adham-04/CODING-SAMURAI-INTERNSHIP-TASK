# 🌸 Iris Flower Classification - Machine Learning Project

This project was developed as part of the **Coding Samurai Machine Learning Internship**. It focuses on classifying the species of Iris flowers based on their sepal and petal dimensions using multiple machine learning algorithms.

---

## 📌 Project Objective

To build, evaluate, and compare classification models that predict the species of an Iris flower using sepal and petal measurements. The project also includes interactive user prediction and data visualization.

---

## 📊 Dataset

The classic **Iris dataset** was used, which includes the following features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)
- Species (Iris-setosa, Iris-versicolor, Iris-virginica)

---

## 🛠️ Models Used

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**

---

## 🔍 Steps Performed

1. **Data Cleaning**
   - Removed duplicates
   - Checked for null values
   - Handled outliers using Z-score method

2. **Data Encoding**
   - Encoded species names into numerical values using `LabelEncoder`

3. **Data Visualization**
   - Pairplot to explore feature relationships
   - Countplot to see class distribution
   - Heatmap to show feature correlations
   - Boxplots to detect outliers per species

4. **Model Training**
   - Split data into training and test sets
   - Trained Logistic Regression, KNN, and Random Forest
   - Evaluated using accuracy, confusion matrix, and classification report

5. **Model Comparison**
   - Displayed a bar chart comparing the accuracy of each model

6. **User Input Prediction**
   - Accepts 4 numeric inputs from the user
   - Predicts the Iris species using the trained Logistic Regression model

---

## 📈 Model Accuracy

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~0.97    |
| K-Nearest Neighbors | ~0.95    |
| Random Forest       | ~0.97    |

> *Note: Accuracy may vary slightly depending on train-test split and data randomness.*

---

## 💡 Prediction Example
- Sepal length (cm) = 5.1
- Sepal width (cm) = 3.5
- Petal length (cm) = 1.4
- Petal width (cm) = 0.2

✅ Predicted Iris Species: Iris-setosa


