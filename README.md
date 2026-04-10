# Sales Performance Dashboard | Power BI

An interactive 3-page Power BI dashboard analyzing 9,994 retail 
transactions from a US superstore (2014–2017).

## Pages
**Page 1 — Sales Performance**
- KPI cards: Total Sales ($2.3M), Total Profit ($286K), Profit Margin (12.47%)
- Monthly sales trend line chart with year slicer
- Sales breakdown by product category
<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/68d4af29-5c17-40fd-a63d-415d0a3180d5" />

**Page 2 — Product Analysis**
- Sales vs Profit comparison by Sub-Category
- Identified Tables as high-revenue but near-zero profit product
- Category slicer (Furniture / Office Supplies / Technology)
<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/74496b24-5565-48dd-869a-ddc1721e1df9" />

**Page 3 — Region Analysis**
- US map with bubble size representing sales by State
- West region leads in total revenue across all 4 years
- Region slicer for dynamic filtering
<img width="500" height="380" alt="image" src="https://github.com/user-attachments/assets/c3aa197c-05f5-4206-a791-bc1f6fb30e0f" />

## Key Insights
- Technology is the top-performing category by revenue
- Tables sub-category shows high sales but negative profit margin
- West region generates the highest revenue but profit margins remain low across all regions
- Sales show consistent year-over-year growth from 2014 to 2017

## Recommendations
- Discontinue or reprice Tables sub-category to address negative profit margin
- Increase marketing investment in West region given highest revenue contribution
- Focus Q4 promotions on Technology category which drives highest revenue

## Tools & Skills
- Power BI Desktop
- DAX (SUM, DIVIDE, CALENDAR)
- Power Query (data cleaning, type formatting)
- Data modeling (Star Schema, Date Table, table relationships)

## Dataset
- Source: Superstore Sales Dataset (Kaggle)
- 9,994 rows | 21 columns | 4 regions | 3 product categories | 2014–2017
