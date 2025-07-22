# Insurance-Data-Analysis
1. Project Title
   A Power BI report analyzing insurance policies, claims, and customer feedback using SQL Server and sentiment analysis.

2. Short Description/ Purpose
   This report was created to help an insurance company understand their policy and claim data in a simple and visual way. The data was first taken from a CSV file and loaded into Microsoft SQL Server, then connected to Power BI for analysis. The report shows key insights like total premium, coverage, and claim amounts, along with customer details such as age, gender, and policy types. It also highlights how many claims were settled, pending, or rejected. A special part of the report shows customer feedback and their sentiment, helping the company understand if customers are happy or facing issues. By using clear charts, tables, and filters, the report helps the company make better decisions, improve services, and identify trends or problems in their data easily.

3. Tech Stack
   Microsoft SQL Server	--Data storage, flat file import, schema creation
   Power BI Desktop	---Data profiling, data modeling, interactive reporting
   Power Query Editor----	Data transformation and cleaning
   DAX	--- Measures and calculated columns for KPIs

4. Data Information
   Format: CSV
   Imported into: Microsoft SQL Server
   Total Records: ~10,000 rows
   Tables: One main table containing policy, customer, and claim data
   Columns include:
   PolicyNumber, CustomerID, ClaimNumber
   Gender, Age, PolicyType, PolicyStartDate, PolicyEndDate
   CoverageAmount, PremiumAmount
   ClaimStatus, ClaimDate, ClaimAmount

5. Business Impact and key insights
   Identified High-Performing Policy Types
→ Travel and Health policies brought in the highest premium amounts, helping the company focus on profitable segments.

  Detected Claim Patterns by Age Group
→ Most claims came from adult customers, guiding targeted risk assessment and policy design.

  Monitored Claim Statuses Effectively
→ The dashboard revealed the proportion of claims that were settled, rejected, or still pending—helping improve claim handling and reduce delays.

  Improved Customer Understanding through Feedback
→ Sentiment analysis helped classify feedback into Excellent, Good, or Needs Improvement—highlighting areas where customer service can be improved.


   
