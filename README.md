# 🚗 Car Sales Analysis using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Car Sales dataset using Python. The objective is to analyze sales trends, customer preferences, vehicle categories, pricing, and other important insights through data visualization and statistical analysis.

---

## 🎯 Objectives

- Import and clean the dataset
- Handle missing values
- Perform Exploratory Data Analysis (EDA)
- Analyze sales trends
- Visualize relationships between variables
- Generate business insights using charts

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Project Structure

```
car_sales/
│
├── Car_Sales.ipynb
├── car_sales.csv
├── README.md
└── images/
```

---

## 📚 Python Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 📊 NumPy Functions Used

| Function | Purpose |
|----------|---------|
| np.array() | Create NumPy array |
| np.mean() | Calculate mean |
| np.median() | Calculate median |
| np.std() | Standard deviation |
| np.max() | Maximum value |
| np.min() | Minimum value |
| np.sum() | Sum of values |
| np.unique() | Unique values |
| np.where() | Conditional selection |
| np.isnan() | Check missing values |

Example:

```python
np.mean(df["Price"])
np.max(df["Sales"])
np.unique(df["Fuel"])
```

---

# 🐼 Pandas Functions Used

## Loading Data

```python
pd.read_csv()
```

## Dataset Information

```python
df.head()
df.tail()
df.info()
df.describe()
df.shape
df.columns
df.dtypes
```

## Data Cleaning

```python
df.isnull()
df.isnull().sum()
df.dropna()
df.fillna()
df.duplicated()
df.drop_duplicates()
```

## Data Selection

```python
df.loc[]
df.iloc[]
df['Column']
```

## Sorting

```python
df.sort_values()
```

## Grouping

```python
df.groupby()
```

## Statistical Functions

```python
df.mean()
df.median()
df.max()
df.min()
df.value_counts()
df.nunique()
```

## Filtering

```python
df[df["Fuel"]=="Petrol"]
```

---

# 📈 Seaborn Functions Used

## Histogram

```python
sns.histplot()
```

## Bar Plot

```python
sns.barplot()
```

## Count Plot

```python
sns.countplot()
```

## Scatter Plot

```python
sns.scatterplot()
```

## Line Plot

```python
sns.lineplot()
```

## Box Plot

```python
sns.boxplot()
```

## Violin Plot

```python
sns.violinplot()
```

## Heatmap

```python
sns.heatmap()
```

## Pair Plot

```python
sns.pairplot()
```

---

# 📊 Sample Visualizations

- Sales Distribution
- Fuel Type Analysis
- Transmission Analysis
- Price Distribution
- Correlation Heatmap
- Vehicle Sales by Brand
- Year-wise Sales Trend

---

# 📌 Key Insights

- Identify the most sold car brands.
- Compare Petrol vs Diesel vehicle sales.
- Analyze selling price distribution.
- Detect outliers using Boxplots.
- Study feature correlations using Heatmaps.

---

# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/sidd5911/car_sales.git
```

2. Install dependencies

```bash
pip install numpy pandas matplotlib seaborn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebook cells.

---

# 📦 Requirements

```
Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Jupyter Notebook
```

Install all packages using:

```bash
pip install -r requirements.txt
```

---

# 📈 Future Improvements

- Machine Learning Sales Prediction
- Power BI Dashboard
- Interactive Streamlit Dashboard
- Sales Forecasting
- Customer Segmentation

---

## 👨‍💻 Author

**Kunwar Siddharth Singh**

**Data Analyst | Computer Science (AI & ML)**

### Skills

- Python
- NumPy
- Pandas
- Seaborn
- Matplotlib
- SQL
- Power BI
- Excel
- Exploratory Data Analysis (EDA)
- Git & GitHub

📧 Email: sohisiddhart@gmail.com

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!
