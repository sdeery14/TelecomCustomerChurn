# Predictive Analysis of Customer Churn in the Telecom Sector

The full paper is in the Deery_FinalProject.docx file.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Results](#results)
- [License](#license)

## Introduction
Customer churn, where customers switch from one service provider to another, poses a significant challenge for telecommunications companies. This project leverages data science methodologies to analyze customer data, understand the underlying factors of churn, and develop predictive models to forecast potential churn. This enables telecom companies to implement targeted retention strategies and enhance customer loyalty.

## Data
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics/data). It contains 7043 rows and 38 columns, each representing a customer from a telecommunications company in California in Q2 2022. Key features include demographic information, service usage, and customer status (churn, stay, join).

## Data Cleaning
Data cleaning involved:
- Removing irrelevant columns like Customer ID.
- Converting zip codes to strings and handling leading zeros.
- Addressing missing values by assigning default values based on logical assumptions.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was conducted to uncover relationships between customer attributes and their churn status. Key findings include:
- **Customer Status:** Approximately 26.5% of customers churned in Q2.
- **Churn Category:** Most churn is due to competitors, followed by dissatisfaction and service issues.
- **Location and Demographics:** Analyzed the impact of geographic location and demographic factors on churn.
- **Service Usage:** Explored how different service subscriptions and usage patterns relate to churn.

## Modeling
Three machine learning models were used to predict customer churn:
1. **Logistic Regression:** Simple and interpretable, providing probabilities for churn.
2. **Random Forest Classifier:** Captures complex relationships and provides feature importance.
3. **Support Vector Machine (SVM):** Finds the optimal hyperplane for classification, handling high-dimensional data well.

Models were evaluated using accuracy metrics and confusion matrices to understand their performance.

## Conclusion
The analysis revealed that service quality and financial considerations are critical factors influencing customer churn. By adopting competitive pricing, enhancing service delivery, and fostering long-term customer relationships, telecom companies can significantly reduce churn rates.

## How to Use
To replicate this project, follow these steps:
1. Clone the repository to Google Drive: `git clone https://github.com/sdeery14/telecom-churn-analysis.git`
2. Open the files 'Deery_EDA.ipynb' and 'Deery_Modeling.ipynb' in Google Colab.
3. Run the notebooks to see the analysis and modeling in action.

## Results
The best-performing models were Random Forest and SVM, both achieving an accuracy of 84.6%. The choice of model may depend on whether the goal is to maximize overall accuracy or to correctly identify customers likely to churn.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

