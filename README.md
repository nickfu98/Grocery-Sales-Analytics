# Grocery Sales Analytics Dashboard (Power BI)

This project analyzes 6 million rows of synthetic grocery sales data from January–April 2018 using Power BI.  
The dashboard provides insights into sales performance, geographic trends, salesperson behavior, customer analytics, and key drivers of sales performance.

---

## Project Structure

# 1. Grocery Sales Overview (Page 1)

![Page 1](images/page_01_overview.png)

### **Key Questions Answered**
- What were total sales and average sales per month?
- Which regions and categories drove the most revenue?
- What are the top-selling products?
- How did monthly sales trend from January to April?

### **Key Visuals**
- KPI cards: Total Sales, Avg Sales/Month, Avg Sales/Order, Avg Orders/Purchase  
- Total Sales by Region (bar)  
- Total Sales by Category (donut)  
- Total Sales per Month (line)  
- Top 10 Products by Sales (bar)

---

# 2. Sales Breakdown (Page 2)

![Page 2](images/page_02_sales_breakdown.png)

### **Key Questions Answered**
- How do sales vary across cities, regions, and salespeople?
- What is the relationship between sales volume and order counts?
- How do top salespeople perform across product categories?

### **Key Visuals**
- Scatter: Sales vs. Orders for Top 10 Revenue Cities  
- Matrix Heatmap: Category Sales Breakdown of Top 10 Salespeople  
- Region Sales Distribution (pie chart)  
- KPI cards: Total Sales, Avg Sales per City, Avg Sales per Salesperson, Total Orders

---

# 3. Customer Analytics (Page 3)

![Page 3](images/page_03_customer_analytics.png)

### **Key Questions Answered**
- Who are the top customers by lifetime spend?
- How are customers segmented based on total purchase amount?
- How many customers are active by region?
- How do customer orders trend month-to-month?

### **Key Visuals**
- Top 10 Customers by Sales (bar)  
- Customer Segmentation by Lifetime Spend (bucketed)  
- Customers per Region (bar)  
- Customer Orders per Month (line)  
- KPI cards: Total Customers, Avg Sales/Customer, Avg Orders/Customer

---

# 4. Geographic Breakdown (Page 4)

![Page 4](images/page_04_geographical_breakdown.png)

### **Key Questions Answered**
- Which cities generate the highest and lowest sales?
- How is revenue distributed geographically across the U.S.?

### **Key Visuals**
- Top 10 Cities by Total Sales (map)
- Bottom 10 Cities by Total Sales (map)
- Slicers for Month, Category, Salesperson, Region

---

# 5. Sales Root Cause Analysis (Page 5)

![Page 5](images/page_05_root_cause_analysis.png)

### **Key Questions Answered**
- What is driving sales performance across different dimensions?
- How do region → city → category → salesperson combinations influence results?

### **Key Visuals**
- Decomposition Tree using:
  - Region  
  - City  
  - Category  
  - Salesperson  

This provides a true **root-cause analysis** workflow typical of executive BI dashboards.

---

# 6. Key Drivers of Performance (Page 6)

![Page 6](images/page_06_key_drivers.png)

### **Key Questions Answered**
- What factors increase the likelihood of below-average sales performance?
- Which cities and categories most strongly influence low performance?

### **Key Visuals**
- Power BI Key Influencers (AI visual)
- City-level comparison of Below-Average Sales %  

This page uses Power BI’s AI engine to statistically evaluate contributors to underperformance.

---

# Tools & Skills Demonstrated

### **Power BI**
- Advanced DAX measures  
- KPI design  
- Decomposition tree & Key Influencers (AI visuals)  
- Custom Top-N logic  
- Heatmaps & segment analysis  

### **Data Modeling**
- Star schema  
- Measures vs. calculated columns  
- Customer segmentation and bucket logic  
- Sales, region, city, and customer dimension analysis  

### **Analytics & Insights**
- Executive KPI reporting  
- City-level geographic insights  
- Salesperson productivity patterns  
- Customer lifetime value segmentation  
- Root-cause and driver analysis  

---

# 📌 About This Project

This dashboard was created as part of a larger BI portfolio to demonstrate:

- End-to-end dashboard development  
- Multi-page storytelling  
- Advanced Power BI features  
- Performance/segment/customer analysis at scale  
- Ability to work with large (6M+ row) datasets  
