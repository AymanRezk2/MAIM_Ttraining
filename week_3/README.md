# Telco Customer Churn Analysis

## Dataset

This project uses the **Telco Customer Churn** dataset from [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn), which contains demographic, usage, and churn information of customers for a telecommunications company.

## Objective

The goal is to analyze the customer data using both unsupervised and supervised machine learning techniques to:

- Identify meaningful customer segments via clustering (K-Means).
- Predict customer churn using classification models.
- Extract insights supported by clear data storytelling and visualizations.

## Project Structure

- **Data Cleaning:** Handling missing values, encoding categorical variables, and preparing data for modeling.
- **Unsupervised Learning:** Clustering customers based on selected features (e.g., tenure, monthly charges, contract type) and interpreting cluster characteristics.
- **Supervised Learning:** Training classification models (Logistic Regression, Random Forest) to predict churn and evaluating their performance using accuracy, precision, recall, and F1-score.
- **Visualizations:** Exploring key feature distributions, churn rates per cluster, and important factors influencing churn.
- **Storytelling:** A narrative summarizing key findings and actionable insights.

## How to Run the Notebook

1. Ensure you have Python 3.x installed with necessary packages:
    ```bash
    pip install -r requirements.txt
    ```
    *(You may create a `requirements.txt` containing packages like pandas, numpy, scikit-learn, matplotlib, seaborn, etc.)*

2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook assignment.ipynb
    ```

3. Execute the notebook cells sequentially.

## Deliverables

- `assignment.ipynb`: Jupyter Notebook containing data cleaning, clustering, supervised learning, and visualization.
- `README.md`: This file.
- *(Optional)* `summary.pdf`: A brief report summarizing findings and recommendations.

## Key Insights (Summary)

- Customer segments differ notably in contract types, tenure, and monthly charges.
- Customers with shorter tenure and month-to-month contracts have higher churn rates.
- Models such as Random Forest provide good accuracy in predicting churn.
- The insights support targeted retention strategies for different customer groups.

---

Feel free to contact me for any questions or further collaboration!
