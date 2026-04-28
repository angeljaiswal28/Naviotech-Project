**Machine Learning Predictive Analysis Portfolio**

Welcome to my repository featuring two high-impact Machine Learning projects focused on predictive modeling. These projects demonstrate the end-to-end data science workflow: from data cleaning and exploratory analysis to model deployment and evaluation.

**Project 1: Medical Insurance Cost Prediction**

**Objective:** To predict the annual medical insurance premium for individuals based on their demographic and health profile.

**Project Overview**

This project helps insurance providers automate the cost-estimation process. By analyzing historical data, the model identifies which factors (like lifestyle or age) contribute most to healthcare expenses.

**Dataset Features:** Age, Sex, BMI, Number of Children, Smoking Status, and Region.

**Target Variable:** charges (USD).

**Technologies:** Python, Pandas, Scikit-Learn, Seaborn.

**Key Findings**

**The "Smoker" Effect:** Smoking status is the most significant predictor. Smokers are charged significantly higher premiums regardless of other factors.

**BMI Impact:** There is a strong correlation between high BMI (>30) and increased costs, especially when combined with smoking.

**Model Performance:** The Random Forest Regressor provided the highest accuracy, effectively capturing the non-linear nature of insurance pricing.

**Project 2: Big Mart Sales Prediction**

**Objective:** To forecast product sales across various Big Mart outlets to optimize inventory management and business strategy.

**Project Overview**

Retailers face challenges in stocking the right amount of product. This model predicts the Item_Outlet_Sales by analyzing product attributes and store characteristics.

**Dataset Features:** Item Weight, Fat Content, MRP (Price), Outlet Size, Location Type, and Establishment Year.

**Target Variable:** Item_Outlet_Sales.

**Technologies:** Python, XGBoost, Matplotlib, Label Encoding.

**Key Findings**

**Price Power:** Item_MRP has the strongest positive correlation with sales volume.

**Store Intelligence:** Supermarket Type 3 outlets consistently outperformed Grocery Stores and smaller outlets in total revenue.

**Data Challenges:** Success required significant data cleaning, specifically handling missing values in "Outlet Size" and "Item Weight."

**Top Model:** XGBoost was utilized for its superior ability to handle complex, high-dimensional retail data.

**Technical Skills Demonstrated**

**Data Cleaning:** Handling null values, fixing inconsistent labels, and removing outliers.

**Feature Engineering:** Converting categorical text into numerical data using Label Encoding.

**Data Visualization:** Using Heatmaps, Bar Plots, and Scatter Plots to derive business insights.

**Regression Modeling:** Implementing Linear Regression, Decision Trees, and Ensemble methods (Random Forest/XGBoost).

**Evaluation:** Using metrics like MAE (Mean Absolute Error) and RMSE (Root Mean Square Error) to validate results.
