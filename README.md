# Europe 2015 Enterprise Survivability

## Description

This is an academic project, developed as a Master Degree in Data Science at Insper University Brazil. The challenge consisted of building a complete data pipeline and developing classification models capable of predicting whether a European company would cease operations within two years from the collected data.

The work integrated the knowledge from Python and Statistical Machine Learning, using a real dataset of companies operating between 2005 and 2016.

## Objective

Create, test, and evaluate predictive models based on financial and operational data. It's a real-world application of Data Science in a business context.

## Project Pipeline
- **Preprocessing in Python:**
  - Data cleaning and removal of columns with a high percentage of missing values
  - Creation of new variables (e.g., company age, sales transformation)
  - Adjustments to variables with inconsistencies (e.g., negative sales)
  - Definition of the target variable based on future operation
  - Filtering of companies with revenue between 1,000 and 10 million euros

- **Modeling in R:**
  -  Building and evaluating predictive models:
    - Logistic Regression
    - Decision Tree
    - Random Forest
    - XGBoost
  - Evaluation using metrics:
    - Accuracy
    - AUC
    - Sensitivity and Specificity
  - Model interpretation with:
    - VIP (Variable Importance Plot)
    - PDP (Partial Dependence Plot)

## Results
The final model showed excellent predictive performance, with sales variables, company age, and capital structure standing out. The project received a top score from the evaluation panel.

## Repository Structure

```
├── data/                          # Base de dados utilizada
├── notebook/                      # Notebook de pré-processamento em Python
│   └── atividade_integradora_01_grupo02_v6.ipynb
├── modelagem/                     # Relatório de modelagem e scripts em R
├── imagens/                       # Gráficos e visualizações
├── README.md                      # Arquivo de descrição do projeto
```

## Requirements:

### Python
- pandas
- numpy
- matplotlib
- seaborn
- missingno

### R
- glmnet
- rpart
- ranger
- xgboost
- vip
- pdp
- DALEX
- caret

## Authors
Para mais informações, entre em contato com [Seu Nome] via LinkedIn ou GitHub.
