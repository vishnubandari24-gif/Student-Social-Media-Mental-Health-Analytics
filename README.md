# 📊 Student Social Media & Mental Health Analytics Dashboard

## 📌 Project Overview

This Power BI project analyzes the relationship between social media usage and student mental health using interactive dashboards and data-driven insights.

The dashboard explores how factors such as screen time, stress levels, sleep quality, physical activity, and study habits influence student wellbeing across different countries and academic levels.

---

## 🎯 Objectives

- Analyze social media usage patterns among students.
- Measure the impact of social media on mental health.
- Identify stress-level distributions and wellbeing trends.
- Compare student behavior across countries and academic levels.
- Generate actionable insights through interactive visualizations.

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- CSV Dataset
- Data Modeling
- Interactive Data Visualization

---

## 📂 Dataset Information

| Attribute | Details |
|------------|------------|
| Records | 5000 |
| Columns | 13 |
| Domain | Education Analytics |
| Dataset Type | Student Mental Health Data |

### Key Features

- Age
- Gender
- Country
- Academic Level
- Most Used Platform
- Purpose Of Use
- Avg Daily Usage Hours
- Daily Unlocks
- Study Hours
- Physical Activity Hours
- Sleep Hours Per Night
- Stress Level
- Mental Health Score

---

## 🔄 Data Transformation

The dataset was cleaned and transformed using Power Query.

### Data Cleaning Steps

- Fixed incorrect data types
- Handled missing values
- Removed unwanted errors
- Standardized categorical values
- Created helper columns

### Custom Columns Created

- Usage_Category
- Sleep_Category
- Age_Group
- Study_vs_Social
- Stress_Order

---

## 📈 DAX Measures

The following measures were created:

```DAX
Total Students
Avg Mental Health Score
Avg Daily Usage Hours
Avg Study Hours
Avg Sleep Hours
Avg Stress Numeric
High Stress %
Good Sleep %
Most Used Platform
```

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

Features:

- KPI Cards
- Platform Distribution
- Mental Health Map
- Stress Distribution
- Interactive Filters

### KPIs

- Total Students
- Avg Mental Health Score
- Avg Daily Usage Hours
- Avg Sleep Hours
- Avg Study Hours
- Avg Stress Numeric

---

### 2️⃣ Social Media Analytics

Features:

- Most Used Platform Analysis
- Platform Usage by Purpose
- Daily Unlock Analysis
- Usage Category Insights

---

### 3️⃣ Lifestyle Analytics

Features:

- Sleep Quality Distribution
- Study Hours vs Social Media Usage
- Physical Activity Analysis
- Mental Health Trends

---

### 4️⃣ Country Analytics

Features:

- Global Mental Health Map
- Country Rankings
- Mental Health Score Comparison
- Student Distribution by Country

---

## 🔍 Key Insights

- Higher social media usage is associated with lower mental health scores.
- Students with poor sleep quality tend to experience higher stress levels.
- Physical activity contributes positively to mental wellbeing.
- Instagram and TikTok are the most frequently used platforms.
- Balanced study habits are linked to better mental health outcomes.

---

## 📷 Dashboard Screenshots

### Executive Overview

<img width="100%" src="Screenshots/Executive_Overview.png">

### Social Media Analytics

<img width="100%" src="Screenshots/Social_Media_Analytics.png">

### Lifestyle Analytics

<img width="100%" src="Screenshots/Lifestyle_Analytics.png">

### Country Analytics

<img width="100%" src="Screenshots/Country_Analytics.png">

---

## 🚀 Future Enhancements

- Real-time data integration
- AI-based mental health prediction
- Sentiment analysis
- Mobile dashboard optimization
- Advanced predictive analytics

---

## 📁 Repository Structure

```text
Student-Social-Media-Mental-Health-Analytics
│
├── Dashboard
│   └── Final Project.pbix
│
├── Dataset
│   └── Student_Social_Media_And_Mental_Health_Impact.csv
│
├── PPT
│   └── Student_Mental_Health_Dashboard_Presentation.pptx
│
├── Screenshots
│   ├── Executive_Overview.png
│   ├── Social_Media_Analytics.png
│   ├── Lifestyle_Analytics.png
│   ├── Country_Analytics.png
│
├── Documentation
│   └── PowerBI_Dashboard_Guide.pdf
│
└── README.md
```

---

## 👨‍💻 Author

**Bandari Vishnu**

Power BI Developer | Data Analyst | Business Intelligence Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository.
