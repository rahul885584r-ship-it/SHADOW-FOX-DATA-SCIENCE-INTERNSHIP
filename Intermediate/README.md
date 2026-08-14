# 🌫️ Air Quality Data Analysis

This project is an **Air Quality Data Analysis** project focused on analyzing Delhi air-quality observations using Python.

The project explores **PM2.5, PM10, and other air-quality parameters** through data cleaning, statistical analysis, and visualization.

## 📌 Project Overview

The dataset contains hourly air-quality observations from Delhi. The analysis includes loading the CSV dataset, understanding its structure, checking data quality, preparing date information, and creating different visualizations.

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 📂 Dataset

The dataset contains the following air-quality parameters:

* `CO`
* `NO`
* `NO2`
* `O3`
* `SO2`
* `PM2.5`
* `PM10`
* `NH3`
* `Date`

The working dataset contains **561 observations and 9 columns**.

## 🔄 Project Workflow

1. Load the Delhi air-quality CSV dataset
2. Inspect rows and columns
3. Check dataset shape and data types
4. Generate summary statistics
5. Check missing values
6. Remove duplicate/null records
7. Convert the date column into datetime format
8. Create a Month column
9. Analyze PM2.5
10. Create different visualizations
11. Analyze relationships between air-quality parameters

## 📊 Visualizations

The project includes the following visualizations:

* 📈 PM2.5 Trend Over Time — Line Chart
* 📊 Average PM2.5 by Month — Bar Chart
* 📉 PM2.5 Distribution — Histogram
* 📦 PM2.5 Variability — Box Plot
* 📈 Monthly PM2.5 Trend — Line Plot
* 🔥 Air-Quality Correlation — Seaborn Heatmap
* 🔵 PM2.5 vs PM10 — Scatter Plot

## 🔍 Data Quality

The dataset was checked for missing values. The report shows **zero missing values across all columns**. A cleaning step using `dropna()` is also included as a defensive measure.

## 📈 Key Analysis

### PM2.5 Trend

A line chart is used to observe changes in PM2.5 across the recorded dates.

### Monthly PM2.5

Monthly aggregation is used to compare average PM2.5 values across the available observations.

### PM2.5 Distribution

A histogram is used to understand the concentration and spread of PM2.5 values.

### Correlation Analysis

A Seaborn heatmap is used to inspect pairwise correlations between numerical air-quality variables.

### PM2.5 vs PM10

A scatter plot is used to visually inspect the relationship between PM2.5 and PM10 observations.

## 🎯 Key Learnings

Through this project, I learned how to perform a beginner-to-intermediate data-analysis workflow:

* Loading datasets with Pandas
* Exploring dataset structure
* Checking data quality
* Handling missing/duplicate records
* Working with datetime data
* Performing basic data analysis
* Creating visualizations with Matplotlib
* Creating statistical visualizations with Seaborn
* Analyzing correlations between variables

## 📁 Project Files

```text
Air-Quality-Data-Analysis/
│
├── Intermediate_project(2).ipynb
├── delhiaqi.csv
├── README.md
└── Air_Quality_Analysis_Report.pdf
```

## 💡 Conclusion

This project provides a visual understanding of particulate pollution and its relationship with other measured air-quality parameters. Matplotlib is used for chart customization, while Seaborn makes statistical visualizations such as heatmaps and scatter plots convenient.

## 👨‍💻 Author

**Rahul Kharwar**



