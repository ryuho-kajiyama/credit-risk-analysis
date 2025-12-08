## 📌 Credit Risk Analysis Dashboard
Exploring financial, demographic and behavioral factors that influence loan default risk using Python and Looker Studio.

## 🧾 1. Project Overview
This project analyzes borrower data to identify patterns associated with loan default risk.

Using:
- **Python (Pandas)** for data exploration and cleaning
- **Looker Studio** for interactive dashboard visualizations
- **Kaggle Notebook** for code and documentation

The goal is to answer key questions related to loan risk, such as:
- How do income levels affect default risk?
- Does Debt-to-Income (DTI) ratio correlate with default?
- How does home ownership relate to repayment behavior?

This project reflects my background as a **loan officer** and my developing skills in **data analytics.**

## 📊 2. Dataset
**Source:** Kaggle – Credit Risk Dataset\
**Original Size:** 32,581 rows, 12 columns\
**Final Size After Cleaning:** 32,409 rows, 12 columns\
**Target Variable:** default (0 = no default, 1 = default)

Key features include:
- **Income**
- **Debt-to-Income Ratio (DTI)**
- **Home ownership**
- **Employment Length**
- **Age**

## 🧹 3. Data Cleaning
Main cleaning steps:
- Removed duplicate rows and rows with invalid values
- Filled missing values using median
- Created income and DTI groups for analysis
- Ensured dataset consistency before visualization

## 🔍 4. Exploratory Analysis
I explored several questions to understand risk drivers:
1. Are lower-income borrowers more likely to default?
- Income was grouped into 4 ranges.
- Default risk was highest in the lowest income group.
2. Do higher DTI ratios correlate with increased risk?
- Borrowers were divided into three DTI groups: [0-0.3), [0.3-0.6), [0.6-1.0).
- Higher DTI correlates with increased default risk. 
3. Does home ownership status relate to default risk?
- Categories: OWN, MORTGAGE, RENT, OTHER.
- Renters and ‘OTHER’ borrowers showed higher default risk than other categories.
4. How does age relate to default risk?
-  Age was grouped into three segments: [20-40), [40-60), [60-100).
- Older borrowers showed a slightly higher likelihood of default.

## 📈 5. Key Performance Indicators (KPIs)
The dashboard highlights these KPIs:
- **Overall Default Rate:** 21.82%
- **Average Income:** $66.07K
- **Average DTI:** 17.02%

These KPIs help assess the general risk level of the loan portfolio.

## 📊 6. Dashboard (Looker Studio)
The final dashboard includes:
#### ✔️ **Default Rate by Income Group**
#### ✔️ **Default Rate by DTI Group**
#### ✔️ **Default Rate by Home Ownership**
#### ✔️ **Filters for deep exploration (Age Group, Loan Intent)**

#### 📸 Dashboard Screenshots:
![Dashboard Preview](dashboard_1.png)
![Dashboard Preview 2](dashboard_2.png)

## 🧠 7. Insights
- Lower income borrowers appear more vulnerable to default.
- Borrowers with DTI ratios above 0.3 show significantly higher default rates.
- Renters tend to default more frequently than homeowners.

## 🧰 8. Tools Used
- Python (Pandas, NumPy)
- Looker Studio
- Kaggle Notebook
- GitHub

## 🚀 9. How to Reproduce
1. Download the dataset from Kaggle
2. Open the Jupyter/Kaggle notebook
3. Run all cells to generate the cleaned dataset
4. Upload the dataset into Looker Studio
5. Rebuild the dashboard using the KPIs and charts

## 📌 10. Next Steps
- Build a predictive model for default risk
- Add credit history features
- Improve dashboard formatting

👨‍💻 *Created by: Ryuho Kajiyama
📍 Netherlands | 📧 Kumagorou.ryuho@gmail.com | 🔗 [GitHub: https://github.com/ryuho-kajiyama / LinkedIn: https://www.linkedin.com/in/ryuho-kajiyama-979205362/]
