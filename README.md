# Bank Loan Report -- Interactive Excel Dashboard

## Project Overview

This project presents a **comprehensive interactive Excel dashboard**
for analyzing bank loan applications, funding, and repayment
performance. Using a dataset of over **95,000+ loan records**, the
report provides insights into loan trends, funding amounts, repayment
behavior, and customer profiles. The dashboards feature **switch
buttons, slicers, and navigation controls** for seamless exploration.

------------------------------------------------------------------------

## Data Preparation

-   Collected and reviewed a large dataset (95k+ rows) of bank loan
    applications with details such as funded amounts, received amounts,
    interest rates, terms, purposes, and customer profiles.\
-   Cleaned and structured the dataset to remove inconsistencies,
    duplicates, and missing values.\
-   Connected data to **MS SQL Server** for advanced querying; also
    provided CSV connectivity for users without server access.

------------------------------------------------------------------------

## Dashboard Development Process

1.  **Primary KPI Design**
    -   Designed KPIs for **total loan applications, funded amount,
        amount received, average interest rate, and average DTI
        (Debt-to-Income ratio)**.\
    -   Added **month-over-month growth metrics** to track performance
        trends.
2.  **Dashboard Layout & Visualization**
    -   Built a clean layout separating summary metrics, state-level
        breakdowns, term distribution, and borrower profiles.\
    -   Created **interactive charts** for loan applications by month,
        state, employee length, purpose, and home ownership.
3.  **Adding Primary KPI to Dashboard**
    -   Positioned key KPIs at the top for immediate visibility.\
    -   Used color coding to highlight performance changes.
4.  **Secondary KPI Design & Integration**
    -   Designed KPIs to separate **Good Loans vs Bad Loans** (fully
        paid vs charged-off loans).\
    -   Created visual blocks to display **funded amount, amount
        received, and interest rates by loan status**.
5.  **Loan Status KPI Chart**
    -   Added pie and bar charts to clearly differentiate good vs bad
        loan percentages and totals.
6.  **Charts & Interactivity**
    -   Implemented dynamic slicers for **loan grade, loan purpose, and
        term**.\
    -   Added **switch buttons** and navigation controls to toggle
        between dashboards.\
    -   Used conditional formatting to highlight critical insights.

------------------------------------------------------------------------

## Final Dashboards

### **1. Overview Dashboard**

![Overview Dashboard](overviewdasboard.PNG)

### **2. Summary Dashboard**

(summarydashboard.PNG)

------------------------------------------------------------------------

## Key Insights

-   **38.6k total loan applications**, with consistent month-over-month
    growth (\~6.9%).\
-   **\$435.8M total funded amount** and **\$473.1M amount received**
    indicate strong repayment performance.\
-   **Good Loans:** 86.18% of applications are fully paid, totaling
    **\$370.2M funded** and **\$435.8M received**.\
-   **Bad Loans:** 13.82% of applications are charged off, totaling
    **\$65.5M funded** and **\$37.3M received**.\
-   **Loan purposes:** Debt consolidation, credit card refinancing, and
    home improvement dominate.\
-   **Borrower profiles:** Higher applications from individuals with 10+
    years employment and homeowners with mortgages or rent.

------------------------------------------------------------------------

## Tools Used

-   **Microsoft Excel** (Pivot Tables, Power Query, Slicers, Charts,
    Conditional Formatting)
------------------------------------------------------------------------

## How to Use

-   Open the `Bank loan report excel p3.xlsx` file.\
-   Use slicers and buttons to switch between the **Overview** and
    **Summary** dashboards.\
-   Analyze KPIs, loan status breakdowns, and borrower segment
    performance interactively.

------------------------------------------------------------------------

## Author

**Shanmukha Sai Bada**\
*Data Analyst \| Excel Dashboard Developer
