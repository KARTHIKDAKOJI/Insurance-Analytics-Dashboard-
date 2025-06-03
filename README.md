# Insurance-Analytics-Dashboard-


![image alt](https://github.com/KARTHIKDAKOJI/Insurance-Analytics-Dashboard-/blob/7098426d29a03f1c1d6bb2ae3641cbc3b75e9717/Screenshot%202025-06-03%20100843.png)


## 📊Insurance Data Analysis Project (Power BI & SQL)
# 🚀Project Overview
This project analyzes insurance data to extract valuable insights into how an insurance company operates. It focuses on key metrics such as Premium Amount, Coverage Amount, and Claim Amount to understand patterns in policies, claims, and coverage over a specific period.

# 📌Key Definitions
# 💰Premium Amount: The amount charged by the insurance company to the policyholder for providing coverage.

# 🛡️Coverage Amount (Sum Insured): The maximum payout the insurer agrees to pay in case of a claim.

# 📄Claim Amount: The amount requested by the policyholder from the insurer after a loss or damage.

# 🧹Data Cleaning & Preprocessing
Raw data initially loaded into MS SQL Server for error detection and datatype corrections.

Further cleaning in Power BI Power Query:

# 🔍Removed 4 duplicate rows (from 10,004 to 10,000 rows).

# 🛠️Handled nulls, fixed errors, and corrected data types.

# ➕Added 2 new columns for better analysis.

# 🎯Main KPIs
Premium Amount

Coverage Amount

Claim Amount

# 🛠️Slicers Used
Policy Type

Claim Number

Customer ID

Policy Number

# 📈Key Visualizations & Insights
Claim Status Distribution

# 🍩Donut pie chart showing 43.54% claims rejected; remainder settled or pending.

Premium Amount by Policy Type

# 📊Bar chart shows highest premiums from Travel Insurance (~₹2.5M), followed by Health Insurance.

Age Group vs Claim Amount

# 👥Created Age Group column:

Young (18–30), Middle-aged (31–50), Senior (51–70), Elderly (71–90)

# 📉Line chart shows middle-aged group has highest claims (₹5.0M), followed by seniors (₹4.8M).

Policy Activity Status

# ⏳Based on policy dates as of 20-12-2024:

# 🟢55.47% active, 🔴 44.53% inactive (pie chart).

Gender Distribution

# 👩‍🦰👨Double row card shows equal split: 5,000 females and 5,000 males.

Policy Type vs Claim Status (Matrix Table)

# 📋Matrix compares rejected, settled, and pending claims:

❌ Most rejections & pendings: Travel Insurance

✅ Most settlements: Health Insurance

🏠 Least rejections, pendings, and settlements: Home Insurance

# 🛠️Tools Used
MS SQL Server – data cleaning & preprocessing

Power BI – data modeling & visualization

# 🎯Purpose
The primary objective of this project is to transform raw insurance data into clear, actionable insights that empower stakeholders to make data-driven decisions. By analyzing premiums, claims, and policy statuses, the project helps identify trends, detect inefficiencies, and highlight opportunities for improving customer service and operational effectiveness. This detailed analysis supports strategic planning, risk management, and enhances the overall understanding of insurance business dynamics, ultimately contributing to better policy management and increased profitability
