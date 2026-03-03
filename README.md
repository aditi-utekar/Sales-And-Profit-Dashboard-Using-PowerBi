# 📊 Sales and Profit Dashboard – Power BI
📌 __Project Overview__    
This project is an interactive __Sales and Profit Dashboard__ built using __Power BI Desktop__.  
The dashboard provides insights into sales performance, profit trends, regional performance, category distribution, and sub-category analysis.

It is designed to demonstrate strong data modeling, DAX calculations, bookmarks, drill-through functionality, and interactive reporting features.  

🎯 __Objectives__
- Analyze Sales and Profit trends over multiple years
- Compare performance across Regions
- Evaluate Category and Sub-Category contribution
- Analyze Sales by Salespersons
- Track Profit Ratio by Region
- Build a fully interactive and user-friendly dashboard  

---
📂 __Dashboard Features__  

1️⃣ __Sales & Profit Toggle__ (Using Bookmarks and Buttons)
One of the key highlights of this dashboard is the Sales and Profit toggle functionality.
- I used 4 buttons:
  - 2 for Sales
  - 2 for Profit
- Each pair consists of:
  - One colored (active) button
  - One grey (inactive) button
- The buttons are overlapped on each other
- The line charts are also overlapped  

🔁 __How It Works__

- When the colored Sales button is clicked:
   - It displays the Sum of Sales by Year line chart
   - The Sales button appears active
- When the colored Profit button is clicked:
   - It displays the Sum of Profit by Year line chart
   - The Profit button appears active

This functionality is implemented using:
   - __Bookmarks__
   - __Selection Pane__ (to control visibility)
   - Overlapping visuals

This creates a smooth toggle experience without switching pages.

---
2️⃣ __Drill Through – Sub Category Analysis__

I implemented Drill Through functionality to provide deeper insights.
From the main dashboard:

- Users can right-click on a Category
- Select Drill Through
- Navigate to a detailed page showing: __Sum of Sales by Sub-Category__
This allows detailed analysis of individual sub-categories.
---

3️⃣ __Sales by Year and Category__
- Clustered Column Chart
- Shows yearly sales comparison
- Helps identify growth trends across categories

---
4️⃣ __Sales by Category__
- Donut Chart visualization
- Displays contribution percentage of Category
---
5️⃣ __Sales by Persons__
- Horizontal Bar Chart
- Shows top-performing salespersons
- Easy performance comparison
---

6️⃣ __Profit Ratio by Region__
- Tabular visual showing Regions
- Includes calculated Profit Ratio (%)
---

7️⃣ __Interactive Filters__
- Region slicer
- Month slicer
- Year slicer
- Card visual to show Report Date
---

📈 __Key DAX Measures Used__
- Profit Ratio
- Date table
- Report Date
---

📷 __Dashboard Preview__
<img width="1290" height="721" alt="Dashboard_Screenshot" src="https://github.com/user-attachments/assets/01818ffb-2aeb-48a5-bd0c-e4799664dadc" />
<img width="1290" height="730" alt="Screenshot 2026-03-01 185347" src="https://github.com/user-attachments/assets/ca4ab77b-d360-44e4-bafd-ab0971a35c59" />

---

📌 __Conclusion__

This Sales and Profit Dashboard demonstrates my ability to transform raw business data into meaningful and actionable insights using Power BI.
Through this project, I have implemented not only standard visualizations but also advanced interactive features such as:

- Building relationships between tables
- Bookmark-driven toggle between Sales and Profit line charts
- Overlapping buttons with active (colored) and inactive (grey) states
- Drill-through functionality to analyze Sales by Sub-Category
- Dynamic filtering using slicers
- Clean and structured data modeling using a Star Schema approach
- Writing efficient DAX measures
- Designing interactive and user-friendly dashboards
- Applying business logic to real-world datasets
- Creating visually balanced and professional layouts

Overall, this dashboard reflects both my technical skills in Power BI and my ability to think from a business perspective — focusing not just on visuals, but on delivering insights that answer real business questions.  
This project represents my practical readiness to contribute as a Data Analyst by combining analytical thinking, data modeling, and strong visualization skills.
  
