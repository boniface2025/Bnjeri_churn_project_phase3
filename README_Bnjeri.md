# Early Detection of Imminent SyriaTel Churn Through Predictive Signal Analysis

###  Author: Boniface Kimondo Njeri  
**Institution:** Moringa School  
**Course:** Data Science – Phase 3  
**Technical Mentor:** George Kamundia  

## Project Overview

This final project focuses on developing a machine learning-based predictive system to identify potential customer churn at SyriaTel a leading telecommunications provider. Customer churn, which refers to customers discontinuing their services, is a critical metric that directly affects the company's profitability and growth.

By leveraging historical customer usage data, service plans, and behavioral trends, this project aims to create a model that can proactively detect customers at risk of churning, allowing SyriaTel to take preemptive retention measures.

## Objectives

- Analyze customer behavior and service data to understand churn patterns.
- Perform in-depth exploratory data analysis (EDA) to uncover meaningful insights.
- Engineer and preprocess relevant features for modeling.
- Build and evaluate a robust machine learning classification model.
- Provide actionable business insights and recommendations for retention strategies.

## Dataset Description

The dataset includes information on customer call behavior, service plans and usage patterns. Key features include:

- **Account Length**
- **International Plan**
- **Voice Mail Plan**
- **Number of Customer Service Calls**
- **Day, Evening, Night, and International Call Minutes and Charges**
- **Churn (Target Variable)**

## Data Exploration & Insights

Using various visual and statistical techniques, the following patterns were observed:

- **Churn Distribution:** Approximately 14.5% of the customers had churned, indicating an imbalanced dataset.
- **Customer Service Calls:** Churn rate is significantly higher among customers who contacted customer service 4 or more times.
- **International Plan:** Customers subscribed to the international plan show a higher tendency to churn.
- **High Daytime Usage:** High daytime minutes and charges correlate with increased churn probability, potentially due to billing dissatisfaction.

## Data Preprocessing & Feature Engineering

- Categorical variables (e.g., 'international plan', 'voice mail plan') were encoded using Label Encoding.
- Data was split into training and test sets (70% training, 30% testing).
- Feature scaling was performed using StandardScaler to normalize numerical attributes.

## Model Development and Training

A **Random Forest Classifier** was chosen for its robustness and ability to handle both categorical and numerical data. Key steps included:

- Initializing the model with 100 decision trees.
- Training on the preprocessed dataset.
- Generating predictions on the test set.
- Evaluating model performance using classification metrics.

## Evaluation Metrics

The model's performance was evaluated using:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)

**Key Findings:**

- The model is highly accurate in identifying non-churners.
- It performs fairly well in detecting churners (Recall ~0.71).
- The F1-score provides a balanced evaluation, especially due to class imbalance.

## Key Business Insights

- **Frequent Support Calls = Risk:** Users contacting support multiple times are at a much higher risk of churning.
- **International Plan Under Scrutiny:** Customers on this plan have higher churn rates—possible dissatisfaction or cost concerns.
- **Heavy Users Are Vulnerable:** Contrary to expectation, high usage does not imply loyalty—these users might feel overcharged.

## Recommendations

- **Improve Customer Support Quality:** High support call frequency is a churn signal—consider addressing root causes.
- **Revise International Plan Strategy:** Reevaluate pricing or include better benefits to improve satisfaction.
- **Offer Loyalty Incentives:** Target heavy users with discounts or personalized offers to retain them.

*This project was completed as part of the Phase 3 Data Science curriculum at Moringa School.*

To access the github hosting the project work, click on the "Project Git Hub" hyperlink below.
[Project git hub](https://github.com/boniface2025/Bnjeri_churn_project_phase3.git)