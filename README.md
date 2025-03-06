# Ames Housing Price Prediction - Linear Regression Project

This repository contains a Machine Learning project that applies **Linear Regression** using **ElasticNet** to predict house prices based on the **Ames Housing Dataset**.

## Project Overview
The goal of this project is to build a **Linear Regression Model**, optimize it using **Grid Search**, and evaluate its performance on a test dataset. The dataset used in this project contains various housing features from Ames, Iowa, with **SalePrice** as the target variable.

### **Key Steps in the Project**
1. **Setting up the workspace**  
   - Created a GitHub repository  
   - Ignored unnecessary files using `.gitignore`  
   - Managed dependencies with `environment.yml`  

2. **Data Preparation & Preprocessing**  
   - Loaded the cleaned Ames Housing dataset  
   - Split data into **X (features) and y (target)**  
   - Scaled features using `StandardScaler`  

3. **Model Selection & Optimization**  
   - Used **ElasticNet** regression (combination of L1 & L2 regularization)  
   - Tuned hyperparameters (**alpha** and **l1_ratio**) using **GridSearchCV**  

4. **Model Evaluation**  
   - Evaluated on **10% unseen test data**  
   - Performance metrics:  
     - **MAE** (Mean Absolute Error): ~14,365  
     - **RMSE** (Root Mean Squared Error): ~21,111  

---

## **Setup & Installation**
To run this project on your machine, follow these steps:

### **Clone the Repository**
```bash
git clone https://github.com/your-username/linear-regression-housing.git
cd linear-regression-housing
