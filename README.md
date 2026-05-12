---

# 📊 Page View Time Series Visualizer

A data visualization project built with **Python**, **pandas**, **matplotlib**, and **seaborn**.  
This project is part of the freeCodeCamp Data Analysis with Python Certification.

## 🚀 Project Overview
The goal of this project is to visualize forum page views over time.  
We clean the dataset by removing extreme outliers (top 2.5% and bottom 2.5%) and then generate three types of plots:

1. **Line Plot** – Daily page views over time.  
2. **Bar Plot** – Average monthly page views grouped by year.  
3. **Box Plots** – Distributions of page views by year and by month.

## 📂 Dataset
- Source: `fcc-forum-pageviews.csv`  
- Columns:
  - `date` → Date of observation (set as index).  
  - `value` → Number of page views.  

## 🛠️ Tech Stack
- [Python 3](https://www.python.org/)  
- [pandas](https://pandas.pydata.org/)  
- [matplotlib](https://matplotlib.org/)  
- [seaborn](https://seaborn.pydata.org/)  
- [Jupyter Notebook](https://jupyter.org/)  

## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/AllFatherZA/Time-series-visualizer.git
   cd Time-series-visualizer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook time_series_visualizer.ipynb
   ```

## 📊 Visualizations
### Line Plot
Shows daily page views from 2016–2019.

### Bar Plot
Displays average monthly page views grouped by year.

### Box Plots
- **Year-wise**: Trends across years.  
- **Month-wise**: Seasonal patterns across months.

## 👨‍💻 Author
- GitHub: AllFatherZA
- Project Maintainer: **Sibusiso Mnyandeni**

---
