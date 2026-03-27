# Remote Work Burnout Analysis

## 📌 Project Overview
This project analyzes how different work arrangements (remote, hybrid, and on-site) impact employee burnout, work-life balance, and social isolation using real-world survey data.

The goal is to combine data analysis, statistical testing, and visualization to generate meaningful insights about employee well-being.

---

## 🚀 Run the Project

👉 [Open in Google Colab](https://colab.research.google.com/github/imxal/Remote-work-burnout-analysis/blob/main/remote_work_analysis.ipynb)

---

## 📂 Dataset
- Source: Kaggle – Remote Work Health Impact Survey (2025)
- Records: 3,157 employees

### Key Features:
- Work Arrangement (Remote / Hybrid / On-site)
- Burnout Level
- Work-Life Balance Score
- Social Isolation Score
- Hours Worked

---

## Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization (Seaborn, Matplotlib)
- Statistical Testing (SciPy – ANOVA)
- Tableau (Interactive Dashboard)

---

## Data Processing
- Converted date column to datetime format
- Standardized categorical values (lowercase, trimmed)
- Removed unrealistic working hours (> 80 hours/week)
- Converted burnout levels into numerical scores:
  - Low = 1, Medium = 2, High = 3

---

## Key Analysis & Insights

### 🔹 Burnout Distribution
- Most employees fall into **medium burnout levels**
- A significant portion also experiences **high burnout**
- Indicates burnout is a widespread issue

---

### 🔹 Burnout by Work Arrangement
- Burnout levels are **similar across work types**
- On-site workers show **greater variability in burnout levels**

---

### 🔹 Statistical Testing (ANOVA)
- F-statistic: 59.28  
- P-value: < 0.001  

**Conclusion:**
- Burnout differs significantly across work arrangements
- However, the **practical difference is relatively small**

---

### 🔹 Average Burnout Comparison
- Remote workers show **slightly higher average burnout**
- On-site workers show **slightly lower burnout**
- Indicates a moderate, not extreme, difference

---

### 🔹 Working Hours vs Burnout
- No strong relationship between working hours and burnout
- Suggests burnout is influenced more by environment than hours

---

### 🔹 Correlation Analysis
- Burnout has **very weak correlation** with:
  - Working hours
  - Work-life balance
- Slight positive relationship with **social isolation**

---

### 🔹 Work-Life Balance
- Similar across remote, hybrid, and on-site work
- Suggests work arrangement alone does not determine balance

---

### 🔹 Social Isolation
- Remote workers show **higher social isolation**
- Highlights a key trade-off of remote work

---

## 🔬 Research Validation

This analysis was compared with findings from:

**“Remote Work Opportunities and Preferences Among Public Health Employees (2026)”**

### Alignment:
- Work arrangement impacts employee well-being ✔️
- Social isolation is higher in remote work ✔️

### Difference:
- Research suggests remote work reduces burnout  
- This dataset shows slightly higher burnout in remote workers  

### Interpretation:
This suggests that remote work outcomes depend on additional factors such as:
- Social isolation
- Work boundaries
- Organizational support

---

## 💡 Final Conclusion

- Work arrangement has a statistically significant impact on burnout  
- Differences are relatively small in practice  
- Remote work may increase social isolation  
- Burnout is influenced by multiple factors beyond work type  

---

## 🚀 Future Improvements
- Predictive modeling for burnout risk
- Regression analysis
- Enhanced dashboard interactivity
- Larger and more diverse datasets

---

## 📌 Key Takeaway
This project demonstrates how data analysis, statistical validation, and visualization can be combined to analyze real-world problems and generate actionable insights.
