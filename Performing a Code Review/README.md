# Smartphone Insights Visualizer 📱📊

This project is a Python-based data analysis and visualization tool designed to explore smartphone features and trends using a dataset of various phone models. It includes data cleaning, preprocessing, and visualization using `pandas`, `matplotlib`, and `seaborn`.

## 📂 Files
- `smartphone-insights-visualizer.ipynb`: The main analysis notebook.
- `smartphones.csv`: Raw data containing smartphone specifications.
- `requirements.txt`: Python dependencies needed to run the notebook.

## 🚀 Features
- Cleans raw smartphone data by:
  - Selecting relevant columns
  - Dropping missing values for key features
  - Converting price from cents to dollars
- Creates insightful visualizations:
  - Distribution of battery capacity
  - OS-based feature comparisons
  - Price and performance relationships

## 📊 Dataset Columns Used
- `brand_name`
- `os`
- `price`
- `avg_rating`
- `processor_speed`
- `battery_capacity`
- `screen_size`

## 🔍 Sample Visualizations
- Battery capacity by OS
- Processor speed vs price
- Brand comparisons on screen size

## 📃 License
This project is for educational and research purposes.

---

### 📦 `requirements.txt`

```txt
pandas
matplotlib
seaborn