# Customer Churn Prediction - Interconnect / Predicción de cancelación de clientes - Interconnect

## Project Description / Descripción del proyecto

This project develops a machine learning model to predict customer churn for Interconnect, a telecommunications company. The goal is to identify customers who are likely to cancel their service so the company can take preventive actions and improve customer retention.

Este proyecto desarrolla un modelo de machine learning para predecir la cancelación de clientes de Interconnect, una empresa de telecomunicaciones. El objetivo es identificar clientes con alta probabilidad de cancelar el servicio para que la empresa pueda tomar acciones preventivas y mejorar la retención.

## Project Scope / Alcance del proyecto

This repository contains the final modeling notebook, which consolidates the main technical work of the project: data preprocessing, exploratory analysis, model training, evaluation and final model selection.

Este repositorio contiene el notebook final de modelado, que consolida el trabajo técnico principal del proyecto: preprocesamiento de datos, análisis exploratorio, entrenamiento de modelos, evaluación y selección del modelo final.

## Objective / Objetivo

Build and evaluate classification models to predict whether a customer is likely to churn, using historical customer information, service usage and contract data.

Construir y evaluar modelos de clasificación para predecir si un cliente tiene probabilidad de cancelar el servicio, utilizando información histórica del cliente, uso de servicios y datos contractuales.

## Technologies Used / Tecnologías utilizadas

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Jupyter Notebook

## Process / Proceso realizado

- Data loading and initial exploration.
- Data cleaning and preprocessing.
- Integration of customer, contract, internet and phone service information.
- Exploratory data analysis.
- Feature engineering.
- Encoding of categorical variables.
- Train-test split.
- Training and comparison of classification models.
- Model evaluation using AUC-ROC and accuracy.
- Hyperparameter tuning with GridSearchCV.

---

- Carga y exploración inicial de datos.
- Limpieza y preprocesamiento de datos.
- Integración de información de clientes, contratos, internet y servicios telefónicos.
- Análisis exploratorio de datos.
- Ingeniería de características.
- Codificación de variables categóricas.
- División de datos en entrenamiento y prueba.
- Entrenamiento y comparación de modelos de clasificación.
- Evaluación del modelo mediante AUC-ROC y accuracy.
- Ajuste de hiperparámetros con GridSearchCV.

## Models Evaluated / Modelos evaluados

- Logistic Regression
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Decision Tree

---

- Regresión Logística
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Árbol de Decisión

## Main Results / Principales resultados

Gradient Boosting achieved the best overall performance among the evaluated models, with an AUC-ROC close to 0.84 before optimization. After hyperparameter tuning with GridSearchCV, the final model reached an AUC-ROC close to 0.88 on the test set.

Gradient Boosting obtuvo el mejor desempeño general entre los modelos evaluados, con un AUC-ROC cercano a 0.84 antes de la optimización. Después del ajuste de hiperparámetros con GridSearchCV, el modelo final alcanzó un AUC-ROC cercano a 0.88 en el conjunto de prueba.

## Main File / Archivo principal

The full analysis is available in the notebook:

`customer_churn_prediction_interconnect.ipynb`

El análisis completo se encuentra en el notebook:

`customer_churn_prediction_interconnect.ipynb`

## Dataset / Conjunto de datos

The dataset was provided as part of the TripleTen Data Science bootcamp for academic purposes.

El conjunto de datos fue proporcionado como parte del bootcamp de Data Science de TripleTen con fines académicos.
