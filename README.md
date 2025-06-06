
# 📚 Learning Operations Analytics Projects

This repository contains two simulated data analytics projects tailored for Learning & Development (L&D) operations, inspired by real-world roles such as the **Deloitte Analyst – Learning Operations & Data Reporting** position.

---

## 📁 1. LMS Simulation Project (Excel)

### 📌 Overview
The **LMS Simulation Project** is a structured Excel-based dashboard simulating a real-world Learning Management System (LMS) for tracking learner participation, attendance, and course completion.

### 🎯 Objectives
- Track learner enrollments across departments and courses
- Calculate key metrics such as **Attendance Rate**, **Completion Rate**, and **No-Show Count**
- Provide a user-friendly, refreshable Excel dashboard using **Pivot Tables** and **Slicers**

### 🛠️ Tools & Features
- Microsoft Excel
- Pivot Tables and Charts
- Conditional Formatting
- Slicers (Course, Department, Status)
- KPI summary dashboard

### 📊 KPIs Tracked
- Total Enrollments
- Attendance Rate (% sessions attended)
- Completion Rate (% of courses completed)
- No-Show Count

### 📈 Outcome
Delivered an Excel dashboard that allows L&D teams to visualize learner engagement and course outcomes, enabling quick decision-making on training improvements.

---

## 📁 2. Training Program Enrollment & Attendance Dashboard (Power BI)

### 📌 Overview
This Power BI project simulates a professional-grade **Training Dashboard** for analyzing enrollment, attendance, and completion across training programs.

### 🎯 Objectives
- Analyze learner engagement across departments and courses
- Provide drill-down dashboards for training performance
- Use DAX to compute essential L&D metrics

### 🛠️ Tools & Technologies
- Power BI Desktop
- DAX Measures
- KPI Cards, Bar and Line Charts
- Slicers for Department, Course Name, and Status

### 📊 DAX Measures
```DAX
TotalEnrollments = COUNTROWS('TrainingData')
PresentCount = CALCULATE(COUNTROWS('TrainingData'), 'TrainingData'[Attendance Status] = "Present")
CompletionCount = CALCULATE(COUNTROWS('TrainingData'), 'TrainingData'[Completion Status] = "Completed")
AttendanceRate = DIVIDE([PresentCount], [TotalEnrollments], 0)
CompletionRate = DIVIDE([CompletionCount], [TotalEnrollments], 0)
```

### 📈 Dashboard Features
- Dynamic filtering by Department and Status
- Enrollment trends over time
- No-show and low-completion analysis
- Department-wise attendance performance

### 🧠 Key Takeaway
Replicates dashboards used by L&D or Learning Operations teams at enterprise firms like **Deloitte** to monitor and improve training effectiveness.

---

## 🔗 Ideal For
- Entry-Level Analyst Roles (L&D / HR / Reporting)
- Data Analytics Portfolios
- Power BI / Excel Dashboard Practice

---
