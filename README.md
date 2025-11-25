# EDA-on-Retail-Sales-Data 
This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to uncover insights into customer demographics, purchasing behavior, product performance, and sales trends. The analysis is designed to demonstrate skills in data cleaning, statistical analysis, visualization, and storytelling with data.


Tools & Libraries
Python → Core language for analysis

Pandas & NumPy → Data cleaning, manipulation, and aggregation

Matplotlib & Seaborn → Visualizations (line charts, bar plots, histograms, heatmaps)

Google Colab → Interactive notebook environment

Project Workflow
1. Data Cleaning
Checked shape, dtypes, missing values, duplicates

Standardized categorical values (Gender, Product Category)

Validated transaction totals (Total Amount = Quantity × Price per Unit)

2. Descriptive Statistics
Mean, Median, Mode, Variance, Standard Deviation

Revenue and quantity analysis by product category

Demographic breakdown by gender and age

3. Time Series Analysis
Created YearMonth column from Date

Monthly sales trends

Category‑wise revenue trends

Rolling averages to smooth fluctuations

4. Customer & Product Analysis
Revenue by gender and age groups

Age distribution histogram

Top 10 customers by revenue

Product category preferences

Correlation heatmap of key variables

5. Conclusion & Recommendations
Electronics and Clothing drive most revenue

Beauty shows premium spend per transaction

Female customers contribute slightly more revenue

Sales peak in May and December → focus promotions

Age group 25–44 is the most profitable segment

 Key Insights
Transaction Values: Most purchases are small, but a few large ones skew the average upward.

Product Categories: Electronics lead revenue, Clothing close behind, Beauty has higher spend per transaction.

Customer Demographics: Average age ~41 years; females contribute slightly more revenue.

Seasonality: Sales peak in May and December, dip in March.

Correlation: Quantity and Total Amount strongly correlated; Age weakly correlated with spending.

 Recommendations
 Increase inventory & promotions in peak months (May, December)

 Focus marketing on Electronics and Clothing

 Build loyalty programs for female customers

 Target 25–44 year olds as the most profitable demographic

 Explore Beauty category for premium growth opportunities
