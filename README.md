# Iris Flower Classification

This project focuses on classifying the Iris flower species using machine learning algorithms. The dataset used is the well-known Iris dataset, which contains measurements of 150 Iris flowers from three different species: Setosa, Versicolor, and Virginica. The goal is to predict the species of the flower based on the given measurements of the petals and sepals.

## Project Overview

In this project, we use the following machine learning algorithms:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Decision Tree Classifier**

These models are trained on the Iris dataset to classify flower species based on input features such as sepal length, sepal width, petal length, and petal width.

## Libraries Used

- `pandas` - For data manipulation and analysis.
- `numpy` - For numerical operations.
- `seaborn` & `matplotlib` - For data visualization.
- `scikit-learn` - For machine learning algorithms and metrics.

## Steps Involved

1. **Loading the Dataset**: 
   - The Iris dataset is loaded using `sklearn.datasets.load_iris()`.
   - The data is then converted into a pandas DataFrame for better readability and exploration.
   
2. **Data Exploration**:
   - Basic statistics and a heatmap of correlations between features are displayed.
   
3. **Data Preprocessing**:
   - The dataset is split into features (X) and target (Y) variables.
   - The data is then divided into training and testing sets using `train_test_split` from `sklearn.model_selection`.

4. **Model Training**:
   - The models (SVM, Logistic Regression, and Decision Tree) are trained on the training data.
   
5. **Model Evaluation**:
   - The models' performance is evaluated using accuracy scores and classification reports.
   
6. **Testing the Model with Custom Input**:
   - A custom sample is predicted using the trained model.

## Code Walkthrough

1. **Data Exploration**: 
   - Visualize correlations and describe the dataset.
   
2. **Model Building**:
   - Three models are built and trained:
     - **Support Vector Machine (SVC)**: A powerful classifier for classification problems.
     - **Logistic Regression**: A statistical method for binary classification that can be extended to multi-class problems.
     - **Decision Tree Classifier**: A model that splits the data based on feature values to make predictions.
   
3. **Evaluation**:
   - Accuracy scores and detailed classification reports (precision, recall, F1-score) are printed for each model.

4. **Prediction**:
   - The trained models are tested with custom input to predict the species of the Iris flowers.

## Example Output

### Accuracy Scores:

- **Support Vector Machine (SVM)**: 96.67% accuracy
- **Logistic Regression**: 96.67% accuracy
- **Decision Tree Classifier**: 96.67% accuracy

### Classification Report (SVM):

          precision    recall  f1-score   support

 setosa       1.00      1.00      1.00         9
accuracy                          1.00        25
macro avg     1.00      1.00      1.00        25
weighted avg  1.00      1.00      1.00        25


### Custom Input Prediction:
Prediction of Species: ['setosa' 'setosa' 'virginica']


## Requirements

To run the code, you need to install the following Python libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn


Conclusion
The project demonstrates the application of machine learning models on the Iris dataset for classification purposes. It covers data preprocessing, model training, evaluation, and custom predictions. This project can be extended to other classification tasks or datasets with similar structures.

