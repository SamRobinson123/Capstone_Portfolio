# Capstone Portfolio

This portfolio highlights the Data Science Capstone project, focusing on leveraging advanced data analysis and machine learning techniques to solve a specific challenge. Click the link below to view the code on my personal GitHub page.

## [Group6Capstone: Project Overview](https://github.com/SamRobinson123/Group6Capstone/blob/main/Group6Capstone.ipynb)
![Project Status](https://img.shields.io/badge/status-complete-green.svg)

### Business Problem
The **Group6Capstone** project addresses a significant operational challenge for Swire Coca-Cola, which experiences an annual loss of approximately $60 million due to machine downtime. Workers are currently deployed reactively to fix broken machines, resulting in delays and productivity losses. This project focuses on building a predictive model to identify machines at high risk of failure, enabling proactive interventions and reducing downtime.

### 🎯 Objective
The primary goal of this project was to:
- Develop a **survivor model** to predict time-to-failure for machines based on historical maintenance data and operational logs.
- Leverage exploratory data analysis (EDA) to refine the dataset and uncover critical patterns influencing downtime.
- Implement predictive modeling techniques to identify high-risk machines and enable proactive maintenance.

### 📊 Project Details
- **Dataset**: The dataset included operational logs, maintenance histories, and machine identifiers. Due to a high proportion of missing data (80% null values), the focus was on a subset where at least 20% of values were present to construct reliable models.
- **Data Cleaning and Feature Engineering**:
  - Created key metrics, such as "Time to Failure" and "Days Since Planned Maintenance," which served as critical inputs to the survivor model.
  - Standardized and split complex columns, like `FUNCTIONAL_LOC`, for improved modeling and interpretability.
  - Calculated maintenance frequency and part replacement rates to enhance feature robustness.

- **Modeling**:
  - Built a **survivor model** using Cox Proportional Hazards regression to estimate the hazard rate of machine failure over time.
  - Achieved the following performance metrics:
    - **Concordance Index (C-Index)**:
      - Model 1: **0.7783**
      - Model 2: **0.7552**
  - Validated the models using time-based cross-validation to ensure temporal robustness.

### 🚀 Personal Contribution
As a member of the **Group6Capstone** team, I contributed significantly to the project through the following efforts:

1. **Feature Engineering and EDA**:
   - Developed survival-related features, such as "Time to Failure," which was calculated from unplanned maintenance logs.
   - Engineered machine-level attributes to represent historical maintenance schedules, part replacements, and operational time.

2. **Model Development**:
   - Designed and implemented the **Cox Proportional Hazards survivor model** to predict time-to-failure, focusing on hazard rates for each machine.

3. **Validation and Optimization**:
   - Assessed model performance using survival-specific metrics, such as Concordance Index, and refined features to improve predictions.

### 🚀 Value of the Solution
This project delivered actionable insights and predictions, enabling Swire Coca-Cola to:
- Prioritize maintenance for high-risk machines, reducing unexpected failures.
- Save significant operational costs by minimizing reactive maintenance.

### Key Metrics
- **Concordance Index (C-Index)**:
  - Model 1: **0.7783**
  - Model 2: **0.7552**

These metrics demonstrate the survivor model's capability to predict machine failures with precision and reliability.

### Challenges

The project faced several significant challenges, including:

1. **High Proportion of Missing Data**:
   - Over 80% of the dataset contained null values, requiring creative solutions, such as focusing on a 20% subset with viable data.

2. **Complex Target Definition**:
   - The target variable, "Time to Failure," had to be constructed from raw logs by calculating time intervals between unplanned maintenance events.

3. **Temporal Dependencies**:
   - Modeling time-to-failure introduced challenges related to event censoring, necessitating survival analysis techniques like the Cox model.

### Takeaways
Key learnings from this project include:
- The critical importance of survival analysis techniques for time-based prediction challenges.
- How data limitations influence modeling decisions and performance.
- The value of time-based validation to ensure the model's applicability to real-world scenarios.
