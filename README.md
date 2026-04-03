# Scikitlearn_py

Collection of small machine learning and data analysis projects using Python, NumPy, pandas, Matplotlib, and scikit-learn.

## 1. NEPSE NBL Stock Analysis

Simple analysis of NBL (Nepal Bank Limited) stock data using Python, NumPy, pandas, and Matplotlib.

### What’s implemented
- Loaded NBL historical stock data from `nbl_stock_data.csv`.
- Converted the `Date` column to datetime and sorted by time.
- Plotted the closing price over time to visualize NBL’s price movement.

### Ideas for future work
- Add moving averages (e.g., 5-day, 20-day) and other technical indicators.
- Try a simple scikit-learn model to predict whether tomorrow's close will be higher or lower than today.
- Compare model-based strategy vs buy-and-hold using cumulative returns.

Files:
- `nbl_stock_data.csv`
- `nepse_nbl_analysis.ipynb`  *(or your actual notebook filename)*

---

## 2. Iris Classification

- Task: Classify Iris flowers into species using sepal/petal measurements.
- Methods: Train/test split, baseline classifier (e.g., LogisticRegression or RandomForest), accuracy evaluation.
- File(s): `iris_classification.ipynb`

---

## 3. Wine Dataset Analysis

- Task: Classify wines based on chemical properties.
- Methods: EDA, feature scaling, scikit-learn classification model.
- File(s): `wine_classification.ipynb`

---

## Tech Stack

- Python  
- NumPy  
- pandas  
- Matplotlib  
- scikit-learn  
- (Optional) SciPy, Seaborn