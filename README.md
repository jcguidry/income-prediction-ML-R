# Customer Salary Prediction

This project is focused on predicting whether customers' salaries are above or below $50,000 based on various demographic and economic factors. It utilizes data analysis, preprocessing, and machine learning techniques to build and evaluate predictive models. The project was developed using R, and it covers the entire data science pipeline, from data exploration and preprocessing to model building and evaluation.

## Project Overview

### Data Source

The project uses a dataset containing information about customers, including features such as age, race, marital status, work class, occupation, hours worked per week, education, capital gain, and capital loss, among others. The target variable is "salary," which indicates whether a customer's salary is greater than $50,000 or not.

### Project Steps

1. **Data Exploration and Preprocessing**: The project begins by loading and exploring the dataset. It includes steps to handle missing values, outliers, and data transformations. Categorical variables are converted into factors, and feature engineering is performed to simplify some variables.

2. **Naïve Bayes Model**: A Naïve Bayes classification model is built using selected features from the dataset. The model's accuracy, true positive rate, false positive rate, specificity, precision, and prevalence are calculated and reported.

3. **Logistic Regression Model**: A logistic regression model is trained using the same set of features. The significant variables are identified, and the model's performance metrics are computed.

4. **Decision Tree (CART) Model**: A decision tree classification model (Classification and Regression Trees) is created to capture non-linear relationships in the data. The model is visualized, and its importance scores for each feature are calculated.

5. **Random Forest Model**: A random forest ensemble model is constructed, which combines multiple decision trees to improve predictive performance. The feature importance scores are reported, and model evaluation metrics are calculated.

6. **Model Comparison**: The project concludes by comparing the performance of all three models, including accuracy, true positive rate, false positive rate, specificity, precision, and prevalence. The results are presented in a tabular format.

## Project Files

- **Customer Salary Prediction.Rmd**: The R Markdown document containing the code for data preprocessing, model building, and evaluation.

- **data/adult_sampled.csv**: The preprocessed dataset used for model training and testing.

- **data/variable_importance.csv**: A CSV file containing feature importance scores from the decision tree and random forest models.

- **data/model_stats.csv**: A CSV file summarizing the performance metrics of all models.

## Model Performance

The project evaluates and compares the performance of four different models:

- Naïve Bayes
- Logistic Regression
- Decision Tree (CART)
- Random Forest

Model evaluation metrics, including accuracy, true positive rate, false positive rate, specificity, precision, and prevalence, are provided in the `model_stats.csv` file.

## How to Run the Code

To replicate the project's results and run the code, follow these steps:

1. Ensure you have R installed on your system.

2. Clone or download this repository to your local machine.

3. Open the "Customer Salary Prediction.Rmd" file using an R Markdown compatible IDE (e.g., RStudio).

4. Install the required R packages mentioned at the beginning of the document if you haven't already.

5. Run the code chunks in the document step by step, starting from data loading and preprocessing to model building and evaluation.

6. Review the model results and performance metrics in the output.

---

