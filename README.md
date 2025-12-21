# BANK BRANCH PROFITABILITY ANALYSIS

## Project Overview
This project is a complete Power BI analysis tool designed to check the true health of a bank’s branch network. It moves beyond simple "Net Profit" numbers to evaluate branches based on **Efficiency** and **Risk-Adjusted Return (RAR)**.

The main goal of this report is to answer: *"Which branches are truly helpful to the business, and which ones are risky or inefficient?"* It helps managers identify "at-risk" branches and find the best operational models to copy across the network.

## Overall Bank Health
At first glance, the bank looks very healthy over the last 3 years:
* [cite_start]**Total Net Profit**: **$5.36 billion** [cite: 3]
* [cite_start]**Profit Margin**: **33.10%** [cite: 5]
* [cite_start]**Cost-to-Income Ratio**: **65.41%** [cite: 10]

However, these big numbers hide significant risks, specifically regarding **operational waste** in our largest regions and **cash safety risks** in our most profitable branches.

<p align="center"> 
<img width="921" height="509" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/eae48e73-d3f4-49e9-96a3-df46059d7565" />
</p>

---

## 1. Overview Dashboard: Big Revenue vs. Real Quality
**The Story:** "Bigger" does not always mean "Better."

* [cite_start]**The Deception of Scale:** The **East Region** is our biggest engine, bringing in **$5.3 billion** in revenue[cite: 55, 56]. However, the ranking table shows that the East is **not** home to our best performers.
* [cite_start]**True Quality:** The top branches based on **Risk-Adjusted Return (RAR)** are actually in **Houston (South)** and **Washington (Central)**, which have RAR scores over **100%**[cite: 32, 41].
* [cite_start]**Inefficiency Map:** The map visual confirms this by showing "Red Zones" (low profit margins) clustered in our biggest, busiest cities[cite: 17]. We are making money simply because we have a huge volume of customers, not because we are running efficiently.

---

## 2. Profitability Analysis: The Cost Trap
**The Story:** Our costs are too rigid, making us vulnerable during bad times.

<p align="center">
<img width="917" height="508" alt="Profitability View" src="https://github.com/user-attachments/assets/be33ef03-f73c-4329-b7bc-5bcd82807749" />
</p>

* **90% Fixed Costs:** The Expense Breakdown shows that **90.15%** of our operating costs are fixed. [cite_start]We spend **60.16%** on Salaries and **29.99%** on Rent[cite: 120, 127].
* **We Lack Flexibility:** The "Revenue vs. Cost Growth" chart shows the danger of this. [cite_start]In **Q4 2024**, our revenue growth dropped, but our cost growth stayed high[cite: 130]. Because we couldn't cut salaries or rent fast enough to match the drop in sales, our profit margin was squeezed. This proves the bank cannot easily adjust to economic downturns.

---

## 3. Loan Performance: The Hidden Risk
**The Story:** Our most profitable branches are running on the edge.

<p align="center">
<img width="916" height="509" alt="Loan Performance View" src="https://github.com/user-attachments/assets/a1351595-7873-453b-ad8d-d5eb75e9ae46" />
</p>

* [cite_start]**Aggressive Lending:** Our #1 performing branch, **Houston (Branch 6016)**, has a Loan-to-Deposit Ratio (LDR) of **82.17%**[cite: 30]. [cite_start]This is much higher than the bank average of **67%**[cite: 8].
* **Liquidity Warning:** While this high lending explains why Houston makes so much profit, it creates a **Liquidity Risk**. An LDR of 82% means the branch has lent out almost all the cash it has. [cite_start]If depositors suddenly withdraw funds, this branch—our "best" performer—would face an immediate cash crisis[cite: 425].

---

## 4. Regional Ranking: The Efficiency Gap
**The Story:** Comparing the "Risk Zone" vs. the "Model Zone."

<p align="center">
  <img width="916" height="510" alt="Regional Ranking View" src="https://github.com/user-attachments/assets/54849a2f-6314-4f63-96f9-1786fee974fa" />
</p>

* **The Risk Zone (East):** The Scatter Plot shows the East region high on the "Volatility" axis. [cite_start]It generates high profit ($1.74bn) but with the highest instability ($17.66M volatility)[cite: 392].
* **The Model Zone (South):** The South region sits in the "sweet spot." It delivers stable returns with lower costs. [cite_start]The scorecard proves the South is our most efficient region (**63.10% Cost-to-Income**), making it the model we should replicate[cite: 392].

---

## 5. What-If Analysis: Future Vulnerability
**The Story:** We are lucky... for now.

<p align="center">
  <img width="923" height="507" alt="NII Impact View" src="https://github.com/user-attachments/assets/250122a9-c9bb-4a56-8736-f93fb75df07f" />
</p>

* [cite_start]**High Sensitivity:** Simulating a **+1% interest rate hike** boosts our Profit Margin from 33% to nearly **40%**, adding **$1.8 billion** to Net Interest Income[cite: 148, 153].
* **The Danger:** While a rate hike helps us, this proves we are overly reliant on high interest rates. If rates were to **drop** by 1%, we would lose that same massive amount of profit.
* **Vulnerable Branches:** The "Top 10 Impacted Branches" list shows that our inefficient branches (like **Branch 6006**) are the most exposed. [cite_start]They have such thin margins that a rate drop could instantly push them into losing money[cite: 201].

<p align="center">
<img width="919" height="507" alt="Margin Impact View" src="https://github.com/user-attachments/assets/2efde297-c733-4d6b-baf5-da1e3c7f00d5" />
</p>

---

## Strategic Recommendations
Based on these findings, we recommend the following actions:

1.  **Replicate the "Houston" Blueprint**: Lower costs. [cite_start]Target a **Cost-to-Income ratio of 55%** by copying the efficient operations of Branch 6016[cite: 448].
2.  **Variable Pay Structure**: Change how we pay bonuses. [cite_start]Make a portion of salaries "variable" so that when revenue drops, our expenses drop too[cite: 449].
3.  [cite_start]**Review the "Bottom 10"**: Audit the bottom 10 branches (mostly in the West and North) to see if we should close them or shrink their office space to save rent money[cite: 451].
4.  [cite_start]**Liquidity Safety Net**: Set up an automatic alert for any branch with an **LDR over 75%** (like Houston) to make sure they don't run out of cash[cite: 453].

## Tools and Skills Used
* **Tools**: Power BI Desktop, DAX, Power Query (M), Excel.
* **Skills**: Data Modeling (Star Schema), Advanced DAX (Time Intelligence, Ranking), What-if Scenarios, KPI Development, Data Storytelling.

## Interactive Report Features
* **Sync-Slicers**: Filter by Year, Region, and State across all pages at once.
* **Page Navigator**: Easily switch between the three main analysis pages.
* **Drill-through**: Right-click any branch to see a detailed "Report Card" comparing it to its neighbors.
* **What-If Slider**: A tool to simulate interest rate shocks in real-time.

## Resources and Links
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Bank_Profitability_Project_Dataset.xlsx">Bank Branch Profitability Dataset
- <a href="https://app.powerbi.com/links/X0RdC87_Bd?ctid=7f2cea9c-d8e4-4c74-a024-cb436d9ecfd5&pbi_source=linkShare">Interactive Report (Power BI Service)
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Executive%20Summary.pdf">Executive Summary: Findings & Insights
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Technical%20Documentation.pdf">Technical Documentation
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Model%20ER%20Diagram.PNG">Model ER Diagram (Data Model)
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Bank%20Branch%20Profitability%20Analysis.pbix">Bank Branch Profitability Analysis (.pbix file)
