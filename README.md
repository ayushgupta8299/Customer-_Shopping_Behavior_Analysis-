Customer Shopping Behavior Analysis 


Project Overview
This project focuses on analyzing customer shopping behavior for a leading retail company to improve sales, customer satisfaction, and long-term loyalty. By examining demographics, 
purchasing patterns, and promotional impact, the project identifies key trends to optimize marketing and product strategies.


 Tools & Technologies
• Python: Data manipulation, cleaning, and exploratory data analysis (EDA).
• SQL (PostgreSQL): Advanced data analysis and answering complex business questions.
• Power BI: Building an interactive dashboard to track KPIs and visualize insights.
• AI Tools (Gamma): Automating the creation of a professional client-ready presentation.
• GitHub: Version control and public portfolio hosting.


 Project Workflow
1. Data Cleaning & Feature Engineering (Python)
The initial phase involved loading the dataset into a Jupyter Notebook for cleaning and preparation.
• Imputation: Missing review ratings were imputed using the median rating within each specific category to maintain data integrity and avoid category bias.
• Formatting: Column names were converted to snake_case for consistency and ease of use in SQL.
• Feature Engineering:
    ◦ Created age_group (Young Adult, Adult, Middle-aged, Senior) to analyze demographic patterns.
    ◦ Converted textual purchase frequencies into a numerical purchase_frequency_days column for easier metric calculation.
• Optimization: Dropped the promo_code_used column as it was found to be redundant with the discount_applied data.
2. Deeper Analysis (SQL)
The cleaned data was migrated to a PostgreSQL database to perform advanced queries. Key business insights derived include:
• Revenue Segmentation: Analyzing revenue split by gender and age group (e.g., Young Adults drive the most revenue).
• Shipping Impact: Comparing average spend between Standard and Express shipping, revealing that Express shipping customers tend to spend more.
• Customer Segmentation: Categorizing customers into New, Returning, and Loyal segments based on their purchase history.
• Product Performance: Identifying the top 3 best-selling products within each category using window functions like ROW_NUMBER().
• Subscription Analysis: Determining that while loyal customers exist, many remain unsubscribed, suggesting a need to optimize subscription offers.
3. Interactive Dashboard (Power BI)
A sleek, interactive dashboard was built to communicate findings to stakeholders.
• KPI Tracking: Cards for Total Customers, Average Purchase Amount, and Average Review Rating.


• Visualizations:
    ◦ Donut Chart: Subscription status distribution.
    ◦ Column/Bar Charts: Revenue and Sales volume by category and age group.
• Interactivity: Added slicers for Gender, Category, Subscription Status, and Shipping Type to allow for dynamic data exploration.
5. Documentation & Presentation
• Project Report: Detailed documentation of the methodology and technical steps.
• Presentation Deck: A high-level, client-ready deck generated using AI to summarize insights for managers and stakeholders.


 Repository Structure
• data/: Contains the customer_shopping_behavior.csv dataset.
• notebooks/: Python scripts for EDA and cleaning.
• sql_queries/: SQL scripts for business question analysis.
• dashboard/: Power BI project file.
• reports/: Final project report and PDF presentation.




