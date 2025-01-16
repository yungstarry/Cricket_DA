# **T20 World Cup Player Analysis**

## **1. Title**
T20 World Cup Player Analysis – Performance Insights and Recommendations

---

## **2. Introduction**
This project analyzes players' performance in the T20 World Cup based on batting and bowling metrics. The goal is to identify key performers, derive actionable insights, and provide recommendations for team selection and strategy.

---

## **3. About the Data**
The dataset includes player statistics from the T20 World Cup. The data is categorized by batting and bowling performances, covering metrics such as batting average, strike rate, innings batted, innings bowled, economy rate, and dot-ball percentage.

---

## **4. Methodology**

### **Data Collection**
The data was collected from publicly available T20 cricket databases, scorecards, and APIs, providing detailed player performance metrics.

### **Data Cleaning & Transformation**
- Removed duplicates and irrelevant columns.
- Normalized data formats (e.g., dates, numeric values).
- Handled missing data by imputing averages for minor gaps or excluding records with significant missing values.

### **Exploratory Data Analysis**
Analyzed key player performance metrics using statistical techniques and visualized trends across batting and bowling statistics.

### **Visualization**
- Created dynamic dashboards using **Power BI** to display key insights interactively.
- Developed visualizations to compare batting and bowling performances.

### **Statistical Analysis**
- Correlation between batting average and strike rate.
- Analyzed bowling economy and dot-ball percentage to evaluate bowlers' efficiency.

### **Interpretation & Recommendations**
Derived insights to aid in player selection and game strategy optimization.

---

## **5. Data Structure**

| **Table Name**           | **Description**                              |
|--------------------------|---------------------------------------------|
| `dim_players`            | Player information (name, role, team, style). |
| `fact_batting_summary`   | Player batting statistics.                   |
| `fact_bowling_summary`   | Player bowling statistics.                   |
| `dim_match_summary`      | Match metadata (stage, teams, date).         |


![Data Model Overview](/images/tableView.png)

---

## **6. Data Model Overview**
![Data Model Overview](/images/Model.png)

The model uses a star schema:
- **Fact Tables**: `fact_batting_summary`, `fact_bowling_summary`.
- **Dimension Tables**: `dim_players`, `dim_match_summary`.

---

## **7. Analysis**
### **Batting Analysis**
- **Batting Average**: Reflects consistency. Higher averages indicate dependable players.
- **Strike Rate**: Measures scoring efficiency. Key for identifying aggressive players.
- **Batting Position**: Analyzed impact on performance metrics.

### **Bowling Analysis**
- **Economy Rate**: Evaluates efficiency in conceding runs.
- **Bowling Strike Rate**: Measures frequency of taking wickets.
- **Dot Ball Percentage**: Key indicator of pressure applied by bowlers.

---

## **8. Dashboards**
### **Player Performance Dashboard**
![Dashboard Image 1](/images/dash1.png)
![Dashboard Image 3](/images/dash3.png)

### **Batting and Bowling Comparison**
![Dashboard Image 2](/images/dash2.png)

---

## **9. Insights**
### **Batting Insights**
- **Power Hitters**: High strike rates but moderate averages indicate aggressive intent.
- **Anchors**: High averages with consistent performance.
- **Optimal Batting Positions**: Players perform better in positions suited to their style.

### **Bowling Insights**
- **Economical Bowlers**: Low economy rates and high dot-ball percentages are key for controlling runs.
- **Wicket-Takers**: Low bowling strike rates identify consistent wicket-takers.

---

## **10. Recommendations**
1. Select players with high batting averages for top-order positions and strike rate specialists for finishing roles.
2. Use bowlers with high dot-ball percentages to build pressure during the middle overs.
3. Optimize team strategy by leveraging batting and bowling metrics specific to match conditions.

---

**Author**: AdorDev  
**Date**: January 2025  
**Tools Used**: Power BI, SQL, Python  

- [Check it out on Power BI Services](https://app.powerbi.com/view?r=eyJrIjoiYTA0N2JkYjctM2UwNy00ZTc0LWJiZjktNmEwY2ZmM2ZkZGY1IiwidCI6IjhmNzg3ODg0LTA2MTctNDEzMi05MzFhLTQyYjljM2ViNjM3YiJ9)

