# Automotive Market Intelligence | PostgreSQL & Power BI

## Project Overview
Analysed **17,048 Australian vehicle listings** using PostgreSQL to explore market composition, vehicle pricing patterns, and data quality. The project aims to identify key pricing factors and flag potentially mispriced vehicles for further review.

## Tools Used
- **PostgreSQL (pgAdmin):** Data cleaning and SQL analysis
- **SQL:** CTEs, JOINs, window functions, aggregations, and views
- **Power BI:** Dashboard design and data visualisation

## Key Findings
- Identified **65 duplicate listings**, leaving 16,982 analysable records after data-quality exclusions.
- Used vehicles had a median asking price of **A$29,888**, compared with a mean of **A$35,639**.
- Found that vehicle age, mileage, and model were strongly associated with asking prices.
- Developed a comparable-vehicle pricing benchmark covering **75.7%** of used listings and flagged **328 high-priority listings** for review.

## Power BI Dashboard
Designed three dashboard pages:
1. **Market Overview** – Listing distribution by brand and vehicle category.
   <img width="1202" height="680" alt="image" src="https://github.com/user-attachments/assets/54de02a7-6f34-4393-b4a5-99cb9f4e7bb4" />

2. **Price & Mileage Analysis** – Asking-price patterns and vehicle characteristics.
3. **Pricing Review Queue** – Peer-price comparisons and unusual listing identification.

## Business Recommendations
- Improve data validation to reduce duplicate and inconsistent listings.
- Use median prices for more reliable vehicle comparisons.
- Prioritise unusual asking prices for manual review.

## Limitations
The dataset contains asking prices rather than completed sales. Results do not represent actual transaction prices, customer demand, or sales performance.
