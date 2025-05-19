# HR Analytics - Predict Employee Attrition

## Overview

This project aims to analyze employee attrition within an organization to understand the primary contributing factors and build a predictive model for future attrition. By leveraging data analytics and machine learning techniques, the goal is to provide actionable insights for HR to proactively address employee retention.

## Objective

* Use analytics to understand the main causes of employee resignation.
* Predict future employee attrition.

## Tools Used

* **Python:**
    * **Pandas:** For data manipulation and analysis.
    * **Seaborn:** For statistical data visualization.
    * **Scikit-learn (Sklearn):** For building and evaluating the classification model (Logistic Regression).
    * **Reportlab:** For generating the PDF report.
* **Power BI:** For creating interactive data visualizations and a dashboard to explore attrition factors.
* **GitHub:** For version control and project collaboration.

## Project Workflow

1.  **Data Loading and Initial Exploration:**
    * Loaded the HR dataset using Pandas.
    * Performed initial data inspection, including checking data types, identifying missing values, and understanding the distribution of key features.

2.  **Exploratory Data Analysis (EDA):**
    * Investigated the distribution of the target variable ('Attrition').
    * Handled missing values using appropriate strategies.
    * Performed data preprocessing steps necessary for model building.

3.  **Data Preprocessing:**
    * Encoded categorical features using techniques suitable for the chosen model.
    * Scaled numerical features to ensure they have a similar range.
    * Split the data into training and testing sets to evaluate model performance.

4.  **Model Building:**
    * Built a classification model using Logistic Regression from Sklearn to predict employee attrition.
    * Trained the model on the training data.

5.  **Model Evaluation:**
    * Evaluated the performance of the trained Logistic Regression model on the testing data.
    * Generated a classification report including precision, recall, F1-score, and accuracy.
    * Created a confusion matrix to visualize the model's predictions.

6.  **Power BI Dashboard (Assuming Completed):**
    * Connected the HR data to Power BI.
    * Created an interactive dashboard with the following key visualizations (this list assumes you have completed these):
        * **Attrition Rate by Department:** A visual (e.g., bar chart or pie chart) showing the percentage or count of attrition in each department. This helps identify departments with higher turnover.
        * **Attrition by Salary Bands:** A visual (e.g., histogram or box plot) illustrating the distribution of attrition across different salary ranges, potentially highlighting if lower or higher salary bands experience more attrition.
        * **Impact of Promotions on Attrition:** A visual (e.g., stacked bar chart) showing the attrition rate for employees who have and have not received promotions, potentially indicating if a lack of promotion opportunities contributes to attrition.
        * **Attrition by Years in Current Role:** A visual (e.g., line chart or bar chart) showing attrition trends based on the number of years employees have been in their current role. This can help identify if attrition is higher at certain tenure milestones.
        * **Attrition by Other Relevant Factors:** Visualizations exploring the relationship between attrition and other significant features identified during EDA or feature importance analysis (e.g., job satisfaction, work-life balance, distance from home).
        * **Overall Attrition Rate:** A key metric displayed prominently on the dashboard, showing the overall percentage of employees who have left the company.
        * **Interactive Filters:** The dashboard includes filters allowing users to drill down into specific departments, job roles, or other relevant categories to explore attrition patterns in more detail.

7.  **SHAP Value Analysis (Attempted with Errors):**
    * Attempted to perform SHAP (SHapley Additive exPlanations) value analysis to understand the contribution of individual features to the model's predictions for specific employees.
    * Encountered technical errors during the implementation of SHAP analysis that prevented its successful completion within the scope of this project. This limitation will be acknowledged in the final report.

8.  **Attrition Prevention Suggestions:**
    * Generated a PDF report outlining actionable strategies for HR to proactively address employee attrition based on common HR best practices and potential insights from the analysis.

## Deliverables

* **Power BI Dashboard:** An interactive dashboard visualizing key attrition factors (as described above).
* **Model Accuracy Report + Confusion Matrix:** A report (likely within the notebook or a separate document) detailing the performance metrics of the Logistic Regression model, including accuracy, precision, recall, F1-score, and the confusion matrix.
* **PDF of Attrition Prevention Suggestions:** A document containing actionable recommendations for reducing employee turnover.

## Next Steps (If Applicable)

* Further refine the classification model by exploring other algorithms or hyperparameter tuning.
* Investigate and resolve the errors encountered during the SHAP value analysis for deeper model interpretability.
* Gather more data or features that could provide additional insights into attrition drivers.
* Develop a proactive intervention system based on the attrition prediction model.

## Repository Contents

* `notebooks/`: Contains the Jupyter/Colab notebooks with the Python code for data analysis, model building, and evaluation.
* `reports/`: May contain the model accuracy report and the PDF of attrition prevention suggestions.
* `data/`: Contains the HR dataset used for the analysis.
* `power_bi/`: (If applicable) May contain the Power BI file (.pbix) for the attrition dashboard.
* `README.md`: This file, providing an overview of the project.

## Author

* [RAVULA MANOJ KUMAR]
