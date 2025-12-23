# BANK BRANCH PROFITABILITY ANALYSIS

## Project Overview
This project is a complete Power BI analysis tool designed to check the true health of a bank’s branch network. While many reports only look at "Net Profit," this project goes deeper. It evaluates branches based on **Efficiency** (how much it costs to make a dollar) and **Risk-Adjusted Return (RAR)** (how stable the profit is over time).

The main goal of this report is to answer the critical question: *"Which branches are truly helpful to the business, and which ones are risky or inefficient?"* It helps managers identify "at-risk" branches that are hiding behind big revenue numbers and find the best operational models to copy across the network.

## Overall Bank Health (The "Headline" Numbers)
The bank's consolidated performance over the 3-year period appears strong at first glance:
* **Total Net Profit**: **$5.36 billion** 
* **Profit Margin**: **33.10%** 
* **Cost-to-Income Ratio**: **65.41%** (For every $1 earned, we spend nearly 65 cents) 
* **Loan-to-Deposit Ratio**: **67.73%** 

However, these headline numbers hide significant underlying risks, specifically regarding **Operational Inefficiency** in our largest regions and **Liquidity Risk** in our most profitable branches.

<p align="center"> 
<img width="898" height="508" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/5da30d7d-1f9e-4992-8cd1-957a12b86bda" />
</p>


## Core Finding #1: Big Revenue vs. Real Quality
**The Story:** "Bigger" does not always mean "Better." We found that our total revenue is driven by the **size of our network**, not the **quality of our operations**.

* **Quantity vs. Quality:** Even though the East is our largest market holding **13 of our 40 branches** and generating **$5.3bn** in revenue, but it is not home to our best performers. The ranking table reveals that our top-tier branches are actually found in smaller regions: **Houston (South)** leads with a **111.39%** Risk-Adjusted Return, followed by **Washington (Central)** at **108.62%**. This proves that having the biggest network does not guarantee the smartest or most profitable business.
* **True Quality:** Real success is found in the **South Region**, which achieves better results with fewer branches (only 8). Its top branch, **Houston (Branch 6016)**, delivers a massive RAR score of **111.39%** and a Profit Margin of **43.79%**. This branch proves that a lean, efficient operation is worth more than a large, inefficient network.
* **Inefficiency Map:** The map visual exposes the truth behind the revenue numbers. It highlights several states in "Red" (Bottom 25% Profit Margin). This visually confirms that while these regions contribute to the bank's total revenue bucket, they are actually operating at very thin, inefficient margins.

## Core Finding #2: The Cost Trap (Profitability)
**The Story:** Our costs are too rigid (fixed), making us vulnerable when the economy slows down.

<p align="center">
<img width="899" height="506" alt="Profitability" src="https://github.com/user-attachments/assets/c2241bca-a635-4223-95b6-c09adafd6faf" />
</p>

* **90% Fixed Costs:** The Operating Expense Breakdown reveals a structural weakness: **90.15%** of our costs are fixed. We spend **$6.38 billion (60.16%)** on Salaries and **$3.18 billion (29.99%)** on Rent. These are bills we have to pay every month, no matter how much money we make.
* **We Lack Flexibility:** The "Revenue Growth vs. Cost Growth" chart shows the danger of this. In **Q1 2025 and Q3 2025**, our revenue growth dropped, but our cost growth stayed high. Because we couldn't cut salaries or rent fast enough to match the drop in sales, our profit margin was squeezed. This proves the bank cannot easily adjust to economic downturns.

## Core Finding #3: The Hidden Risk (Loan Performance)
**The Story:** The **Loan Performance** view reveals a major trade-off between profit and safety.

<p align="center">
<img width="897" height="509" alt="Loan Performance" src="https://github.com/user-attachments/assets/d9bb8ca4-a737-4833-a1c2-c2537feadb0b" />
</p>

* **Aggressive Lending:** Our #1 branch, **Houston (Branch 6016)**, has a Loan-to-Deposit Ratio (LDR) of **82.17%**. This is significantly higher than the bank average of **67%**.
* **Strategy Correlates with Success**: This aggressive strategy is directly linked to performance across the board. The data shows that **7 out of the Top 10 branches by LDR** are also ranked in the **Top 10 for Risk-Adjusted Return (RAR)**. Conversely, **6 out of the Bottom 10 branches by LDR** are ranked in the **Bottom 10 for RAR**. This proves that being too conservative with lending is a major driver of poor performance.
* **Liquidity Warning:** While this aggressive lending drives Houston's high profit, it creates a **Liquidity Risk**. An LDR of 82% means the branch has lent out almost all its cash. If depositors suddenly withdraw funds, this branch which is also our "best" performer would face an immediate cash crisis.

