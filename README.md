# End-to-End Grocery Sales Intelligence

This project explores a synthetic grocery dataset containing over 6 million order line items recorded between January and April 2018.
Using Power BI, the analysis breaks down nationwide sales trends, regional performance, customer behavior, and operational drivers across product categories, cities, and sales teams.
The final dashboard highlights executive KPIs, geographic insights, salesperson contribution patterns, customer segmentation, and AI-driven diagnostics to provide a full sales intelligence experience.

This dashboard was created to demonstrate:

- End-to-end dashboard development  
- Multi-page storytelling  
- Advanced Power BI features  
- Performance/segment/customer analysis at scale  
- Ability to work with large (6M+ rows) datasets  


---

## Project Structure

# 1. Grocery Sales Overview (Page 1)

![Page 1](images/Grocery_Sales_01.png)

### **Key Questions Answered**
- What were total sales and average sales per month?
- What does the average order look like?
- Which regions and categories drove the most revenue?
- What are the top-selling products?
- How did monthly sales trend from January to April?

### **Key Visuals**
- KPI cards: Total Sales, Average Sales/Month, Average Sales/Order, Average Orders/Purchase  
- Total Sales by Region (bar)  
- Total Sales by Category (donut)  
- Total Sales per Month (line)  
- Top 10 Products by Sales (bar)
- Slicers for Month, Category, Salesperson

---

# 2. Sales Breakdown (Page 2)

![Page 2](images/page_02_sales_breakdown.png)

### **Key Questions Answered**
- How do sales vary across cities, regions, and salespeople?
- What is the relationship between sales volume and order counts?
- How do top salespeople perform across product categories?

### **Key Visuals**
- KPI cards: Total Sales, Total Orders, Average Sales per Salesperson, Average Sales per City
- Sales vs. Orders for Top 10 Revenue Cities (scatter)
- Region Sales Distribution (pie chart)  
- Category Sales Breakdown of Top 10 Salespeople (matrix heatmap)
- Slicers for Month, Salesperson, Region
---

# 3. Customer Analytics (Page 3)

![Page 3](images/page_03_customer_analytics.png)

### **Key Questions Answered**
- Who are the top customers by total spend?
- How are customers segmented based on total spend?
- How many customers are active by region?
- How do customer orders trend month-to-month?

### **Key Visuals**
- KPI cards: Total Customers, Avg Spend/Customer, Avg # Orders/Custome, Monthly Retention Rate
- Top 10 Customers by Total Spend (bar)
- Customer Segmentation by Lifetime Spend (histogram)
- Customers per Region (bar)
- Customer Orders per Month (line)
- Slicers for Month, Category, Salesperson

---

# 4. Geographic Breakdown (Page 4)

![Page 4](images/page_04_geographical_breakdown.png)

### **Key Questions Answered**
- Which cities generate the highest and lowest sales?
- How is revenue distributed geographically across the U.S.?

### **Key Visuals**
- Top 10 Cities by Total Sales (map)
- Bottom 10 Cities by Total Sales (map)
- Slicers for Month, Category, Region

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
- Slicers for Month, Category, Salesperson
  
This provides a true root-cause analysis workflow typical of executive BI dashboards.

---

# 6. Key Drivers of Performance (Page 6)

![Page 6](images/page_06_key_drivers.png)

### **Key Questions Answered**
- What factors increase the likelihood of above/below average sales performance?
- Which cities and categories most strongly influence sales performance?

### **Key Visuals**
- Power BI Key Influencers (AI visual)
- City-level comparison of Below-Average Sales %  

This page uses Power BI’s AI engine to statistically evaluate contributors to sales performance.

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


