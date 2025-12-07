## 📌 Credit Risk Analysis Dashboard
Exploring financial, demographic and behavioral factors that influence loan default risk using Python and Looker Studio.

## 🧾 1. Project Overview
This project analyzes borrower data to identify patterns associated with loan default risk.

Using:
- **Python (Pandas)** for data exploring and cleaning
- **Looker Studio for** for interactive dashboard visualizations
- **Kaggle Notebook** for code and documentation

The goal is to answer key questions related to loan risk, such as:
- How do income levels affect default risk?
- Does Debt-to-Income (DTI) ratio correlate with default?
- How does home ownership relate to repayment behavior?

This project reflects my backgroud as a **loan officer** and my developing skills in **data analytics.**

## 📊 2. Dataset
**Source:** Kaggle – Credit Risk Dataset\
**Data Size**\
Original Size: 32,581 rows, 12 columns\
Final Size: 32,409 rows, 12 columns 
**Target Variable:** Default (0 = no default, 1 = default)

Key features include:
- Income
- Debt-to-income Ratio (DTI)
- Home ownership
- Age
- Employment Length

## 🧹 3. Data Cleaning
Main cleaning steps:
- Removed duplicate rows and rows which included invalid values
- Filled missing values with median
- Created income and DTI groups for analysis
- Ensured dataset consistancy before visualization

## 🔍 4. Exploratory Analysis
I explored several questions to understand risk drivers:
1. Are lower-income borrowers more likely to default?
- I grouped the data by 4 age groups: [0:1e4), [1e4:1e5), [1e5:1e6), [1e6:1e7).
- The lowest income group is the most likely to default.
2. Do higher DTI ratios correlate with increased risk?
- I divided the data into 3 groups: [0:0.3), [0.3:0.6), [0.6:1.0)
- The higher DTI ratios are, the more people default.
3. Does home ownership status relate to default risk?
- There are 4 categories: OWN, MORTGAGE, RENT, OTHER.
- People in the RENT category and OTHER category are more likely to default than in other categories.
4. How does age relate to default risk?
-  I grouped the data by 3 age groups: [20:40), [40:60), [60:100).
-  The oldest group are more likely to default than other groups.
-  However, the number of data in the category is wey less than other groups.

## 📈 5. Key Performance Indicators (KPIs)
The dashboard hilights these KPIs:
- Overall Default Rate: 21.82%
- Average Income: $66.07K
- Average DTI: 17.02%

These KPIs help assess the general risk level of the loan portfolio.

## 📊 6. Dashboard (Looker Studio)
The Final dashboard includes:
#### ✔️ **Default Rate by Income Group**
#### ✔️ **Default Rate by DTI group**
#### ✔️ **Default Rate by Home Ownership**
#### ✔️ **Filters for deep exploration (Age Group, Loan Intent)**

#### 📸 Dashboard Screenshots:
![Dashboard Preview]()
![Dashboard Preview 2]()

## 🧠 7. Insights


## 🧰 8. Tools Used
- Python (Pandas, NumPy)
- Looker Studio
- Kaggle Notebook
- GitHub

## 🚀 9. How to Reproduce
1. Download the dataset frome Kaggle
2. Open the Jupyter/Kaggle notebook
3. Run all cells generated the cleaned dataset
4. Uproad into Looker Studio
5. Rebuild the dashboard using the KPIs and charts

## 📌 10. Next Steps
- Build a predictive model for default risk
- Add credit history features
- Improve dashboard formatting