## Core Finding #4: The Efficiency Gap (Regional Scorecard)
**The Story:** The **Regional Ranking** view compares our regions to find the best operational model.

<p align="center">
<img width="894" height="511" alt="Regional Ranking" src="https://github.com/user-attachments/assets/5479f432-3fe0-412d-a670-c2769316328a" />
</p>

* **The Risk Zone (East):** The Scatter Plot places the East region high on the "Volatility" axis. It generates high profit ($1.74bn), but it is unstable, with the highest profit volatility of **$17.66M**. It effectively makes money by brute force (size), not skill.
* **The Model Zone (South):** The South region sits in the "sweet spot." It delivers stable returns with lower costs. The scorecard proves the South is our most efficient region with a **Cost-to-Income ratio of 63.10%** (compared to the East's 65.59%).
* **The Problem Zone (West):** The West region is struggling operationally. It generates low profit ($0.74bn) relative to the risk it takes, with a low Risk-Adjusted Return of **23.34%**.

## Core Finding #5: Future Vulnerability (What-If Analysis)
**The Story:** The **What-If Simulation** reveals our sensitivity to external factors.

<p align="center">
<img width="897" height="507" alt="NII Impact" src="https://github.com/user-attachments/assets/868d9da7-d04f-4154-a2a4-cfba7620fa88" />
</p>

* **High Sensitivity:** Our simulation shows that if interest rates go up by just **+1%**, our Profit Margin would jump from 33% to nearly **40%**, adding **$1.8 billion** to our Net Interest Income.
* **The Danger:** While a rate hike helps us, this proves we are overly reliant on external factors. If rates were to **drop** by 1%, we would lose that same massive amount of profit.
* **Vulnerable Branches:** The "Top 10 Impacted Branches" list shows that our inefficient branches are the most exposed. For example, **Branch 6006 (Philadelphia)**, which has a massive Cost-to-Income ratio of **84.92%**, would see its margin impacted by over **9%**. These branches have such thin margins that a rate drop could instantly push them into losing money.

<p align="center">
<img width="898" height="506" alt="Margin Impact" src="https://github.com/user-attachments/assets/9960da2c-2dc2-44b9-a74c-1d1d82410ec2" />
</p>

## Strategic Recommendations
Based on these data-driven findings, the following actions are recommended:

1.  **Replicate the "Houston" Blueprint**: Target a reduction in peer **Cost-to-Income ratios towards 55%** by adopting the operational efficiency model of Branch 6016.
2.  **Variable Pay Structure**: Introduce performance-based bonuses to convert some fixed Salary costs into variable costs. This ensures expenses drop when revenue drops.
3.  **Operational Audit for "Bottom 10"**: Conduct immediate reviews of the Bottom 10 branches (specifically in the West and North) for potential downsizing or closure to reduce the fixed Rent burden.
4.  **Liquidity Safety Net**: Implement an automated monitoring system (Power BI Service Alert) to flag branches with **LDR > 75%** (like Houston) to ensure they maintain sufficient cash reserves.

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

- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/Bank_Profitability_Project_Dataset.xlsx">Bank Branch Profitability Dataset
- <a href="https://app.powerbi.com/links/X0RdC87_Bd?ctid=7f2cea9c-d8e4-4c74-a024-cb436d9ecfd5&pbi_source=linkShare">Interactive Report (Power BI Service)
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/Bank%20Branch%20Profitability%20Analysis%20Report.pdf">Power BI Report PDF
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/Executive%20Summary.pdf">Executive Summary: Findings & Insights
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/Technical%20Documentation.pdf">Technical Documentation
- <a href="https://github.com/sure-trust/PANKAJ-MACHIYA-DEORI-g20-sql-and-powebi/blob/main/Final%20capstone%20project/Bank%20Branch%20Profitability%20Analysis/Model%20ER%20Diagram.PNG">Model ER Diagram (Data Model)
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/Bank%20Branch%20Profitability%20Analysis.pbix">Bank Branch Profitability Analysis (.pbix file)
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability Analysis/blob/main/Bank%20Branch%20Profitability%20Analysis%20Presentation.pdf">Project Presentation
- <a href="https://github.com/Pankaj-M-Deori/Bank-Branch-Profitability-Analysis/blob/main/SURE%20ProED%20Project%20Report.pdf">SURE ProED Project Report
