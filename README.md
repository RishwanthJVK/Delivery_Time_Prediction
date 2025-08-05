# Delivery Time Prediction – Regression Analysis

This project applies various regression techniques to **predict delivery time** using a real-world dataset. The goal is to identify the most effective model for accurate estimation and draw actionable insights for operational improvements.

---

## Data Summary

* **Data Source**: Kaggle
* **Dataset Size**: 43,739 rows × 16 columns

### Features

* `Order_ID`
* `Agent_Age`
* `Agent_Rating`
* `Store_Latitude`, `Store_Longitude`
* `Drop_Latitude`, `Drop_Longitude`
* `Order_Date`, `Order_Time`, `Pickup_Time`
* `Weather`, `Traffic`, `Vehicle`
* `Area`, `Category`

### Target Variable

* `Delivery_Time`

---

## Objective of the Analysis

* Develop a **prediction model** for `Delivery_Time` using the available features.
* Apply and compare **multiple regression techniques** to improve prediction accuracy.
* Select the **best-performing model** based on metrics such as **R² score**.

---

##  Data Cleaning & Feature Engineering

- Handled **missing values**
- Analysed Duplicates
- Handled Outliers
- Handled Mistyped data
- Encoded categorical variables (Ordinal Encoding, One-Hot Encoding)

---

## Model Comparison

| Regression Model              | R² Score |
| ----------------------------- | -------- |
| Simple Linear Regression      | \~0.3758 |
| Lasso Regression              | \~0.3672 |
| Polynomial Regression (Deg=4) | \~0.6896 |

---

## Key Findings

* The initial simple models showed signs of **underfitting**.
* **Polynomial Regression (degree = 4)** significantly improved performance with an R² score of **\~0.6896**.
* Indicates that non-linear relationships exist in the data that simpler models couldn't capture.

---

## Limitations

* Although polynomial regression improved results, the model explains only **\~69%** of the variance.
* Higher accuracy could be achieved by generating more complex feature interactions

---

##  Technologies Used

* **Languages**: Python
* **Libraries**:

  * `NumPy`, `Pandas`
  * `Scikit-learn`
  * `Matplotlib`, `Seaborn`
* **Environment**: Jupyter Notebook

---
