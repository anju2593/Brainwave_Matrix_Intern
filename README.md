# Brainwave_Matrix_Intern
**Task 1: Sales Data Analysis Report of any commercial store.**

I have been assigned the task of analyzing sales data for our eCommerce store. The objective is to identify key sales trends, top-performing products, customer behavior, and revenue patterns.

**Steps to be followed**

**Step 1: Load the Dataset into Power BI**
Open Power BI Desktop.
Click Home > Get Data > Text/CSV.
Select your sample_sales_data.csv file and click Open.
A preview of the dataset appears; click Load to import it.

**Step 2: Transform Data in Power Query**
Click Transform Data (Power Query Editor opens).
Check column types:
Ensure Date column type is set to "Date."
Ensure Quantity, Price, and Total Sales are set to "Decimal Number."
Remove unnecessary columns.
Click Close & Apply to save changes.

**Step 3: Create Visualizations for the Dashboard**
Now, build different charts and visuals for insights.

**1. Sales Overview (KPIs)**
Visual Type: Card
Create cards for:
Total Sales → Use SUM(Total Sales)
Total Orders → Use COUNT(Order ID)
Total Customers → Use DISTINCTCOUNT(Customer ID)
Average Order Value (AOV) → Use Total Sales / Total Orders

**2. Sales Trend Over Time**
Visual Type: Line Chart
X-axis: Date
Y-axis: Total Sales
Shows revenue trends over time.

**3. Best-Selling Products**
Visual Type: Bar Chart
X-axis: Product Name
Y-axis: SUM(Total Sales)
Sort in descending order to see top products.

**4. Sales by Category**
Visual Type: Pie Chart
Category on Legend.
Total Sales as Values.

**5. Sales by Sales Channel**
Visual Type: Stacked Column Chart
X-axis: Sales Channel
Y-axis: Total Sales
Helps compare online vs in-store sales.

**6. Customer Insights**
Visual Type: Table or Matrix
Columns: Customer ID, Total Sales, Order Count.
Use SUM(Total Sales) and COUNT(Order ID).

**Step 4: Add Interactivity**
Add Slicers for filtering:
Date Range
Product Category
Sales Channel
Enable Drill-Through to analyze product or customer details.
Set up Tooltips for additional insights on hover.

**Step 5: Format and Finalize the Dashboard**
Apply themes & colors for professional visuals.
Rename visuals & provide titles.
Adjust layout for a clear & intuitive design.

**Step 6: Publish the Dashboard**
Click Publish in Power BI.
Save it to Power BI Service for sharing.
Set up scheduled data refresh (if using live data).

**Expected Outcome:**
The expected outcome is a comprehensive sales report with charts and recommendations for business improvements. 

**Deadline:**
The deadline for this task is February 14, 2025.
