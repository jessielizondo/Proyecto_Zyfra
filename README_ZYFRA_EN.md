# 🟡 Gold Recovery Prediction - Zyfra Processing Plant
Regression modeling and industrial data analysis with Python

## 📌 Introduction
Zyfra, a mining industry company, aims to improve control and efficiency in its gold recovery process. This project uses sensor data to predict the effectiveness of intermediate and final gold recovery based on various technical parameters.

We focus on predicting:
- `rougher.output.recovery` (intermediate recovery)
- `final.output.recovery` (final gold recovery)

## 🎯 Business Problem
The extraction and purification process of gold is complex. Data-driven decisions can fine-tune process parameters, reduce losses, and enhance efficiency and profitability.

## 🔍 Project Objectives
✔ Clean and prepare industrial datasets  
✔ Validate the consistency of chemical-physical processes  
✔ Apply regression models to predict recovery  
✔ Evaluate model performance using sMAPE  
✔ Benchmark against a dummy (baseline) model  

## ❓ Key Questions
- Which variables most influence gold recovery?  
- Are there inconsistent or outlier values?  
- Which model provides the most accurate predictions?

## 📊 Key Metrics
- **sMAPE**: Symmetric Mean Absolute Percentage Error  
- Performance comparison for rougher and final stages  
- Cross-validation evaluation with error metrics

## 🗂 Dataset Overview
📁 Files:
- `gold_recovery_full.csv`: complete dataset
- `gold_recovery_train.csv`: training data
- `gold_recovery_test.csv`: test data

Key columns:
- Input variables: concentration, amount, particle size  
- Target variables: `rougher.output.recovery`, `final.output.recovery`

## ⚙️ Analysis Process
📌 Tools used: Python, Pandas, NumPy, Scikit-Learn, Matplotlib

### Step 1: Load & Clean
✔ Handle missing values  
✔ Align features between train/test  
✔ Format conversions

### Step 2: EDA & Consistency Check
✔ Chemical balance validation  
✔ Visualize distributions & correlations

### Step 3: Modeling
✔ Train RandomForestRegressor  
✔ Cross-validation using sMAPE  
✔ Compare with baseline model

## 📁 Repository Structure
📂 data  
 └── gold_recovery_full.csv  
 └── gold_recovery_train.csv  
 └── gold_recovery_test.csv  

📂 notebooks  
 └── Proyecto_Zyfra_FINAL.ipynb  

📂 insights  
 └── summary.md  

## 📬 Contact
📧 Email: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
