<div align="center">
  
![image](https://github.com/user-attachments/assets/eb3535c2-35e2-40de-af0c-3dc39996e10b)




### **Artificial Intelligence (Lab)**

### Lab 04: Supervised Learning - Classification with k-NN and Decision Trees

### Syed Muhammad Naqi Raza
### 2022574
### Cyber Security

</div>


![image](https://github.com/user-attachments/assets/b4b660c3-e4bc-4159-afa6-36c369ad00b3)

![image](https://github.com/user-attachments/assets/9e181aa3-29bd-44fa-be65-5f8fdbfa708f)


# Titanic Dataset Classification with k-NN and Decision Tree

**Overview**

This project demonstrates two supervised machine learning models—k-Nearest Neighbors (k-NN) and Decision Tree Classifier—using the Titanic dataset to predict the survival of passengers based on various features such as age, gender, ticket class, and fare. The project explores the following tasks:

  - Data exploration and preprocessing.
  
  - Model training and evaluation using k-NN and Decision Trees.
  
  - Visualization of decision boundaries and classification results.

# Project Structure

This project consists of the following key components:

1. **Data Exploration and Preprocessing:**

  - Handling missing data, encoding categorical features, and scaling numerical data.
  
  - Splitting the dataset into training and testing sets.

2. **k-Nearest Neighbors (k-NN):**

  - A simple but effective algorithm that classifies samples based on the majority class among the nearest      neighbors.
  
  - k = 3 is used as the number of neighbors in this implementation.
  
  - Accuracy and performance metrics are calculated based on the test dataset.

3. **Decision Tree Classifier:**

  - A decision tree is built to classify passengers based on features such as class, age, and fare.
  
  - Gini Index is used as the criterion, with a maximum depth of 3.
  
  - The decision tree is visualized to show decision paths for the survival classification.

4. **Performance Evaluation:**

  - Both models are evaluated using accuracy, precision, recall, and F1-score.
  
  - Graphical visualization is used to demonstrate classification results and decision boundaries.

# Dataset

The dataset used is the Titanic dataset from the Kaggle competition. It contains information about passengers on the Titanic, such as:

- Pclass: Passenger class (1st, 2nd, 3rd).
- Age: Age of the passengers.
- Sex: Gender of the passengers.
- Fare: Ticket fare paid.
- Embarked: Port of Embarkation (S, C, Q).
- Survived: Whether the passenger survived (1) or not (0).

Download the dataset from the following link:

https://www.kaggle.com/c/titanic/data

# How to Run

1. Clone this repository or download the project files.
   
2. Upload the Titanic dataset (train.csv) into your working directory.
3. Run the Python script for k-NN and Decision Tree models:
  - knn_titanic.py (k-Nearest Neighbors)
  - decision_tree_titanic.py (Decision Tree)
  
4. The scripts will output:
   
  - Classification accuracy.
  - Precision, recall, and F1-score.
  - Graphical visualizations of the classification results and decision trees.

# Installation Requirements

  - Python 3.x
  - Libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  
You can install the necessary libraries using pip:


**pip install numpy pandas scikit-learn matplotlib seaborn**

# License

This project is licensed under the MIT License.
