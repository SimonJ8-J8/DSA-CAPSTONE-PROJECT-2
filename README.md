# DSA-CAPSTONE-PROJECT-2

# 🏢 Palmoria Group Employee Bonus Analysis

This project analyzes employee data and applies bonus calculation rules based on department and performance rating. 

It provides insights into workforce structure, reward distribution, and data quality for strategic HR decision-making.

---

## 📦 Dataset Overview

### `emp-data.csv`

Includes:
- `Name`, `Gender`, `Department`, `Salary`, `Location`, `Rating`

### `Bonus Rules.xlsx

Bonus multiplier matrix based on:
- **Department** (rows)
- **Rating** (columns: Very Poor → Very Good)

---

## 🎯 Project Objectives

- Structure and clean HR employee data
- Apply bonus rules per department and performance rating
- Calculate total employee bonuses
- Analyze:
  - Bonus distribution across departments
  - Gender representation by role
  - Salary and rating patterns
- Generate business insights for performance-driven compensation

---

## 🧮 Bonus Calculation Logic

Each employee’s bonus is calculated with:

Bonus = Salary × Bonus Percentage

yaml
Copy
Edit

Bonus Percentage is looked up from a matrix using both `Department` and `Rating`.

> Example:  
> A Sales employee rated “Very Good” gets 8.8% of salary as bonus.

---

## 🔍 Key Findings


- **High performers (Very Good)** earn the most bonuses — up to **8.8%** of salary.
- **Sales** and **Engineering** receive the highest average bonuses due to larger team size.
- **Missing data**: Some records lack department or rating, impacting bonus eligibility.
- **Gender gap** in high-rating roles suggests an area for equity review.

---

## 📊 Suggested Visualizations


*To be created with Excel or Power BI:*

- 📊 Bar chart: Total bonuses by department
- 🧩 Heatmap: Bonus rate matrix
- 🧮 Histogram: Salary distribution
- 🧍 Pie chart: Gender distribution
- 📌 Stacked bar: Ratings by gender

---

## 💡 Business Recommendations


- 🎯 **Reward top talent:** Ensure fairness and visibility of bonus structure.
- 🧹 **Clean data gaps:** Address missing departments and ratings to improve analysis.
- ⚖️ **Close gender gaps:** Explore reasons for lower ratings in underrepresented groups.
- 📈 **Optimize bonus budget:** Focus incentives on high-value contributors.

---

## 🧰 Tools Used


| Tool       | Purpose                     |
|------------|-----------------------------|
| Excel      | Data entry, pivot tables, visualization |
| Power BI   | Dashboarding (optional)     |
| GitHub     | Version control & portfolio |

---

## 📁 Recommended Repository Structure


```plaintext
📦 palmoria-employee-bonus
├── data/
│   ├── Palmoria Group emp-data.csv
│   └── Palmoria Group Bonus Rules.xlsx
├── analysis/
│   └── bonus_calculator.xlsx (or .py)
├── visuals/
│   └── charts, graphs (optional)
├── README.md

### ✍️ Author

Simon Justice
Business Data Analyst
Skills: Excel • Power BI • SQL • Python

⭐ How to Use
Clone/download the project folder.

Open the Excel files under /data.

Apply bonus rules using VLOOKUP, INDEX-MATCH or Power BI model.

Customize visuals or add scripting as needed.

Upload the final project to GitHub or share as a portfolio asset.


# 🏢 Presentation Summary on Palmoria Group Employee Bonus Analysis


---

## 🎯 Executive Summary



This project analyzes employee data from Palmoria Group and applies department-specific bonus rules based on employee performance ratings. The analysis identifies disparities, reward trends, and opportunities for HR policy improvement using structured Excel-based calculations and insights.

---

## 📌 Project Objectives


- ✅ Clean and organize employee records
- 💰 Calculate individual bonuses based on department and rating
- 📊 Analyze reward distribution across departments
- ⚖️ Explore gender and performance equity
- 🧠 Recommend HR improvements for reward transparency

---

## 📁 Dataset Overview


### `emp-data.csv`


- `Name`, `Gender`, `Department`, `Salary`, `Location`, `Rating`

### `Bonus Rules.xlsx`


- Bonus percentages by **Department × Performance Rating**  
  *(Very Poor → Very Good)*

---

## 🧮 Bonus Calculation Logic



Each employee’s bonus is calculated with:

Bonus = Salary × Bonus Percentage

yaml
Copy
Edit

- Bonus % is derived from the matrix combining:
  - Department
  - Performance Rating

> Example: A “Very Good” employee in Sales earns a **8.8%** salary bonus.

---

## 📊 Key Findings


- 🎯 **High performers** (Very Good) earned the **largest share of bonuses**
- 📉 **Data gaps** found: Missing department or rating affected calculations
- 🧑‍🤝‍🧑 **Gender split** in top ratings favored male employees in technical roles
- 💼 **Support & Legal departments** had consistent bonus distributions

---

## 📈 Suggested Visuals


| Visual Type | Insight |
|-------------|---------|
| 📊 Bar Chart | Total bonus by department |
| 🧍 Pie Chart | Gender breakdown |
| 📉 Line Chart | Bonus-to-salary ratio trend |
| 🔥 Heatmap | Bonus matrix: Dept vs Rating |

---

## 💡 Business Recommendations


1. **Clean Data Regularly**  
   Ensure every employee has complete department & rating information.

2. **Promote Equity**  
   Investigate disparities in top ratings across gender or departments.

3. **Refine Bonus Policy**  
   Consider adjusting bonus rules to reflect modern performance metrics.

4. **Automate Bonus Calculations**  
   Reduce HR manual effort with structured Excel/Python workflows.

---

## 🧰 Tools Used


| Tool     | Purpose |
|----------|---------|
| Excel    | Bonus rules, data cleaning, PivotTables |
| Power BI | Visualization (optional) |
| Python   | Bonus automation (optional) |
| GitHub   | Version control & documentation |

---

## 📁 Repository Layout


```plaintext
📦 palmoria-employee-bonus
├── data/
│   ├── Palmoria Group emp-data.csv
│   └── Palmoria Group Bonus Rules.xlsx
├── analysis/
│   └── bonus_calculator.xlsx
├── visuals/
│   └── charts, graphs
├── README.md

### ✍️ Author
Dawat Ezra Simon

📌 Business Data Analyst
📊 Excel • Power BI • SQL • HR Analytics
