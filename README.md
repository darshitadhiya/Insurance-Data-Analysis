# 📊 Insurance-Data-Analysis

## 📌 Project Title  
**A Power BI report analyzing insurance policies, claims, and customer feedback using SQL Server and sentiment analysis.**

---

## 🎯 Short Description / Purpose  
This report was created to help an insurance company understand their policy and claim data in a simple and visual way. The data was first taken from a CSV file and loaded into Microsoft SQL Server, then connected to Power BI for analysis. The report shows key insights like total premium, coverage, and claim amounts, along with customer details such as age, gender, and policy types. It also highlights how many claims were settled, pending, or rejected. A special part of the report shows customer feedback and their sentiment, helping the company understand if customers are happy or facing issues. By using clear charts, tables, and filters, the report helps the company make better decisions, improve services, and identify trends or problems in their data easily.

---

## 🛠 Tech Stack

| Technology              | Purpose / Usage                                      |
|-------------------------|------------------------------------------------------|
| **Microsoft SQL Server**| Data storage, flat file import, schema creation      |
| **Power BI Desktop**    | Data profiling, data modeling, interactive reporting |
| **Power Query Editor**  | Data transformation and cleaning                     |
| **DAX**                 | Measures and calculated columns for KPIs             |

---

## 📂 Data Information

- **Format:** CSV  
- **Imported into:** Microsoft SQL Server  
- **Total Records:** ~10,000 rows  
- **Table Description:** One main table containing policy, customer, and claim data

### 🔑 Key Columns:
- `PolicyNumber`, `CustomerID`, `ClaimNumber`  
- `Gender`, `Age`, `PolicyType`, `PolicyStartDate`, `PolicyEndDate`  
- `CoverageAmount`, `PremiumAmount`  
- `ClaimStatus`, `ClaimDate`, `ClaimAmount`

---

## 💼 Business Impact and Key Insights

- ✅ **Identified High-Performing Policy Types**  
  Travel and Health policies brought in the highest premium amounts, helping the company focus on profitable segments.

- ✅ **Detected Claim Patterns by Age Group**  
  Most claims came from adult customers, guiding targeted risk assessment and policy design.

- ✅ **Monitored Claim Statuses Effectively**  
  The dashboard revealed the proportion of claims that were settled, rejected, or still pending—helping improve claim handling and reduce delays.

- ✅ **Improved Customer Understanding through Feedback**  
  Sentiment analysis helped classify feedback into *Excellent*, *Good*, or *Needs Improvement*—highlighting areas where customer service can be improved.

---

## 📸 Visuals 

### 📍 Insurance Data Analysis Overview  
![Insurance Overview](https://github.com/darshitadhiya/Insurance-Data-Analysis/blob/main/Insurance%20Data%20Analysis%20Overview%20.png)

---

### 📍 Viewing Raw Data by Policy Types  
![Viewing Data by Policy](https://github.com/darshitadhiya/Insurance-Data-Analysis/blob/main/Viewing%20Data%20based%20on%20Policy%20types%20.png)

---

### 📍 Sentiment Analysis Dashboard  
![Sentiment Analysis](https://github.com/darshitadhiya/Insurance-Data-Analysis/blob/main/Sentiment%20Analysis.png)

---
