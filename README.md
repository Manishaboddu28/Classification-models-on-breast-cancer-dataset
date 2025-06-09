# 🩺 Breast Cancer Classification Using Machine Learning
This repository showcases how different classification models perform on the Breast Cancer Wisconsin dataset. The aim is to build predictive models that can accurately classify whether a tumor is benign or malignant.

# 📁 Project Structure
Classification_Models_On_Breast_Cancer_Dataset.ipynb: Main Jupyter notebook containing all the data processing, visualizations, model building, and evaluation.

dataset.csv: Breast Cancer dataset (imported from Kaggle or sklearn).

README.md: Project overview (this file).

# 📊 Dataset Used
We used the Breast Cancer Wisconsin (Diagnostic) Data Set, which includes features computed from digitized images of fine needle aspirates (FNA) of breast masses.

# 📌 Features include:
Radius, Texture, Perimeter, Area, Smoothness

Compactness, Concavity, Symmetry, and more

Diagnosis (Target): M = Malignant, B = Benign

➡️ Dataset Source: UCI Machine Learning Repository or Kaggle Version

# ⚙️ ML Models Used
We trained and evaluated the following classification algorithms:

✅ Logistic Regression

✅ K-Nearest Neighbors (KNN)

✅ Naive Bayes

✅ Support Vector Machine (SVM)

✅ Decision Tree

✅ Random Forest

Each model's performance is compared based on:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

# 🧠 Workflow Summary
Import Libraries

Load Dataset

EDA (Exploratory Data Analysis) - Visualize distributions and correlations

Data Cleaning - Handle missing values

Feature Scaling

Train-Test Split

Model Training & Evaluation

Result Comparison

# 📈 Key Results
Model	Accuracy

Logistic Regression	~97%

KNN	~96%

Naive Bayes	~94%

SVM	~98%

Decision Tree	~96%

Random Forest	~98%

✅ SVM and Random Forest gave the best performance on this dataset.
