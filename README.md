# Campus Facility Insight 📊
### Data Analysis and Visualization for Smart Campus Facility Management

## 📌 Project Overview

**Campus Facility Insight** is a data analytics project designed to analyse campus facility usage, occupancy patterns, examination-period changes, and maintenance downtime. It uses data analysis and visualization techniques to help campus administrators understand how effectively classrooms, laboratories, libraries, seminar halls, and other facilities are being utilized.

The project uses Python for data preprocessing, Exploratory Data Analysis (EDA), and feature engineering, along with Microsoft Excel for statistical analysis, PivotTables, and charts.

## 🎯 Objectives

- Identify the most frequently and heavily utilized campus facilities.
- Determine peak facility utilization periods.
- Identify underutilized rooms and spaces.
- Analyse changes in facility usage during examination periods.
- Identify facilities experiencing frequent maintenance downtime.
- Compare facility capacity with actual occupancy.
- Present analytical findings through meaningful charts and visualizations.

## 🗂️ Dataset Description

The project uses five datasets:

| Dataset | Description |
|---|---|
| `bookings.csv` | Facility reservations, dates, timings, and purposes |
| `facilities.csv` | Facility details, types, capacities, and campus blocks |
| `occupancy.csv` | Occupancy readings, timestamps, and facility information |
| `calendar.csv` | Working days, events, and examination-period indicators |
| `maintenance.csv` | Maintenance records, reported issues, and downtime |

The datasets used for this project are synthetic/sample datasets created for analysis and assessment purposes; they should not be interpreted as actual campus operational records.

## 🛠️ Technologies Used

- **Python** — Data preprocessing, analysis, and feature engineering
- **Pandas & NumPy** — Data manipulation and numerical analysis
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Feature selection
- **Google Colab** — Python notebook execution
- **Microsoft Excel** — Formulas, statistical summaries, PivotTables, and charts
- **GitHub** — Project documentation and version control

## 🔍 Project Workflow

1. **Data Understanding:** Examine the datasets, their structure, data types, and quality.
2. **Data Preprocessing:** Handle missing values, duplicate records, inconsistent facility names, and unusual occupancy readings.
3. **Exploratory Data Analysis:** Calculate descriptive statistics and explore facility utilization patterns.
4. **Feature Engineering:** Derive useful features such as booking duration, hour of day, day of week, peak-hour indicators, and utilization categories.
5. **Feature Selection:** Explore the relevance of numerical features to occupancy utilization.
6. **Excel Analysis:** Build summary tables, PivotTables, and charts to answer the business questions.
7. **Insights and Recommendations:** Interpret the results and identify opportunities for better facility management.

## 📈 Key Business Questions

The project focuses on six key questions:

1. Which facilities are most used?
2. What are the peak utilization periods?
3. Which rooms are underused?
4. How does examination-period activity change facility usage?
5. Which facilities have frequent maintenance downtime?
6. Does facility capacity match actual occupancy?

## 📊 Visualizations

The Excel analysis includes six primary graphs:

- **Most-Used Facilities:** Compares average utilization across facilities.
- **Peak Utilization Periods:** Shows average utilization by hour of day.
- **Underused Rooms:** Highlights facilities below the selected utilization threshold.
- **Exam-Period Comparison:** Compares average utilization during exam and non-exam periods.
- **Maintenance Frequency:** Identifies facilities with the highest number of maintenance records.
- **Capacity vs. Actual Occupancy:** Uses a scatter plot to compare facility capacity with average recorded occupancy.


## 💡 Expected Outcomes

The analysis aims to provide insights into:

- Facility utilization and demand patterns.
- Busy and less-active periods.
- Potential opportunities to improve space allocation.
- Differences in observed occupancy between examination and non-examination periods.
- Facilities with recurring maintenance records.
- The relationship between facility capacity and recorded occupancy.

These findings can help campus administrators make more informed decisions about space planning, resource allocation, scheduling, and maintenance prioritization.

## 🚀 How to Run

### Python Analysis

1. Open the project notebook in Google Colab.
2. Upload or mount the project datasets.
3. Update the dataset paths if required.
4. Run the notebook cells in sequence.
5. Review the generated tables and visualizations.

### Excel Analysis

1. Open `Campus_Facility_Analysis.xlsx` in Microsoft Excel.
2. Review the cleaned data and supporting summary tables.
3. Explore the PivotTables and six required charts.
4. Use the charts to interpret the business questions.

## ⚠️ Limitations

- The project uses synthetic/sample data rather than verified live campus data.
- Findings depend on the completeness and representativeness of the available records.
- Exam-period comparisons require sufficient matched occupancy readings.
- Maintenance downtime units should be confirmed before interpreting duration values.
- Feature relevance scores indicate statistical associations and do not establish causation.

## 🔮 Future Enhancements

- Integrate real-time occupancy sensors.
- Develop interactive dashboards using Power BI.
- Forecast facility demand using time-series analysis.
- Implement maintenance trend monitoring.
- Develop a recommendation system for improved facility scheduling.
