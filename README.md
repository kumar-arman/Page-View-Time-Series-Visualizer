# Page View Time Series Visualizer

This project visualizes time series data using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.  
It is part of the **freeCodeCamp – Data Analysis with Python Certification**.

The dataset contains the number of daily page views on the freeCodeCamp.org forum from **May 2016 to December 2019**.

---

## 📌 Project Objective

The objective of this project is to:
- Analyze trends in forum page views over time
- Identify yearly growth patterns
- Observe monthly and seasonal variations in page views

These insights are obtained using different types of data visualizations.

---

## 📊 Dataset Information

- File name: `fcc-forum-pageviews.csv`
- Source: freeCodeCamp
- Time range: 2016-05-09 to 2019-12-03
- Columns:
  - `date` – Date of page views
  - `value` – Number of page views

---

## 🛠️ Technologies Used

- Python 3.11
- Pandas
- Matplotlib
- Seaborn
- VS Code
- Git & GitHub

---

## 📂 Project Structure

page-view-time-series-visualizer/
│
├── fcc-forum-pageviews.csv
├── time_series_visualizer.py
├── main.py
├── README.md
└── .gitignore


---

## ⚙️ Features Implemented

### 1. Data Cleaning
- Removed the top 2.5% and bottom 2.5% of page view values to eliminate outliers.

### 2. Line Plot
- Visualizes daily forum page views over time.
- Helps identify overall trends and growth patterns.

### 3. Bar Plot
- Displays average monthly page views grouped by year.
- Useful for comparing growth across different years and months.

### 4. Box Plots
- **Year-wise box plot** shows long-term trends.
- **Month-wise box plot** shows seasonal patterns.
- Months are ordered from January to December.

---

## ▶️ How to Run the Project

Ensure **Python 3.11** is installed.

### Install dependencies:
```bash
py -3.11 -m pip install pandas matplotlib seaborn

Run the project:
py -3.11 main.py

📈 Output

Running the project generates the following image files:

line_plot.png

bar_plot.png

box_plot.png

These plots visually represent trends, growth, and seasonality in forum activity.

🎯 Key Learnings

Working with time series data using Pandas

Data cleaning using quantiles

Grouping and aggregating data

Creating line, bar, and box plots

Identifying trends and seasonal patterns

Visual data analysis techniques


📜 License

This project is open-source and intended for educational purposes.


---

## 💾 Save the File
Press:


Ctrl + S


---

## 📤 Commit & Push README to GitHub

Run:

```bash
git add README.md
git commit -m "Added README for Page View Time Series Visualizer"
git push origin main
