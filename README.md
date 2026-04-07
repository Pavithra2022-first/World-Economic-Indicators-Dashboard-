🌍 Global Economic Indicator Analysis – World_Bank_data(2010-2025) 

📌 Project Overview

This project analyzes global economic indicators using real-world data from the World Bank. The focus is on understanding trends in GDP, Tax Revenue, Inflation, and Economic Growth across multiple countries from 2010 to 2025.

The project combines Excel (data cleaning & preprocessing) and Power BI (data visualization & dashboarding) to build an interactive and insightful analytical solution.
________________________________________
🎯 Objectives

•	Analyze global GDP trends across countries and years

•	Identify top-performing economies based on GDP

•	Compare GDP Growth vs Inflation (GDP Deflator)

•	Evaluate Government Revenue vs Government Expenditure

•	Understand tax revenue patterns as % of GDP

•	Perform data cleaning and transformation in Excel

•	Handle missing values using imputation techniques (interpolation & averaging)

•	Build interactive dashboards using Power BI

•	Apply DAX functions for KPI creation and analysis

•	Develop data storytelling and visualization skills
________________________________________
📂 Dataset Description

The dataset is sourced from World Bank data and includes:

•	Country Name – List of countries analyzed

•	Year (2010–2025) – Time dimension

•	GDP (Current USD) – Total economic output

•	GDP Growth (% Annual) – Year-over-year growth

•	Tax Revenue (% of GDP) – Government tax contribution

•	Inflation (CPI & GDP Deflator %) – Price level changes

•	Government Revenue & Expenditure – Fiscal indicators

•	GNI & GDP per Capita – Income-related metrics
________________________________________
🛠 Tools & Technologies

•	Excel – Data cleaning, preprocessing, and imputation

•	Power BI – Dashboard creation and visualization

•	DAX (Data Analysis Expressions) – KPI calculations

•	CSV Dataset – Data storage
________________________________________
🧹 Data Cleaning & Preprocessing (Excel)

Data preparation was performed in Excel before visualization:

•	Removed columns with high missing values (e.g., Public Debt)

•	Handled missing values using:

o	Interpolation (for short gaps)

o	Average-based imputation (for large gaps)

•	Fixed data type inconsistencies (text → numeric)

•	Removed duplicate and unnecessary columns

•	Standardized and structured data for analysis

•	Ensured time-series consistency (year-wise data)
________________________________________
📊 Dashboard Features

🔝 KPI Indicators

•	Total GDP

•	GDP Growth (%)

•	Average Tax Revenue (%)

•	Inflation Metrics
________________________________________
📈 Visualizations

•	Top 10 Countries by GDP – Identifies leading economies

•	GDP Growth vs Inflation – Economic stability analysis

•	Government Revenue vs Expenditure – Fiscal comparison

•	GDP Trend Over Time – Growth pattern visualization

•	GDP per Capita vs GNI – Income distribution insights
________________________________________
🎛 Interactive Elements

•	Year filter (2010–2025)

•	Country-level filtering

•	Dynamic and responsive visuals
________________________________________
📌 DAX Measures Used

Total GDP = SUM('Table'[GDP])

Avg Tax % = AVERAGE('Table'[Tax Revenue (% of GDP)])

GDP Growth % = 
DIVIDE(
    SUM('Table'[GDP]) - 
    CALCULATE(SUM('Table'[GDP]), PREVIOUSYEAR('Table'[Year])),
    CALCULATE(SUM('Table'[GDP]), PREVIOUSYEAR('Table'[Year]))
) * 100
________________________________________
📈 Key Insights

•	The United States and China dominate global GDP rankings

•	GDP shows a steady upward trend globally

•	Inflation and GDP growth show cyclical fluctuations

•	Government revenue and expenditure follow similar patterns

•	Tax revenue remains relatively stable as % of GDP
________________________________________
🎓 Learning Outcomes

•	Hands-on experience with real-world economic datasets

•	Strong understanding of data cleaning in Excel

•	Practical application of missing value imputation techniques

•	Improved skills in DAX and Power BI

•	Ability to create interactive and insightful dashboards
________________________________________
👩‍💻 Author

Pavithra E

Aspiring Data Analyst
