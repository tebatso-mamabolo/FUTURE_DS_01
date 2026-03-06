**BUSINESS SALES PERFORMANCE**


***Tech Stack:***

*Microsoft Excel*: Used for initial data cleaning using Power Query.

*Power BI (Power Query)*: Used for advanced cleaning and formatting.

*Power BI (Desktop)*: Used for building the interactive dashboard and setting up Top N visual filters.

<img width="914" height="509" alt="image" src="https://github.com/user-attachments/assets/263cb16e-b36f-4207-9f83-79d7a1435f27" />


**Project Overview:**
This project was a lesson in how "clean" data rarely stays clean. It started in Excel with a stubborn Date column and moved into Power BI, where a Revenue column decided to break. This dashboard is the final, polished result of that multi-tool cleanup battle.

**Key Technical Challenges and Solutions:**
1. *The first hurdle (Excel and Date Formatting)*
   
   The Problem: Before I got to Power BI, the Date column was a mess of inconsistent formats that would not sort correctly.
   The Fix: I used Excel to standardise the date strings and ensure every row followed a proper calendar format.
   The Result: A reliable timeline that Power BI could actually recognise for time-based analysis.

2. *The Second Battle (Power BI and Revenue)*
   
   The Problem: Once uploaded, the Revenue column was stuck as text, hidden by non-breaking spaces and points that should have been commas.
   The Fix: I used Power Query to strip out the invisible characters and applied Locale-aware transformations to fix decimals.
   The Result: A clean, fixed decimal column that finally allowed for accurate totals.
3. *Making the Insights "smart" (Visual Level Filters)*
   
   The Problem: A standard card visual only shows the first product alphabetically, which is not very helpful for business.
   The Fix: Instead of relying on complex measures, I utilised the Filter Pane by applying the Top N (Top 1) to the card, ranked by Total Revenue.
   The Result: The main card now dynamically highlights the actual number 1 best seller based on whatever category is selected in the slicer.

      **Business Insights and Recommendations:**
After looking at the finished charts, here is what the data is actually telling us:

  --The Big Winners: Laptops (R38K) and Tablets (R34K) are our heavy hitters. We should focus on selling accessories (like mice or bags) with these to increase the total sale.

  --Gauteng is far ahead of everyone else with R56K in revenue. We should double down on marketing there, but also figure out why the Western Cape is so far behind.

  -- Our sales hit a massive high in March (R26.8K) but crashed in September (R4.7K). We need a big promotion or a clearance sale in August to help bridge that gap.

   **The Finished Result**
   <img width="914" height="509" alt="image" src="https://github.com/user-attachments/assets/263cb16e-b36f-4207-9f83-79d7a1435f27" />
   How to use:
   1. Download the .pbix file.
   2. Open in Power BI desktop.
   3. Explore: Click the slicers and watch the "Top Selling Product"  and "Best Region in Revenue" cards change in real time.
