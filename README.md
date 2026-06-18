📊 Marketing ROI – Simple Linear Regression Analysis
📌 Project Overview

This project applies Simple Linear Regression using Python (statsmodels) to analyze the relationship between marketing channels (TV, Radio, Social Media) and Sales performance.

The goal is to identify which marketing channel delivers the highest Return on Investment (ROI) and provide data-driven recommendations for budget allocation.

📁 Dataset
File: marketing_and_sales_data_evaluate_lr.csv
Source: Provided project dataset (included in repository)

The dataset contains marketing expenditure across different channels and corresponding sales outcomes.

🛠️ Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Statsmodels
📊 Project Workflow
1. Data Loading & Cleaning
Loaded dataset using pandas
Checked for missing values
Removed null entries for clean analysis
2. Exploratory Data Analysis (EDA)
Summary statistics computed
Pairwise relationships visualized
Correlation heatmap generated to understand relationships
3. Feature Selection
Correlation analysis performed
The most strongly correlated variable with Sales was selected (e.g., TV)
4. Model Building
Built Simple Linear Regression model using OLS (Ordinary Least Squares)
Model fitted using statsmodels
5. Model Evaluation
R-squared used to measure model performance
Coefficients interpreted for business impact
p-values used to test statistical significance
6. Diagnostic Checks
Linearity checked using regression plot
Residual analysis performed
Normality tested using histogram and Q-Q plot
Homoscedasticity assessed using residual vs fitted plot
📈 Key Results (Example Format)

(Replace with your actual outputs after running the notebook)

Best Predictor: TV Advertising
R-squared: 0.xx
Coefficient: 0.xx
P-value: < 0.05 (statistically significant)
💡 Business Insights
TV advertising shows the strongest positive impact on Sales.
Increasing investment in TV marketing is likely to improve revenue.
Other channels (Radio/Social Media) show weaker predictive power compared to TV.
The model explains a meaningful portion of sales variation, supporting data-driven decision-making.
📌 Recommendation
Increase budget allocation to high-impact channel (TV advertising).
Optimize or re-evaluate lower-performing channels.
Use regression insights to guide future marketing strategy.
📂 Repository Structure
📁 project-folder
 ┣ 📄 regression_analysis.ipynb
 ┣ 📄 marketing_and_sales_data_evaluate_lr.csv
 ┣ 📄 README.md
⚠️ Notes
Ensure the notebook is fully executed before submission.
All plots and regression outputs must be visible.
Dataset must be included in the repository for verification.
🚀 Author

Data Science / Machine Learning Project – Marketing ROI Analysis
