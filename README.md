## Healthcare Claims Analysis Dashboard

# **Summary**
In the complex landscape of healthcare processing, this project aims to identify patterns in claim approvals, denials, and provider performance to optimize efficiency and provide actionable insights. Using **synthetic health insurance claims data**, we analyze trends, uncover key insights, and visualize approval rates based on multiple factors, including provider specialties, claim amounts, patient demographics, and geographic distribution.

# **Research Questions**
1. How many claims were submitted, approved, denied, and are still pending?
2. What trends can we observe in the number of claim submissions over time?
3. How do provider specialties and claim amounts impact approval rates?
4. Are there regional disparities in claim approvals across different locations?

# **Calculations & Methodology**

### **Approval Rate Calculation**
```r
approval_rate <- approved_claims / total_claims
```

### **Trend Analysis**
- Used a **time series line chart** to observe fluctuations in claim volumes over time.
- Applied a **moving average** to smooth out short-term fluctuations and highlight long-term trends.

### **Provider Specialty & Claim Amount Analysis**
- Used a **box plot** to analyze claim amount distributions by specialty and identify variations.
- Created a **heatmap visualization** of **approval rates across provider specialties** to determine which fields had the highest success rates.

### **Geographic Analysis**
- Mapped claim approval rates across the USA using **color gradients** to highlight regional disparities.
- Bubble sizes represent total claims submitted per location.

# **Inferences from the Dashboard**

## **1. Total Claims Breakdown**
- Out of **4,500** total claims:
  - **1,522** were approved ✅
  - **1,512** were denied ❌
  - **1,466** are still pending ⏳
- Approval rates vary significantly across providers, specialties, and geographic locations.

## **2. Trends in Claim Submissions**
- The **line chart** reveals a fluctuating trend in claim submissions over time, with a slight decline in recent months.
- Forecasting suggests a stabilization in future claim submissions.

## **3. Impact of Provider Specialties & Claim Amounts**
- The **box plot** shows high variability in claim amounts across specialties.
- Certain specialties, such as **Orthopedics & Neurology**, show **higher approval rates** compared to **General Practice & Pediatrics**.
- Some specialties have **outliers** with exceptionally high claim amounts, indicating potential billing inconsistencies.

## **4. Geographic Disparities in Claim Approvals**
- The **map visualization** highlights approval rates across different states.
- Some regions have **notably lower approval rates**, possibly due to stricter claim review processes or higher rejection rates.
- Locations with **high claim volumes** but **low approval rates** may require further investigation into provider practices and claim quality.

# **Conclusion & Next Steps**
This analysis provides a **data-driven approach** to understanding claim processing trends and optimizing approval rates. Insights from the dashboard can help **insurance companies, healthcare providers, and policymakers** make informed decisions.

### **Next Steps**
- Deep dive into **denied claims** to identify common rejection reasons.
- Further segment claims by **patient demographics (age, income, employment status)** to refine approval models.
- Optimize provider claim submission practices to improve approval rates.

This project demonstrates how **data visualization & analytics** can transform raw healthcare claims data into actionable insights for better decision-making.









Source: https://www.kaggle.com/datasets/abuthahir1998/synthetic-healthcare-claims-dataset

