# Customer Segmentation & Retention Dashboard

RFM (Recency, Frequency, Monetary) analysis on 2 years of real e-commerce 
transactions from the Online Retail II (UCI) dataset — 800K+ cleaned records, 
5,878 unique customers.

**Key finding:** Champions (29.6% of customers) generate 80.7% of total revenue.

**Stack:** Python (pandas, numpy) for cleaning + RFM scoring → Power BI for 
the interactive dashboard → business recommendations mapped to each segment.

## What's inside
- `notebooks/clean_data.ipynb` — data cleaning, RFM calculation, segmentation
- `data/rfm_segments.csv` — final scored customer segments
- `Customer_Segmentation_Dashboard.pbix` — interactive Power BI dashboard
- `Customer_Segmentation_Case_Study.docx` — full write-up with business recommendations
