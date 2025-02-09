# Retail Sales Prediction using XGBoost

## 📌 Project Overview
This project focuses on predicting retail sales using machine learning techniques, specifically **XGBoost Regressor**. The dataset consists of product attributes, store details, and historical sales data. The goal is to develop an accurate predictive model to estimate future sales.

## 🚀 Features
- **Data Preprocessing**: Handling missing values and encoding categorical variables.
- **Feature Engineering**: Log transformation and outlet age calculation.
- **Model Training**: Using **XGBoost Regressor** to predict sales.
- **Performance Evaluation**: R² score for model accuracy assessment.
- **Data Visualization**: Histograms and count plots for exploratory data analysis.

## 📂 Dataset
The dataset contains the following key columns:
- `Item_Identifier`: Unique ID for products.
- `Item_Weight`: Weight of the product.
- `Item_Visibility`: Visibility percentage of the product.
- `Item_Type`: Category of the product.
- `Item_MRP`: Maximum Retail Price.
- `Outlet_Identifier`: Unique ID for the store.
- `Outlet_Establishment_Year`: Year of store opening.
- `Outlet_Size`: Store size (Small/Medium/High).
- `Outlet_Location_Type`: Location type of the store.
- `Outlet_Type`: Type of store (Grocery, Supermarket, etc.).
- `Item_Outlet_Sales`: **Target variable** representing sales.

## 🛠 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Retail Sales Prediction using Machine Learning (XGBoost, Pandas, Matplotlib).git
   cd retail-sales-prediction
   ```

## 📊 Model Performance
The trained **XGBoost model** achieves the following results:
- **Train R² Score**: `~0.84`
- **Test R² Score**: `~0.32`

## 📌 Usage
1. Load the dataset (`BigMart_Sales.csv`).
2. Run `sales_prediction.py` to preprocess the data, train the model, and visualize results.
3. Modify hyperparameters for further improvements.
