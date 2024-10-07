<h1 align="center">Hi 👋, I'm Yousif</h1>
<h3 align="center">Future Data Scientist | AI Engineer | ML Engineer</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/yousifbahnasy" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="yousifbahnasy" height="30" width="40" /></a>
<a href="https://instagram.com/yousif_-bahnasy" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="yousif_-bahnasy" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

# Diabetes Prediction Using Machine Learning

## Project Overview
Diabetes is a chronic disease affecting millions worldwide, with severe complications such as heart disease, kidney failure, and blindness. Early detection is crucial in managing and preventing these complications. This project uses machine learning algorithms to predict diabetes by analyzing patient data, including factors such as age, BMI, blood glucose levels, and more.

### Agenda:
- Introduction
- Data Collection
- Data Exploration & Cleaning
- Feature Extraction
- Data Preprocessing
- Data Splitting into Training and Testing Sets
- Model Selection
- Graphical User Interface (GUI)
- Data Visualization

## 1. Introduction
Machine learning has become a powerful tool for predicting and managing diabetes. By analyzing large datasets from health records and other sources, machine learning can detect patterns and predict the likelihood of developing diabetes. This project focuses on leveraging various machine learning algorithms to build a predictive model for diabetes.

## 2. Data Collection
The dataset includes the following features:
- Gender
- Age
- Hypertension
- Heart disease
- Smoking history
- BMI
- HbA1c level
- Blood glucose level

## 3. Data Exploration & Cleaning
Before analyzing the data, we explored the dataset to understand the distribution of features and ensure the data's reliability. Any missing or irrelevant data were removed to maintain the accuracy of insights drawn from the data.

## 4. Feature Extraction
Several features, including medical history and demographic data, were extracted to predict whether a patient is likely to have diabetes.

## 5. Data Preprocessing
We standardized the dataset, removed outliers and irrelevant data, and prepared the dataset for modeling. The dataset was split into training and testing sets to ensure the model's performance on unseen data.

## 6. Data Splitting
The data was split into two sets:
- **Training Set:** Used to train the model
- **Testing Set:** Used to evaluate the model’s performance on new data

## 7. Model Selection
Several machine learning algorithms were evaluated, including:
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Naive Bayes Classifier
- Random Forest Classifier

### Model Performance with GridSearchCV:
- **KNN:** Accuracy = 0.9625
- **Naive Bayes:** Accuracy = 0.9600
- **Decision Tree:** Accuracy = 0.9719
- **Random Forest:** Accuracy = 0.9699

We selected the **Decision Tree** algorithm due to its high accuracy.

## 8. GUI
A graphical user interface (GUI) was developed to allow users to interact with the prediction model, making it accessible to a broader audience. The GUI allows users to input patient data and receive diabetes predictions.

## 9. Data Visualization
To compare model performance, we visualized the results of the four models mentioned above. The visualizations provide a clear understanding of each model’s accuracy and performance metrics.

## Conclusion
This project demonstrates how machine learning can be utilized for diabetes prediction, helping in early detection and management. By analyzing health-related features and optimizing various models, we have developed a highly accurate Decision Tree model for diabetes prediction.
