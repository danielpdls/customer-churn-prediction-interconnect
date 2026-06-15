# Customer Churn Prediction — Interconnect

Machine learning project focused on predicting customer churn for **Interconnect**, a telecommunications company.

The goal of this project is to identify customers with a higher probability of canceling their service, allowing the business to support retention strategies through data-driven insights.

---

## Project overview

Customer churn is a key business problem for subscription-based companies. When customers leave, companies lose recurring revenue and often need to spend more on acquisition to replace them.

This project uses historical customer, contract, internet, and phone service data to build and evaluate classification models that estimate whether a customer is likely to churn.

The final model can help prioritize customers for preventive retention actions.

---

## Business problem

Interconnect wants to reduce customer churn by identifying users who are at risk of canceling their service.

The main analytical question is:

> Can customer information, contract details, and service usage data be used to predict whether a customer is likely to churn?

This type of analysis can support business teams by helping them:

* Detect customers with higher churn risk.
* Prioritize retention campaigns.
* Understand which features are associated with churn.
* Improve decision-making based on predictive metrics.

---

## Data

The dataset includes information related to:

* Customer profile.
* Contract type and billing information.
* Internet service.
* Phone service.
* Churn status.

The data was provided as part of the TripleTen Data Science bootcamp for academic purposes.

---

## Tools and technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project workflow

The project followed a complete machine learning workflow:

1. Data loading and initial exploration.
2. Data cleaning and preprocessing.
3. Integration of customer, contract, internet, and phone service tables.
4. Exploratory data analysis.
5. Feature engineering.
6. Encoding of categorical variables.
7. Train-test split.
8. Model training and comparison.
9. Evaluation using AUC-ROC and accuracy.
10. Hyperparameter tuning with GridSearchCV.
11. Final model selection.

---

## Models evaluated

The following classification models were tested:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors
* Gradient Boosting

---

## Evaluation strategy

The main evaluation metric was **AUC-ROC**, because the goal was to measure the model's ability to distinguish between customers who churn and customers who remain active.

Accuracy was also reviewed as a complementary metric, but AUC-ROC was prioritized due to the classification nature of the business problem.

---

## Main results

Gradient Boosting achieved the best overall performance among the evaluated models.

* Best model before optimization: **Gradient Boosting**
* AUC-ROC before optimization: approximately **0.84**
* Final model after GridSearchCV tuning: **Gradient Boosting**
* Final AUC-ROC on the test set: approximately **0.88**

These results suggest that the model was able to capture relevant patterns associated with customer churn and can be used as a basis for customer retention analysis.

---

## Skills demonstrated

* Data preprocessing and cleaning.
* Integration of multiple datasets.
* Exploratory data analysis.
* Feature engineering.
* Encoding categorical variables.
* Supervised machine learning for classification.
* Model comparison and evaluation.
* Hyperparameter tuning with GridSearchCV.
* Interpretation of performance metrics.
* Business-oriented communication of model results.

---

## Main file

The full analysis is available in the notebook:

```text
customer_churn_prediction_interconnect.ipynb
```

---

## How to run

1. Clone this repository:

```bash
git clone https://github.com/danielpdls/customer-churn-prediction-interconnect.git
```

2. Navigate to the project folder:

```bash
cd customer-churn-prediction-interconnect
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook customer_churn_prediction_interconnect.ipynb
```

5. Run the notebook cells.

---

## Methodological note

This project was developed for academic and portfolio purposes. The model results depend on the available dataset, preprocessing decisions, selected features, and evaluation strategy.

In a production environment, the next steps would include additional validation, monitoring model performance over time, analyzing business costs of false positives and false negatives, and working with business teams to define retention actions.

---

## Author

**Daniel Puente de los Santos**

Data Analyst focused on business, operations, and data-driven decision-making.

* GitHub: [github.com/danielpdls](https://github.com/danielpdls)
* LinkedIn: [linkedin.com/in/danielpdls](https://www.linkedin.com/in/danielpdls)
