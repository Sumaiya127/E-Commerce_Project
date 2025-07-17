# E-Commerce_Project
A machine learning based project aimed at classifying E-Commerce customers into segments using Python, Feature Engineering, Multiple Model Evaluations, and Tableau for Visual Insights.

# E-Commerce Customer Segmentation Project

## 📌 OBJECTIVE

To Develop a predictive model to classify customer segments based on e-commerce related features. The goal is to help businesses personalize marketing, improve retention, and optimize resource allocation using data-driven customer insights.

---

## 📊 TOOLS AND TECHNOLOGIES USED

- Python(Jupyter Notebook) :For Data Cleaning, EDA, Feature Engineering, Dimensionality Reduction, and Model Building.
- Libraries: Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, Xgboost, etc.
- Tableau :For interactive Dashboards and Visualization.
- Machine Learning Models :Logistic Regression, Random Forest, XGBoost, Gradient Boosting, SVM.

---

## 📁 PROJECT WORKFLOW

### 1.Data Preprocessing
- Checked for missing/duplicate values
- Converted Categorical variables using One-hot Encoding
- Removed irrelevant columns like Customer_ID, Customer_Name

### 2.Exploratory Data Analysis(EDA)
- Univariate & Bivariate analysis
- Feature distribution visualization
- Statistical testing (ANOVA, chi-square tests)
- Insights into customer behavior, income, and spending patterns

### 3.Feature Engineering
- Created derived features like:
  - Income_Spending_Interaction
  - Spending_Efficiency
  - Orders_Per_Year
  - Order_Value_Frequency

### 4.Feature Selection
Used multiple methods:
- Univariate (SelectKBest)
- Recursive Feature Elimination (RFE)
- Random Forest Importance
- Correlation-based filtering
- Combined feature sets

### 5.Model Building
- Tested classifiers: Logistic Regression, Random Forest, SVM, XGBoost, Gradient Boosting
- Evaluated with and without PCA
- Accuracy remained around ~33% for all models

### 6.Visualization
- Created Tableau dashboards to visualize:
  - Segment-wise distribution
  - Key influencing features
  - Customer profiling by behavior & demographics

---

## 📌 KEY TAKEAWAYS

- Despite extensive feature engineering and model testing, predictive accuracy was limited (~33%)
- Possible reasons include:
  - Weak correlation of features with Target variable
  - Model Complexity vs Dataset Simplicity
  - Class overlaps
- Demonstrates a complete end-to-end ML pipeline and strong data exploration

---

## 📂 PROJECT FILES

- CAPSTONE_PROJECT_REPORT.pdf: Detailed documentation of project steps, analysis, and results
- Notebooks: Python scripts or notebooks
- Visuals: Tableau screenshots or dashboard links

---

## ✨ AUTHOR

 - SUMAIYA IRSHAD

---

## 📫 Contact

If you'd like to connect or have questions, feel free to reach out on GitHub or LinkedIn.




