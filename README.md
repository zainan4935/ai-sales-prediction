# AI Sales Prediction using Python & Machine Learning

This project is based on analyzing and predicting retail sales using the Superstore dataset. The main goal of the project is to understand business sales performance and use machine learning to predict future sales trends. The project combines data analysis, data visualization, and machine learning in Python.

---

## Project Overview

In this project, I worked with a real-world retail dataset that contains information about customer orders, products, sales amount, profit, shipping details, and different business regions. Using Python, I analyzed the dataset to discover useful business insights and created a machine learning model to predict future sales.

---

## Steps Performed in the Project

### 1. Importing Required Libraries
I used different Python libraries for data analysis and visualization:

- Pandas for handling and analyzing data  
- NumPy for numerical operations  
- Matplotlib and Seaborn for creating graphs and charts  
- Scikit-learn for machine learning and prediction  

---

### 2. Loading the Dataset
The Superstore dataset was loaded from an Excel file using Pandas. After loading the data, I checked:

- Dataset shape  
- Column information  
- Statistical summary of the dataset  

This helped in understanding the structure and quality of the data.

---

### 3. Data Cleaning and Preprocessing
To make the dataset accurate and ready for analysis:

- Checked for missing values  
- Removed duplicate records  
- Converted order and shipping dates into proper datetime format  

I also created new columns from the order date such as:

- Year  
- Month  
- Day  
- Weekday  

These columns helped in analyzing sales trends over time.

---

## Exploratory Data Analysis (EDA)

### 4. Yearly Sales Analysis
I grouped the sales data by year and created a line graph to analyze yearly sales trends. This helped identify whether sales increased or decreased over time.

---
#### Yearly Sales Trend
[Yearly Sales](output/Screenshot 2026-05-21 104420.png)


### 5. Monthly Sales Analysis
I analyzed monthly sales performance to understand which months had higher or lower sales. This can help businesses plan marketing and inventory strategies.

---
#### Monthly Sales Analysis

### 6. Top Products Analysis
I identified the top 10 products with the highest sales using bar charts. This helped understand customer demand and the best-performing products.

---

### 7. Region-wise Sales Analysis
I compared sales performance across different regions to determine which regions generated more revenue for the business.

---

## Machine Learning Model

### 8. Feature Selection
For prediction, I selected:

- Year  
- Month  

as input features, and:

- Sales  

as the target variable.

---

### 9. Splitting the Dataset
The dataset was divided into:

- Training data (80%)  
- Testing data (20%)  

This helped train and evaluate the model properly.

---

### 10. Building the Prediction Model
I used the Linear Regression algorithm from Scikit-learn to train the model. The model learned patterns from historical sales data and predicted future sales values.

---

## Model Evaluation

To measure model performance, I used:

- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  

These metrics helped evaluate how accurately the model predicted sales.

---

## Actual vs Predicted Visualization

I created a scatter plot comparing actual sales and predicted sales values. This visualization helped understand the prediction accuracy of the model.

---

## Future Sales Prediction

Finally, I predicted future sales for upcoming months in the year 2026. This demonstrates how businesses can use machine learning for:

- Sales forecasting  
- Business planning  
- Inventory management  
- Decision-making  

---

## Skills Gained Through This Project

- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA)  
- Data Visualization  
- Machine Learning Basics  
- Sales Forecasting  
- Python Programming  
- GitHub Project Management  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Git & GitHub  
