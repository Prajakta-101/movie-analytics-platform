# movie-analytics-platform



## Overview
This project analyzes large-scale IMDb and TMDB movie metadata to evaluate financial performance, audience sentiment, and return on investment (ROI). The platform integrates data engineering, analytics, and visualization to support data-driven decision-making in the film industry.

---

## Tools & Technologies
- Python  
- Azure Data Factory / Power Query  
- Power BI  
- Tableau  
- SQL  

---

## Data
- The full dataset (>1M rows) is excluded due to GitHub file size limits  
- A representative sample dataset is provided in the `/data` folder for reproducibility  

---

## Data Pipeline
Power Query was used to implement the data pipeline, including:
- Inflation-adjusted budget and revenue calculations  
- ROI and profit margin computation  
- Feature engineering and data type standardization  

Transformation logic and pipeline steps are documented in the `/data_pipeline` folder.

---

## Visualizations
Power BI dashboards were developed to highlight:
- Adjusted budget vs. adjusted revenue (log scale)  
- Top movies by highest adjusted revenue  
 

Visualization assets are available in `/power_bi_visualizations`.

---

## Key Insights
- There is a strong positive relationship between movie budget and adjusted revenue  
- ROI varies significantly due to extreme outliers  
- High audience ratings do not always correlate with strong sentiment scores  

---

## Reports
Detailed documentation covering business objectives, data processing decisions, assumptions, and analytical insights is available in the `/reports` folder, including:
- An executive summary outlining project goals and value proposition  
- A data processing and feature engineering report covering inflation adjustment, ROI calculation, sentiment analysis, and key assumptions  
