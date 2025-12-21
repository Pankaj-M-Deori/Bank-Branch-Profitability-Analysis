# BANK BRANCH PROFITABILITY ANALYSIS

## Project Overview
This project, **"Bank Branch Profitability Analysis"**, is a comprehensive Power BI analytics tool designed to assess the true financial health of a bank’s branch network. It moves beyond simple "Net Profit" to evaluate branches based on **Efficiency** and **Risk-Adjusted Return (RAR)**.

The primary goal was to answer: *"Which branches are truly adding value, and which are simply coasting on high revenue volume?"* The report provides a clear, data-driven narrative to help managers fix inefficient cost structures and replicate the success of top performers.

## Overall Bank Health (The "Headline" Numbers)
The bank's consolidated performance over the 3-year period appears strong at first glance:
* **Net Profit**: **$5.36 billion**
* **Profit Margin**: **33.10%**
* **Cost-to-Income Ratio**: **65.41%**

However, these headline numbers hide significant underlying risks, specifically regarding **Operational Inefficiency** in our largest regions and **Liquidity Risk** in our most profitable branches.

<p align="center"> 
<img width="921" height="509" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/eae48e73-d3f4-49e9-96a3-df46059d7565" />
</p>


## Core Finding #1: Big Revenue vs. Real Quality
**The Deception of Scale:** The **Overview Dashboard** reveals that "Bigger" does not mean "Better."
* **The East Region** is our largest engine, generating **$5.3 billion** in revenue.
* However, the **Branch Ranking Table** shows that the East is **not** the home of our best performers. Top branches based on **Risk-Adjusted Return (RAR)** are actually in **Houston (South)** and **Washington (Central)**.
* **Inefficiency Map:** The map visual confirms this by showing "Red Zones" (low profit margins) clustered in our biggest cities. We are making money simply because we have a massive volume of customers, not because we are running efficiently.

## Core Finding #2: The Cost Trap (Profitability)
**Our Costs Are Too Rigid:** The **Profitability Analysis** diagnoses why our profits are squeezed during downturns.

<p align="center">
<img width="917" height="508" alt="Profitability View" src="https://github.com/user-attachments/assets/be33ef03-f73c-4329-b7bc-5bcd82807749" />
</p>

* **90% Fixed Costs:** The Expense Breakdown shows that **90.15%** of our operating costs are fixed: **Salaries (60.16%)** and **Rent (29.99%)**.
* **The Inflexibility Problem:** The "Revenue vs. Cost Growth" chart shows that in **Q4 2024**, revenue growth dropped, but cost growth stayed high. Because we couldn't cut salaries or rent fast enough to match the drop in sales, our profit margin was squeezed. This proves the bank lacks the flexibility to handle bad economic times.

## Core Finding #3: The Hidden Risk (Loan Performance)
**Profitable but Risky:** The **Loan Performance** view reveals a major trade-off between profit and safety.

<p align="center">
<img width="916" height="509" alt="Loan Performance View" src="https://github.com/user-attachments/assets/a1351595-7873-453b-ad8d-d5eb75e9ae46" />
</p>

* **Aggressive Lending:** Our #1 branch, **Houston (Branch 6016)**, has a Loan-to-Deposit Ratio (LDR) of **82.17%**. This is significantly higher than the bank average of **67%**.
* **Liquidity Warning:** While this aggressive lending drives Houston's high profit, it creates a **Liquidity Risk**. An LDR of 82% means the branch has lent out almost all its cash. If depositors suddenly withdraw funds, this branch—our "best" performer—would face an immediate cash crisis.

## Core Finding #4: The Efficiency Gap (Regional Scorecard)
**The Model Zone vs. The Risk Zone:** The **Regional Ranking** view compares our regions to find the best operational model.

<p align="center">
  <img width="916" height="510" alt="Regional Ranking View" src="https://github.com/user-attachments/assets/54849a2f-6314-4f63-96f9-1786fee974fa" />
