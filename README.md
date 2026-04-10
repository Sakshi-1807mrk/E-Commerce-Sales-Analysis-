# Domain : E-Commerce / Retail Analytics 

## 1. E-Commerce Sales Dashboard : 
An interactive Power BI dashboard designed to analyze and visualize e-commerce sales performance, uncover key business insights, and support data-driven decision-making.


## 2. Purpose :

This dashboard provides a comprehensive view of sales, profit, customer behavior, and product performance. It helps identify trends, top-performing segments, and areas of improvement within an e-commerce business.


## 3. Tech Stack :

The dashboard was built using the following tools and technologies:

- 📊 Power BI Desktop – Used for building interactive dashboards and visualizations  
- 📂 Power Query – Data cleaning and transformation  
- 🧠 DAX (Data Analysis Expressions) – Created calculated measures (Revenue, Profit, KPIs)  
- 🔗 Data Modeling – Relationship established between Orders and Details tables using `orderid`  
- 📁 File Format – `.pbix` for development  


## 4. Data Source :

The dataset consists of two structured tables:

- Orders Table  
  Contains transactional data including:  
  orderid, amount, profit, quantity, category, subcategory, payment mode  

- Details Table  
  Contains customer and location data including:  
  orderid, order date, customer name, state, city  

These tables are connected using a primary key (`orderid`) to enable integrated analysis.

## 5. Features :
 
  • Business Problem like E-commerce businesses generate large volumes of sales data, but extracting meaningful insights from raw data is challenging.  

Key questions such as: Which products and categories drive the most revenue?, What are the most preferred payment methods?, Which cities or states contribute the most to sales?  , Are there any loss-making periods?…cannot be easily answered without proper visualization.

# •  Goal of the Dashboard 
     To deliver an interactive visual tool that: Enables users to explore Provides a clear overview of sales performance, Helps identify trends in revenue and profitEnables analysis of customer behavior and regional performance, Supports business decisions using data-driven insights
     
# •  Walkthrough of Key Visuals
       • KPI Cards (Top Section) Displays metrics like :  
                - Total Revenue: 438K  
                - Total Profit: 37K  
                - Total Orders: 1500  
                - Total Quantity Sold: 5615  
      • Top Cities (Bar Chart) that Highlights cities contributing the highest revenue such as Thiruvananthapuram, Udaipur, and Surat.
      •  Preferred Payment Mode (Donut Chart) Shows distribution of payment methods.COD and UPI dominate, indicating customer preference for flexible payment options.
      • Month-wise Profit (Column Chart) Displays profit trends across months thzt Helps identify seasonal patterns and loss-making periods.
      •  Category vs Quantity Sold (Pie Chart) Shows category contribution and the stock sold  
      • Top Products (Bar Chart) Identifies top-performing subcategories such as printers, sarees, and bookcases.
      • Filters (Quarter & State Slicers) Allow dynamic exploration of data based on time period and region.
      
# •  Business Impact & Insights
    - Category Performance: Clothing is the leading category in terms of sales  
    - Customer Behavior: COD and UPI are the most preferred payment methods  
    - Profit Trends: Certain months show negative profit, highlighting potential inefficiencies  
    - Regional Insights: A few cities contribute significantly higher revenue than others  
## 6. Screenshot / Demo
![Dashboard Preview](https://github.com/Sakshi-1807mrk/E-Commerce-Sales-Analysis-/blob/main/Dashboard%20_Image.png)
Watch the Vedio : 
https://drive.google.com/file/d/1nQyBUtAGQFi0oNWNGLDYFMY_eo4KCkt0/view?usp=drivesdk
