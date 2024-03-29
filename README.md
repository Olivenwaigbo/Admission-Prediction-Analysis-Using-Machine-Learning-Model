# Admission Prediction Analysis Using-Machine Learning Model


This project aims to predict admission outcomes for a given set of applicants using the Gradient Boost Classifier model. After experimenting with various machine learning models, including Logistics Regression, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Random Forest Classifier, we concluded that the Gradient Boosting Classifier yielded the best results and hence was selected for the final prediction model.

## Introduction
Admission prediction is a crucial task for educational institutions and organizations. By leveraging machine learning techniques, we can develop models that analyze applicant data and predict their chances of admission based on historical patterns and trends. The Gradient Boost Classifier is a powerful algorithm that combines multiple weak predictive models, such as decision trees, to create a strong ensemble model capable of accurate predictions.



## Features
The admission prediction model utilizes several features of applicants to make accurate predictions. Some of the key features include:

- GRE Score: The applicant's Graduate Record Examination (GRE) score, which measures their aptitude for graduate-level studies.
- TOEFL Score: The applicant's Test of English as a Foreign Language (TOEFL) score, which assesses their proficiency in the English language.
- University Rating: The rating of the university or institution from which the applicant completed their undergraduate studies.
- Statement of Purpose (SOP): A statement provided by the applicant, describing their objectives, research interests, and career goals.
- Letter of Recommendation (LOR): The strength of the recommendation letters provided by individuals familiar with the applicant's academic and professional background.
- Undergraduate GPA: The applicant's undergraduate Grade Point Average (GPA), reflecting their academic performance during their previous studies.
- Research Experience: A binary indicator representing whether the applicant has prior research experience or not.
- Chance of Admission: The target variable indicating the probability of an applicant being admitted, ranging from 0 to 1.


## Dataset
The dataset used for training and testing the admission prediction model is  included in this repository. The dataset  includes features such as GRE Score, TOEFL Score, University Rating, Statement of purpose, CGPA, Letter of recomendation, and Research, along with the corresponding Admission Chances.

## Model Selection
During the development of this admission prediction system, we experimented with multiple machine learning algorithms, including Logistics Regression, SVM, K-Nearest Neighbors (KNN), Random Forest Classifier, and Gradient Boosting Classifier. After rigorous testing and comparison, we found that the Gradient Boosting Classifier consistently outperformed the other models in terms of predictive accuracy, precision, and recall.

The Gradient Boosting Classifier algorithm iteratively combines weak models to create a robust ensemble model. It effectively handles complex relationships between features, handles missing data, and automatically selects relevant features. Moreover, it minimizes bias and variance issues, providing better generalization and reducing the risk of overfitting.

Hence, based on our extensive evaluation and analysis, we have chosen the Gradient Boosting Classifier as the best model for predicting admission outcomes in this particular context.

Please refer to the documentation and source code for more details on data preprocessing, model training, hyperparameter tuning, and evaluation techniques employed in this project.


## Usage
To use the admission prediction model, follow these steps:

- Data Preparation: Prepare the input data in a suitable format, ensuring it contains the necessary features as mentioned above. It should be in a structured form, such as a CSV file or a database table.
- Model Training: Use the provided dataset to train the Gradient Boost Classifier model. This involves splitting the dataset into training and validation subsets, fitting the model to the training data, and tuning hyperparameters to optimize performance.
- Model Evaluation: Evaluate the trained model using appropriate evaluation metrics, such as accuracy, precision, recall, or area under the Receiver Operating Characteristic (ROC) curve. This step helps assess the model's performance and determine if any adjustments are necessary.
- Prediction: Once the model is trained and evaluated, it is ready to make predictions on new, unseen data. Prepare a separate dataset containing the same features as mentioned above for the applicants you wish to predict admission outcomes for. Pass this dataset through the trained model to obtain the predicted probabilities of admission for each applicant.
- Interpreting Results: Analyze the predicted probabilities of admission to make decisions or take further actions. You can set a threshold value to classify applicants as admitted or not admitted based on their predicted probabilities.

## Requirements
run this project, you need the following dependencies:
Python (version 3.6 or later)
NumPy
Pandas
scikit-learn
Ensure that these dependencies are installed in your environment before running the code.

## Summary
The admission prediction system utilizing the Gradient Boost Classifier provides an accurate and reliable means of assessing the chances of admission for prospective applicants. By leveraging historical applicant data and key features, the model offers valuable insights that can assist educational institutions and organizations in the decision-making process.



## AUTHOR
👤 **Nwaigbo Olive**
- Github:  [@olivenwaigbo](https://github.com/Olivenwaigbo?tab=following)    

- LinkedIn:  [olive nwaigbo](https://www.linkedin.com/in/olive-nwaigbo-95707a151)

## 🤝**Contributing**
Contributions to this project are welcome. If you find any issues or have ideas for improvements, please open an issue or submit a pull request. We appreciate your feedback and collaboration.


## **Show your support**
Give a ⭐️ if you like this project

## **Acknowledgements**
- Thank you Data Thinkers  for guiding me through this project.
## 📝 License 
This project is [MIT](./MIT.md) licensed

