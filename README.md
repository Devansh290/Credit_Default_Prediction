# Credit Default Prediction using SAS Enterprise Miner

This project focuses on predicting credit card default risk using SAS Enterprise Miner (E-miner). It involves both supervised (classification, regression, neural networks) and unsupervised (clustering) learning methods, with a dataset based on customer demographics, repayment history, and credit behavior.

## 🧰 Tools Used
- SAS Enterprise Miner (E-miner)
- Credit Default Dataset 

## 📊 Key Analytical Steps

### 📌 Data Exploration
- Explored credit limits across age groups using boxplots
- Analyzed repayment status by education using bar charts
- Assessed class and interval variables via StatExplore

### 🌲 Decision Tree Modeling
- Used PAY_0 to PAY_6 as inputs
- Found optimal tree depth to prevent overfitting
- Analyzed variable importance (PAY_0 strongest predictor)

### 📈 Regression Modeling
- Linear Regression to predict credit limit (LIMIT_BAL)
- Logistic Regression to classify defaulters
- Evaluated using misclassification rate and lift charts

### 🧠 Neural Network Modeling
- Achieved lowest ASE (0.1357) and RMSE (0.37)
- Examined weight influence on hidden layers
- Analyzed gain/lift and posterior probability ranges

### 🤖 Ensemble Modeling
- Combined Decision Tree, Regression, and Neural Network
- Achieved strong performance across all metrics
- Best generalization across validation/test sets

### 🔍 Unsupervised Clustering
- Grouped customers by billing/payment behavior
- Explored input means, segment sizes, and CCC plot
- Identified distinct behavioral segments for targeted risk management

## 📌 Insights
- **PAY_0** is the most critical predictor across all models
- Neural networks outperform other individual models
- Ensemble model offers robust, stable performance
- Clustering reveals distinct customer profiles

## 📁 Files
- `SAS_Eminer_Project_Report.docx`: Contains detailed step-by-step analysis, interpretations, and results.

## 📝 Note
SAS E-miner project files were lost due to a system change. This report reconstructs and documents the complete project pipeline and results based on detailed analysis performed earlier.