</p>

* **The Risk Zone (East):** The Scatter Plot shows the East region high on the "Volatility" axis. It generates high profit ($1.74bn) but with the highest instability ($17.66M volatility).
* **The Model Zone (South):** The South region sits in the "sweet spot." It delivers stable returns with lower costs. The scorecard proves the South is our most efficient region (**63.10% Cost-to-Income**), making it the model we should replicate.

## Core Finding #5: Future Vulnerability (What-If Analysis)
**A Double-Edged Sword:** The **What-If Simulation** reveals our sensitivity to external factors.

<p align="center">
  <img width="923" height="507" alt="NII Impact View" src="https://github.com/user-attachments/assets/250122a9-c9bb-4a56-8736-f93fb75df07f" />
</p>

* **High Sensitivity:** Simulating a **+1% interest rate hike** boosts our Profit Margin from 33% to nearly **40%**, adding **$1.8 billion** to Net Interest Income.
* **The Danger:** While a rate hike helps us, this proves we are overly reliant on favorable rates. If rates were to **drop** by 1%, we would lose that same massive amount of profit.
* **Vulnerable Branches:** The "Top 10 Impacted Branches" list shows that our inefficient branches (like **Branch 6006**) are the most exposed. They have such thin margins that a rate drop could instantly push them into unprofitability.

<p align="center">
<img width="919" height="507" alt="Margin Impact View" src="https://github.com/user-attachments/assets/2efde297-c733-4d6b-baf5-da1e3c7f00d5" />
</p>

## Strategic Recommendations
Based on these data-driven findings, the following actions are recommended:

1.  **Replicate the "Houston" Blueprint**: Target a reduction in peer **Cost-to-Income ratios towards 55%** by adopting the operational efficiency model of Branch 6016.
2.  **Variable Pay Structure**: Introduce performance-based bonuses to convert some fixed Salary costs into variable costs. This ensures expenses drop when revenue drops.
3.  **Operational Audit for "Bottom 10"**: Conduct immediate reviews of the Bottom 10 branches (specifically in the West and North) for potential downsizing to reduce the fixed Rent burden.
4.  **Liquidity Safety Net**: Implement an automated monitoring system to flag branches with **LDR > 75%** (like Houston) to ensure they maintain sufficient cash reserves.

## Interactive Report Features
The report was designed to be a fully interactive tool for analysts and managers:

- **Sync-Slicers**: Year, Region, and State slicers work across all pages.
- **Page Navigator**: Easy movement between the three core analysis pages.
- **Bookmarks**: Clickable tabs to switch between views (e.g., "Profitability" vs "Loan Performance").
- **Drill-through**: Right-click functionality to jump to a "Branch Details" page for specific peer-to-peer comparison.
- **Drill-down**: Time-series charts allow viewing data by Year, Quarter, or Month.
- **What-If Parameter**: A slider to simulate interest rate shocks in real-time.

## Tools and Skills Used

- **Tools**: Power BI Desktop, DAX, Power Query (M), Excel.
- **Skills**: Data Modeling (Star Schema), Advanced DAX (Time Intelligence, Ranking), What-if Scenarios, KPI Development, Data Storytelling.

## Resources and Links

- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Bank_Profitability_Project_Dataset.xlsx">Bank Branch Profitability Dataset
- <a href="https://app.powerbi.com/links/X0RdC87_Bd?ctid=7f2cea9c-d8e4-4c74-a024-cb436d9ecfd5&pbi_source=linkShare">Interactive Report (Power BI Service)
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Executive%20Summary.pdf">Executive Summary: Findings & Insights
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Technical%20Documentation.pdf">Technical Documentation
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Model%20ER%20Diagram.PNG">Model ER Diagram (Data Model)
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Bank%20Branch%20Profitability%20Analysis.pbix">Bank Branch Profitability Analysis (.pbix file)
