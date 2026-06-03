
# Webpage Phishing Detection Using Machine Learning

## Project Overview

This project focuses on detecting phishing webpages using machine learning techniques. Phishing websites are fake or harmful websites that try to mislead users and steal sensitive information.

In this project, URL-based numerical features are used to classify webpages as legitimate or phishing. Features such as URL length, number of dots, slashes, hyphens, and other special characters help describe the structure of each webpage link.

## Dataset

The dataset used in this project is the Webpage Phishing Dataset from Kaggle.

Dataset Source:  
https://www.kaggle.com/datasets/danielfernandon/web-page-phishing-dataset

The target column is `phishing`.

- 0 means legitimate webpage
- 1 means phishing webpage

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Imported required libraries
2. Loaded the dataset
3. Checked dataset shape and information
4. Checked missing values
5. Checked duplicate records
6. Performed statistical analysis
7. Visualized important URL-based features
8. Analyzed phishing and legitimate webpages
9. Applied feature scaling
10. Trained K-Nearest Neighbors model
11. Added Logistic Regression as a comparison model
12. Evaluated models using accuracy, confusion matrix, and classification report

## Models Used

### K-Nearest Neighbors

KNN was used as the main model. It classifies webpages based on similarity with nearby records.

### Logistic Regression

Logistic Regression was added as a comparison model. It predicts the probability of a webpage being legitimate or phishing.

## Model Comparison Result

KNN achieved an accuracy of 0.770, while Logistic Regression achieved an accuracy of 0.774.

Logistic Regression performed slightly better than KNN, but the difference was very small. Both models performed almost similarly on the dataset.

## Key Findings

- The dataset was clean and ready for analysis.
- There were no missing values.
- Most URLs were short, but some URLs were extremely long.
- Phishing URLs showed more variation and complexity.
- URL length, number of slashes, and special characters were useful indicators.
- Feature scaling helped the machine learning models perform fairly.
- Logistic Regression performed slightly better than KNN based on accuracy.

## Conclusion

This project shows that URL-based numerical features can be useful for detecting phishing webpages. By using data cleaning, visualization, feature scaling, and machine learning models, suspicious webpages can be identified effectively.

The project also shows that comparing more than one model makes the result more reliable.
