#Personal Budget and Savings Scenario Model
- In this project I created a personal budget. It allows you to see different scenarios, track actual spending against your budget, and tests what happens if your income changes. This personal budget allows you to see what happens if income drops or how much work you would have to do in order to reach specific savings goals. 
## What's in the workbook
- Inputs - The first worksheet within the workbook;  lists your income and expenses as inputs and they are able to change as you see fit.
- Transactions - On the second worksheet there are the transactions throughout the month. These do not change.
- Summary - The third worksheet in the workbooks shows a summary of what was actually spent versus your budget. It shows you if there is any variance between the two and states whether you were under budget, on budget, or over budget. Which allows you to adjust your budget to be more realistic the next month. 
- Data Tables - The data tables are available on the input worksheet and include both one and two variable scenarios. 
## Skills Used
- SUMIFS - In my summary I used SUMIFS to go over to the transactions worksheet and add up the rows that match the category. 
- XLOOKUP - In my summary I used XLOOKED allows you to search the income for the term you are looking for, then if it is not there IFERROR prevents the printing of the  error message until it looks over the expenses to see if the term is there. If so it returns it, if not it returns an error message. 
- IFS - In my summary I used IFS in order to indicate if I was under budget, over budget, or on budget. 
- Conditional Formatting - The conditional formatting that I incorporated into my project highlighted any category over budget and highlights the whole row in red so that I know I need to watch my spending in that category and if it continues to happen I may need to adjust my budget. 
- Scenario Manager - The scenario manager can be viewed under the data tab on the ribbon, nested under what_if_analysis and shows the base case where the my earnings do not vary from the original input data. Then there is a view showing what happens if I lost all forms of income during week one and the final view shows what happens if my income goes up to $450 from Upwork, $270 from Fiverr, $556 from Paycheck, $200 from tutoring, and $110 from data annotation.
- Data Table, one-variable - The one-variable table shows different views for just the work on Upwork during week one. The view continues up to $800 in income from Upwork's
- Data Table, two-variable - The two-variable data table shows different variations income made during week one on Upwork and by offering tutoring. You can see what happens if the income on Upwork continues up to the highest view at $800 and the views for tutoring goes up to the highest view of $300.
- Goal Seek - In the Goal Seek I calculated what I would need to make at my first week of pay on Upworks in order to make $1,500 that week instead of bringing home $1,246 in the first week. You would need to make $554 on Upworks.
## How to use it 
- Change a number on inputs - If I change an income or expense the summary automatically updates to the new corresponding values.
- Scenario Manager - Data Tab > What-If Analysis > Scenario Manager > Pick Base Case, Job Loss, or Overtime Month > Show - This will provide me with the answers based on which one someone selects. Make sure you switch back to Base Case after you're done.
- Data Tables - On Inputs, Change Upwork or Tutoring and watch total Week 1 income move; one-variable is Upwork only while two-variable is Upwork and Tutoring. - Goal Seek - Data tab > What-If Analsis > Goal Seek, You set cell P12 to $1500 it will change how much I need to earn from Upwork.
- Goal Seek - Data tab > What-If Analsis > Goal Seek, - set cell P12 to $1500 it will change how much I need to earn from Upwork.
## Key Findings
- Base Case - Week 1 income $1246
- Job Loss - $0, everything stops
- Overtime Month - $1586
- Goal Seek - My pay from Upwork needs to be $554 to have a week's income equal to $1,500.
- Data Tables - One-variable table shows what my income will be with an Upwork income ranging from $0 to $800 which moves the total week 1 income from $946 to $1,746; the two-variable corners are $811 (Upwork $0/Tutoring $0) and $1911(Upwork $800/Tutoring $300).
- What Surprised Me - I was surprised by the total of week 1 income was a lot more than I anticipated with zero income from Upwork.
## Files
project_2-5 cleaned.xlsx and README P2.md
