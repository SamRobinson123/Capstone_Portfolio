# Capstone Portfolio

This portfolio highlights the Data Science Capstone project, focusing on the application of advanced machine learning techniques to address a critical challenge in the financial sector.

## [Home Credit: Project Overview](https://github.com/SamRobinson123/Capstone_Portfolio/blob/main/HomeCreditModel_Final.ipynb)
![Project Status](https://img.shields.io/badge/status-complete-green.svg)

### Business Problem
Home Credit Group is dedicated to expanding financial inclusion for the underbanked population, frequently excluded from traditional banking services due to a lack of credit history. By leveraging alternative data sources, such as telco and transactional information, Home Credit aims to more accurately predict their clients' ability to repay loans. Recognizing the need to enhance their predictive models, Home Credit has engaged the Kaggle community. The objective is to utilize data science techniques to improve the accuracy of loan repayment predictions, ensuring that eligible individuals have access to credit under fair terms. This initiative underscores Home Credit's commitment to promoting financial health and empowerment among traditionally underserved communities.

### Contribution
I am solely responsible for the entirety of the Jupyter notebook, receiving no assistance from Nick Sarka or McKay Flake. I personally handled all aspects of the project, including data cleaning, data frame joins, cross-validation, feature engineering, and finally, fitting and tuning the CatBoost model.

### 🎯 Objective
The primary goal was to develop a predictive model capable of assessing a customer's loan repayment abilities, thereby enhancing financial inclusion. This involved analyzing a substantial dataset to accurately predict loan repayment probabilities.

### 📊 Project Details
- **Dataset**: The project utilized a dataset with over 100,000 data points, providing a robust foundation for modeling customer behaviors.
- **Data Cleaning**: Implemented comprehensive data cleaning techniques to manage missing values, outliers, and incorrect entries, ensuring high data integrity.
- **Modeling**: Developed a CatBoost Model, chosen for its effectiveness with categorical data. Achievements include:
  - **AUC (Area Under the Curve)**: 0.77, demonstrating strong predictive capabilities.
  - **Accuracy**: 92%, highlighting the model's effectiveness in real-world scenarios.

### 🚀 Value of the Solution
The model showcased notable efficacy, achieving an average AUC score of 0.7705 and an average accuracy rate of 91.98% across the folds. These results underline the model’s substantial ability to differentiate between those who are likely to fulfill their loan obligations and those who are not. An AUC score close to 0.77 indicates strong discriminative power, enhancing the model's utility in making informed lending decisions. This endeavor not only aligns with Home Credit's aim to promote financial inclusion by enabling access to credit for traditionally marginalized groups but also exemplifies the impactful use of data science in fostering equitable financial services. Through such predictive modeling efforts, Home Credit is paving the way for more inclusive lending practices, ensuring that creditworthiness is assessed accurately and fairly, based on a person's true potential to repay.

### Challenges
The most significant challenge was being the only group member to build a model. However, every other part of the project was viewed more as a learning experience and an opportunity for growth rather than a challenge.

### Takeaways
Key takeaways from this project include the importance of proper preprocessing techniques. I learned more about using classes or functions to more efficiently preprocess the train and test datasets as well as to reduce manual errors.

### 📈 Exploratory Data Analysis (EDA) Examples
These visualizations illustrate key insights from the data exploration phase and underscore the model's decision-making framework.

#### Feature Importance
![Feature Rank](https://raw.githubusercontent.com/SamRobinson123/Capstone_Portfolio/main/images/Capture.JPG "Feature Rank")

#### Default Rate by Education
![Default Rate by Education](https://raw.githubusercontent.com/SamRobinson123/Capstone_Portfolio/main/images/deafult%20rate%20by%20education.JPG "Default Rate by Education")

#### Default Rate by Family Status
![Default Rate by Family Status](https://raw.githubusercontent.com/SamRobinson123/Capstone_Portfolio/main/images/default%20rate%20by%20family%20status.JPG "Default Rate by Family Status")

---

### 📝 Additional Resources
For more detailed analysis and code, please refer to the notebooks and scripts within this repository.

---
