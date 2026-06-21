# Simple Linear Regression – Marketing ROI Analysis

## Project Overview
This project performs a **Simple Linear Regression** analysis on marketing data to evaluate the return on investment (ROI) of different advertising channels (TV, Radio, and Social Media) on Sales. 

The analysis includes:
- Data loading and cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Identification of the best predictor variable
- Building an OLS regression model using `statsmodels`
- Checking regression assumptions (Linearity, Normality, Homoscedasticity)
- Statistical interpretation and business recommendations

**Goal**: Recommend the marketing channel with the strongest ROI impact for budget allocation.

---

## Dataset
- **File**: `marketing_and_sales_data_evaluate_lr.csv`
- Contains marketing spend across TV, Radio, Social Media, and corresponding Sales figures.

---

## Environment Setup

### Prerequisites
- Python 3.8+
- Google Colab (recommended) or Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
