# Delivery Time Prediction – Regression Analysis
This project applies various regression techniques to predict delivery time based on a real-world dataset. The goal is to identify the most effective model variant for accurate delivery time estimation and draw actionable insights for operational improvements.

Data Summary<br>
Data Source: Kaggle 

Dataset Size: The dataset contains 43739 rows and 16 columns.

Features:
Order_ID, Agent_Age, Agent_Rating, Store_Latitude, Store_Longitude, Drop_Latitude, 
Drop_Longitude, Order_Date, Order_Time, Pickup_Time, Weather, Traffic, Vehicle, 
Area, Category

Target Variable:
Delivery_Time 


Objective of the Analysis
- To develop a prediction model for Delivery_Time using the above features.
- Apply and compare various forms of regression to improve prediction accuracy.
- Choose the best-performing model based on statistical metrics such as R² score.

Model Comparison<br>
The following regression models were tested:
- Simple Linear Regression
- Lasso regression
- Polynomial regression

Performance Metrics (R² Score):
Model Variant	R² Score
Simple Linear Regression	~0.3758
Lasso regression ~0.3672
Polynomial Regression (Degree = 4) ~0.6896

Key Findings
There is a strong positive correlation between sorting time and delivery time.
The initial model was underfitting and polynomial Regression of degree 4 significantly improves model performance, achieving the highest R² score (~0.689).

Limitations and Next Steps
Limitations:
The model is able to explain only 68.96% of the variation, higher r2_score can be achieved by making more complex feature combinations.

Technologies Used
- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, sklearn)
- Jupyter Notebook

                    # Project overview
