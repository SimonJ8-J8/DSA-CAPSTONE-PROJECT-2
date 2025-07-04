# DSA-CAPSTONE-PROJECT-2

# 🏢 Palmoria Group Employee Bonus Analysis

This project analyzes employee data and applies bonus calculation rules based on department and performance rating. 

It provides insights into workforce structure, reward distribution, and data quality for strategic HR decision-making.

---

## 📦 Dataset Overview

### `emp-data.csv`
Includes:
- `Name`, `Gender`, `Department`, `Salary`, `Location`, `Rating`

### `Bonus Rules.xlsx`
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
✍️ Author
Simon Justice
Business Data Analyst
Skills: Excel • Power BI • SQL • Python

⭐ How to Use
Clone/download the project folder.

Open the Excel files under /data.

Apply bonus rules using VLOOKUP, INDEX-MATCH or Power BI model.

Customize visuals or add scripting as needed.

Upload the final project to GitHub or share as a portfolio asset.
