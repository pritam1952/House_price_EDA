# 🏠 House Price Prediction - Exploratory Data Analysis (EDA)

This project performs exploratory data analysis on the [Kaggle House Prices dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques), which contains residential property data from Ames, Iowa.

---

## 📊 Objectives

- Identify key features that influence house prices.
- Handle and visualize missing values.
- Explore relationships between variables and `SalePrice`.

---

## 🗂️ Files

- `House_price_EDA.ipynb`: Jupyter notebook with complete EDA.
- `/images`: Folder with plots saved from the notebook.
- `train.csv` and `test.csv`: Dataset files (must be downloaded from Kaggle).

---

## 🛠️ Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib
- NumPy
- Jupyter Notebook

---

## 🔍 Key Insights

- `SalePrice` is **right-skewed** — log transformation may help modeling.
- Features like `OverallQual`, `GrLivArea`, and `Neighborhood` show strong correlation with price.
- Missing values were imputed with **mode** (for categorical) and **median** (for numerical).

---

## 📈 Visualizations

### 📊 SalePrice Distribution
![SalePrice Distribution](images/saleprice_distribution.png)

### 🔥 Top Correlated Features
![Top Features Heatmap](images/top_features_heatmap.png)

### 🏡 GrLivArea vs SalePrice
![GrLivArea Scatter](images/grlivarea_vs_price.png)

### 📦 OverallQual vs SalePrice
![OverallQual Boxplot](images/overallqual_vs_price.png)

---

## 📥 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/house-price-eda.git
   cd house-price-eda
