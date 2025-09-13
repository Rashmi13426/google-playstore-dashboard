# Google Play Store Data Analytics Dashboard

## Project Overview  
This Power BI dashboard provides an interactive analysis of the Google Play Store app ecosystem. It focuses on app ratings, categories, install counts, and paid vs free status — empowering stakeholders to make data-driven decisions.

## Dataset  
- Source: Google Play Store Dataset  
- Total Apps: 10,830  
- Columns Used: App Name, Category, Rating, Reviews, Installs, Is Paid.

## Data Cleaning (From EDA Project)  
- Removed null ratings and inconsistent installs data.  
- Standardized install counts to numerical format.  
- Created 'is_paid' column.  
- De-duplicated by app name.  

## Key Features  
- KPI cards: Average Rating, Total Apps, Total Installs  
- Bar & Pie Charts: Category distribution and Paid vs Free apps  
- Scatter Plot: Reviews vs Ratings by App  
- Line Chart: Average Rating by Category  
- Interactive Slicers for dynamic filtering

## Key Insights  
- FAMILY apps dominate the store → Strategic focus area  
- Only ~7% apps are Paid → Free model dominates  
- High reviews don’t always mean high ratings → Quality issues to investigate  
- EDUCATION & ART_AND_DESIGN apps have the highest average ratings

## How to Use  
1. Open the `.pbix` file in Power BI Desktop  
2. Use slicers (Category, Paid/Free) to filter data interactively  
3. Hover for tooltips
4. I've also added a screen shot of my dashboard for easy reference


