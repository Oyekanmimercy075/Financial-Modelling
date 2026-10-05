📊 Financial Modeling in Excel — West Ridge North Investment Analysis
📌 Project Overview
This project demonstrates the use of Microsoft Excel for financial modeling, forecasting, scenario analysis, sensitivity analysis, and investment evaluation.

The project focuses on West Ridge North, an 80-unit real estate investment property owned by Shady Tree Mgmt. The objective was to build a dynamic financial model that could forecast the property's financial performance and determine whether the investment would be financially attractive.

The project was completed as part of my DataCamp Financial Modeling in Excel training.

🎯 Business Problem
The key question was:

Should West Ridge North be considered a good investment based on its projected financial performance and expected returns?

To answer this, I built a financial model that allows different assumptions to be changed and evaluates their impact on revenue, expenses, net operating income, cash flows, and investment returns.

🏗️ 1. Financial Model Structure & Forecasting
Problem
A real estate investment involves multiple assumptions, including rental income, operating expenses, growth rates, capital expenditures and investment returns.

The challenge was to organize these assumptions into a model that could be easily updated and used for forecasting.

What I Did
I:

Structured the financial model according to financial modeling standards.
Formatted input cells separately from calculated outputs.
Used SUM() to calculate subtotals and net income.
Applied growth rates to forecast future income and expenses.
Created and used named ranges in formulas.
Used lookup functions to make the model dynamic.
Created forecasted financial statements and investment projections.
Why It Matters
A properly structured financial model makes it easier to update assumptions, understand how different variables affect financial performance, and make informed business decisions.

🔄 2. Scenario Analysis — Scenario Manager
Problem
What happens to West Ridge North's financial performance if rental assumptions change?

Instead of manually changing the assumptions each time, I used Excel Scenario Manager to create different scenarios.

What I Did
I created scenarios including:

Expected Rent Scenario: 5% rent growth with $2,300 monthly rent.
High Rent Scenario: 8% rent growth with $2,500 monthly rent.
Under the expected scenario, projected NOI was approximately $2.95 million.

Under the high-rent scenario, projected NOI increased to approximately $4.21 million.

Why It Matters
Scenario Manager makes it possible to quickly compare different business conditions without rebuilding the model.

This can help management evaluate optimistic, expected and conservative outcomes before making a decision.

🎯 3. Goal Seek — Working Backwards from a Target
Problem
What inputs would be required for West Ridge North to achieve a specific target net income?

What I Did
I used Goal Seek to work backwards from a target net income of $5 million.

Instead of manually testing different assumptions, Goal Seek determined the input required to reach the target.

Why It Matters
Goal Seek is useful when a business already has a target and wants to determine the level of sales, price, revenue growth or other input required to achieve it.

📈 4. One-Variable Sensitivity Analysis
Problem
How sensitive is West Ridge North's NOI to changes in rent growth?

What I Did
I created a one-variable Data Table to test different rent-growth assumptions.

Rent Growth	Projected NOI
0%	~$1.83M
2.5%	~$2.35M
5%	~$2.95M
7.5%	~$3.67M
10%	~$4.52M
I also applied conditional formatting to make the results easier to interpret.

Why It Matters
Sensitivity analysis helps identify which assumptions have the greatest impact on financial performance.

It also helps decision-makers understand the potential risks associated with changing market conditions.

📊 5. Two-Variable Sensitivity Analysis
Problem
What happens when both rent growth and monthly rent per unit change?

What I Did
I created a two-variable Data Table using:

Rent Growth %
Effective Monthly Rent per Unit
For example, at 5% rent growth, increasing monthly rent from $2,000 to $3,000 increased projected NOI from approximately $2.50M to $4.01M.

Why It Matters
Business performance is rarely affected by only one variable.

Two-variable sensitivity analysis allows multiple assumptions to be tested simultaneously and provides a better understanding of potential outcomes.

💰 6. Time Value of Money — FV & PV
Problem
Is the future return from West Ridge North worth the same as its value today?

What I Did
I used Excel's:

FV() — Future Value function
PV() — Present Value function
to evaluate the value of the investment over its holding period.

The model projected a total future return of approximately $79.66M, while the present value of that return was approximately $5.89M, based on the assumptions and benchmark rate in the model.

Why It Matters
The time value of money is important because money received in the future is not economically equivalent to money received today.

PV and FV calculations help investors evaluate future cash flows in today's terms.

📉 7. Investment Evaluation — ROI, NPV & IRR
Problem
After forecasting West Ridge North's financial performance, how can we determine whether the investment is attractive?

What I Did
I calculated several investment performance metrics:

Metric	Result
ROI	~8.58x
NPV	~$13,437
IRR	~29.78%
XIRR	~29.75%
I compared the investment's projected returns and present value against the benchmark assumptions in the model.

Why It Matters
Each metric provides a different perspective:

ROI measures the return relative to the investment.
NPV measures the value created after accounting for the required return.
IRR estimates the investment's rate of return.
XIRR calculates the return using actual cash-flow dates.
Together, these metrics provide a stronger basis for evaluating an investment.

📅 8. Date-Based Analysis — EOMONTH, XNPV & XIRR
Problem
Investment cash flows do not always occur at perfectly regular intervals.

What I Did
I used EOMONTH() to create date ranges and time-series data.

I then used date-based investment functions such as:

XIRR()
XNPV()
to evaluate cash flows using their actual dates.

Why It Matters
Date-based calculations provide a more realistic approach to investment analysis when cash flows occur on different dates.

🏢 9. Capital Budgeting
Finally, I applied the financial modeling techniques to capital budgeting and compared competing investment projects.

The objective was to use financial metrics rather than intuition alone to determine which project provides the more attractive investment opportunity.

This demonstrated how Excel financial models can support capital allocation and strategic decision-making.

🛠️ Excel Skills Demonstrated
Financial Modeling
Financial statement modeling
Revenue and expense forecasting
Growth-rate forecasting
Named ranges
Dynamic formulas
Lookup functions
What-If Analysis
Scenario Manager
Goal Seek
One-variable Data Tables
Two-variable Data Tables
Conditional Formatting
Investment Analysis
ROI
Present Value (PV)
Future Value (FV)
Net Present Value (NPV)
Internal Rate of Return (IRR)
Extended Internal Rate of Return (XIRR)
Extended Net Present Value (XNPV)
Date & Time Functions
EOMONTH()
Date-based cash-flow analysis
📁 Project Files
income_modeling.xlsx — Financial modeling, forecasting and scenario analysis.
Return_on_investment.xlsx — West Ridge North investment and return analysis.
📚 Learning Outcome
This project strengthened my ability to use Excel as a financial decision-making tool, rather than simply as a spreadsheet for calculations.

I learned how to build dynamic financial models, forecast business performance, test different scenarios, perform sensitivity analysis, evaluate investments and compare competing projects using financial metrics.

The project also strengthened my understanding of how data analysis, financial modeling and business decision-making can work together to solve real-world business problems.

Tools: Microsoft Excel | DataCamp Financial Modeling
