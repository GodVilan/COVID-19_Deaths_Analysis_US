# 🦠 COVID-19 Dashboard (Jupyter Notebook)

An interactive COVID-19 data analysis and visualization project built in Jupyter Notebook using **Plotly**, **Dash**, **Pandas**, and **Scikit-learn**.  

This project explores COVID-19 deaths, crude rates, and age-adjusted rates across the United States, regions, and states from **2020 to March 2025**.

---

## 🚀 Features

### KPIs
- Total deaths  
- Crude rate  
- Age-adjusted rate  
- Annualized crude and age-adjusted rates  

### Interactive Visualizations
- Time series trends of COVID-19 deaths and rates  
- Regional and state-level comparisons  
- Clustering analysis (K-means) to group jurisdictions  

### Exploration
- Filter data by jurisdiction (U.S., Regions, or States)  
- Focus on specific time ranges  

---

## 📂 Dataset

The dataset contains:

- **Jurisdictions:** United States, 10 Regions, 50 States  
- **Time Period:** 2020 – March 2025  
- **Metrics:**  
  - COVID deaths  
  - Crude COVID death rate  
  - Age-adjusted COVID death rate  

**Note:** Place the dataset file `COVID_19_Dataset.csv` in the same folder as the notebook before running.  

---

## ⚙️ How to Run


1. Clone the repository:
```bash
git clone https://github.com/your-username/covid19-dashboard.git
cd covid19-dashboard
```

2. Open Jupyter Notebook:
```bash
jupyter notebook
```

3. Open the notebook file (e.g., COVID19_Dashboard.ipynb) and run the cells in order.

4. If the dashboard app cell is included, it will run locally at:
```bash
http://127.0.0.1:8050/
```
## 📦 Dependencies

- Install the required libraries inside your Jupyter Notebook:

### Core libraries
```bash
%pip install pandas plotly scikit-learn statsmodels matplotlib
```

### Needed for Jupyter Notebook rendering
```bash
%pip install nbformat
```

### Dash for interactive dashboard
```bash
%pip install dash
```

## 📌 Notes

- Ensure you have Python 3.8+ installed.

- Make sure the dataset file is in the same directory as the notebook.

- The dashboard will only run if the cell containing Dash app code is executed.
