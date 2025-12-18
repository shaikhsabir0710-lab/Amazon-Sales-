📊 -- Amazon Sales Analysis Summary--

1. Data Loading & Initial Exploration

.Imported necessary libraries: pandas, numpy, matplotlib, seaborn.

.Loaded the dataset Amazon Sale Report.csv.

.Displayed first and last 5 rows, dataset shape, column info, and summary statistics.

-- 2. Data Cleaning --

.Identified and dropped columns with complete null values (New, PendingS).

.Removed rows with any null values across the dataset.

.Converted data types: ship-postal-code → int64

.Date → datetime64[ns]

.Amount → int

-- 3. Feature Engineering --

Created a profit margin column (Profit_Margin) by randomly assigning margins (10–40%) to each product category.
Derived Profit and Cost from revenue.
Extracted Month, Year, and Weekday from the Date column.

4. Exploratory Data Analysis (EDA)

a. Size-wise Distribution

1.Created a count plot for product sizes (Size column).

2.Found 'M' size to be the most ordered.

-- b. Category-wise Profit Analysis --

. Grouped by Category and summed Profit.

. Visualized using a bar chart.

. Found 'Shirt' to be the most profitable category.

-- Key Insights --

1.Data Size: ~128K rows, 21 columns (reduced after cleaning).

2.Most Popular Size: Medium (M).

3.Most Profitable Category: Shirts.

4.Profit Calculation: Random profit margins applied for simulation.

-- Visualization Highlights --

1.Used seaborn and matplotlib for plotting.

2.Cleaned and formatted charts with labels, titles, and bar annotations.

Link project-[Amazone Sales Analysis.ipynb]
Linkdin Profile - [https://www.linkedin.com/in/sabir-shaikh-64163036a]

