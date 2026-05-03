# Covid-19-Case-Study
# 🦠 COVID-19 Data Analysis using Python

## 📌 Overview
This project presents an end-to-end analysis of COVID-19 data using Python.  
The analysis includes data cleaning, transformation, visualization, and extracting key insights from confirmed, deaths, and recovered datasets.

---

## 📂 Project Structure

- 📁 [data](./data) → Raw dataset  
- 📁 [notebooks](./notebooks) → Main analysis notebook  
- 📁 [outputs](./outputs) → Graphs and results  
- 📄 README.md  
- 📄 requirements.txt  

---

## ⚙️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## 🔍 Key Tasks Performed

### 🧹 Data Cleaning
- Handled missing values using forward fill  
- Replaced blank `Province/State` values with "All Provinces"  
- Converted date columns into datetime format  

### 🔄 Data Transformation
- Converted wide format to long format using `melt()`  
- Restructured data into time-series format  
- Aggregated province-level data to country level  

### 📊 Exploratory Analysis
- Identified top countries with highest confirmed cases  
- Visualized COVID-19 trends over time  
- Analyzed country-specific trends (e.g., China, US)  

### 📈 Advanced Analysis
- Peak daily new cases (Germany, France, Italy)  
- Recovery rate comparison (Canada vs Australia)  
- Death rate distribution across regions  

### 🔗 Data Merging
- Merged confirmed, deaths, and recovered datasets  
- Created a unified dataset for comprehensive analysis  
- Performed monthly aggregation of cases  

---

## 📈 Key Insights
- Significant variation observed in death and recovery rates across countries  
- Early pandemic phases showed higher mortality in certain regions  
- Recovery rates improved over time due to better healthcare response  
- Pandemic trends show multiple waves across countries  

---

## 🚀 How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Open the notebook:
jupyter notebook notebooks/covid_analysis.ipynb

---

## 📸 Sample Output
(Add screenshots of your graphs here)

---

## 💡 Key Learnings
- Time-series analysis using Pandas  
- Handling real-world datasets  
- Data transformation (wide → long)  
- Multi-dataset merging  
- Extracting meaningful insights  

---

## 👤 Author
Nishant Shrivastava  
BTech Graduate | Aspiring Data Analyst
