#  Energy Consumption Prediction Using Machine Learning

##  Project Overview
This project predicts **per capita electricity consumption** for selected countries using socio-economic and energy indicators.

The goal is to demonstrate an end-to-end Machine Learning workflow including:
- Data cleaning
- Feature selection
- Model training
- Model comparison
- Performance evaluation

---

##  Dataset Source

Data is sourced from **Our World in Data (OWID Energy Dataset)**  
Public dataset covering global energy consumption and socio-economic indicators.

- 23,000+ rows
- 130 features
- Multiple countries and years

---

##  Problem Statement

Electricity consumption per capita varies across countries due to economic development, population growth, and energy usage patterns.

This project aims to predict:

> **Per Capita Electricity Consumption**

Using:
- GDP
- Population
- Energy per capita
- Year
- Country

Countries analyzed:
- India
- Germany
- United States

---

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

##  Machine Learning Models Used

### 1️⃣ Linear Regression (Baseline Model)
- RMSE: ~344
- R²: ~0.99

### 2️⃣ Random Forest Regressor (Extension Model)
- RMSE: ~148
- R²: ~0.999

Random Forest significantly improved performance by capturing non-linear relationships.

---

## 📈 Key Insights

- Electricity consumption strongly correlates with GDP and energy per capita.
- Random Forest outperformed Linear Regression.
- High R² values indicate strong structure in the dataset.
- Performance may be slightly optimistic due to random train-test splitting on time-based data.

---

##  Project Workflow

1. Data loading from web
2. Dataset inspection
3. Feature selection
4. Missing value handling
5. One-hot encoding
6. Train-test split
7. Linear Regression modeling
8. Random Forest modeling
9. Model comparison
10. Interpretation of high R² scores

---

##  Future Improvements

- Time-based train-test splitting
- Cross-validation
- Hyperparameter tuning
- Expand to more countries
- XGBoost implementation
- Time-series forecasting

---

## 📂 How to Run

```bash
pip install -r requirements.txt
