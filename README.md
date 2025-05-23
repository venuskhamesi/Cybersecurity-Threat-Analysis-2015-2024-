# Cybersecurity Threat Analysis (2015–2024) 🔐

## 📊 Overview
This project explores global cybersecurity threats using data science and machine learning to detect anomalies, uncover behavioral patterns, and build a Power BI dashboard for impactful storytelling. The dataset includes 3,000 real-world incidents recorded from 2015 to 2024.

---

## 🧰 Tools & Technologies
- **Python** (Pandas, Scikit-learn, PyOD)
- **Jupyter Notebook**
- **MySQL Workbench**
- **Power BI**

---

## 📁 Project Phases

### ✅ Phase 1: Data Cleaning & EDA
- Cleaned and explored global cybersecurity incidents
- Analyzed attack types, financial loss, resolution time, and affected industries

### ✅ Phase 2: SQL ETL
- Designed schema and imported cleaned dataset into MySQL Workbench
- Queried key patterns like attack frequency and top loss-causing regions

### ✅ Phase 3: Modeling
- **Isolation Forest**: Detected 150 anomalies (5% of records)
- **One-Class SVM**: Detected 155 anomalies
- **KMeans Clustering**: Revealed 3 unique behavioral clusters of threats

### ✅ Phase 4: Power BI Dashboard
- One-page dashboard with KPI cards, bar chart, line chart, pie chart, and gauge chart
- Showcased attack trends, financial losses, and threat sources

---

## 🔍 Key Insights
- **Ransomware** and **Phishing** caused the highest financial damage
- **Nation-states** and **hacker groups** were primary threat actors
- **Average resolution time** across incidents: 36.48 hours
- **Anomaly detection** identified ~5% of unusual incidents using ML

---

## 📊 Dashboard Preview

![Power BI Dashboard](dashboard.png)

---

## 🏁 How to Run This Project

1. Clone the repository
2. Open `cybersecurity_threat_analysis_EDA.ipynb` in Jupyter Notebook
3. Import `cleaned_cybersecurity_threats.csv` into MySQL
4. Open Power BI and connect to your local MySQL or use the CSV file
5. Rebuild the dashboard using the layout in this README

---

## 🎯 Conclusion

This project demonstrates how data science can proactively enhance cybersecurity response. Through anomaly detection, clustering, and visual analytics, we can uncover hidden patterns and make data-driven decisions for threat mitigation.

---

## 🔗 Connect with Me
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)
