
# Advertising Budget Optimization

## 📌 Overview

This project focuses on **Optimizing Advertising Budget Allocation** across multiple marketing channels using **Machine Learning and Data Analytics**. The goal is to **maximize ROI, improve conversions, and minimize unnecessary spending** by modeling the relationship between ad budget and performance metrics.

---

## 🎯 Objectives

* Identify which marketing channels influence sales the most.
* Build a predictive model to analyze the impact of budget allocation.
* Recommend optimal budget distribution for maximum ROI.
* Provide visual insights and performance analytics.

---

## 🚀 Features

* **Data Preprocessing**: Cleans and transforms raw advertising datasets.
* **Exploratory Data Analysis (EDA)**: Visualizes relationships between TV, Radio, Newspaper budgets and Sales.
* **Machine Learning Model**: Linear Regression / Multiple Regression to predict sales.
* **Feature Importance Analysis**: Determines which channels drive maximum revenue.
* **Budget Optimization**: Suggests ideal spending distribution.
* **Graphical Results**: Scatter plots, regression lines, correlation heatmaps.

---

## 🛠️ Tech Stack

### **Languages & Libraries**

* Python
* NumPy
* Pandas
* Matplotlib / Plotly
* Scikit-learn
* Jupyter Notebook

---

## 📂 Folder Structure

```
├── data
│   └── advertising.csv
├── notebooks
│   └── Advertising_Budget_Optimization.ipynb
├── src
│   ├── preprocessing.py
│   ├── model.py
│   └── optimization.py
├── README.md
└── requirements.txt
```

---

## 📊 Workflow

1. **Load Dataset** – Import advertising dataset containing TV, Radio, Newspaper spend & Sales.
2. **Preprocess Data** – Handle missing values, normalization, encoding if needed.
3. **EDA** – Visualize feature relationships and distribution.
4. **Model Building** – Train regression model to predict sales.
5. **Model Evaluation** – Check RMSE, R² Score, Residual Plots.
6. **Optimization Logic** – Use the model to determine budget combination that maximizes predicted sales.

---

## 🔍 Example Insights

* TV advertising usually shows the highest correlation with sales.
* Radio may have moderate influence.
* Newspaper often contributes least and may yield poor ROI.
* Balanced budget reallocations can significantly improve performance.

---

## ⚙️ How to Run

### **1. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **2. Open Jupyter Notebook**

```bash
jupyter notebook
```

Navigate to: `Advertising_Budget_Optimization.ipynb`.

### **3. Run All Cells**

You will see:

* Data insights
* Regression analysis
* Optimization recommendations
* Visual graphs

---

## 🧪 Model Used

### **Multiple Linear Regression**

Formula:

```
Sales = b0 + b1*TV + b2*Radio + b3*Newspaper
```

Where:

* **TV, Radio, Newspaper** → Ad budgets
* **Sales** → Target variable

Can be extended to:

* Polynomial models
* Ridge/Lasso Regression
* Random Forest Regression

---

## 🧮 Budget Optimization Approach

1. Train model on historical data.
2. Use predicted sales function.
3. Run optimization using:

   * Grid Search
   * Gradient-based optimization
   * Simplemax constraints
4. Output recommended budget distribution.

Example Output:

```
Recommended Budget Split:
TV – 60%
Radio – 30%
Newspaper – 10%
```

---

## 📈 Visualizations

* Correlation Heatmap
* Scatterplots for each feature vs Sales
* Regression Fit Lines
* Actual vs Predicted Sales
* Error/Residual Plot

---

## 📘 Use Cases

* Marketing campaign planning
* Performance analytics
* ROI forecasting
* Real-time budget adjustment systems

---

## 🛡️ Benefits

* Cost savings
* Better marketing performance
* Data-driven decision making
* Continuous optimization possible

