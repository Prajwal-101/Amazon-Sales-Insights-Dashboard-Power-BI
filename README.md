# Amazon Sales Dashboard

### Problem Statement

In the dynamic landscape of e-commerce, optimizing sales performance on platforms like Amazon is paramount for business success. However, the sheer volume and complexity of sales data pose significant challenges in deriving actionable insights efficiently. Therefore, our company seeks to develop a comprehensive Amazon Sales Dashboard to empower stakeholders with insights into sales trends, product performance, and market dynamics.

This dashboard aims to centralize sales data, providing stakeholders with a holistic view of Amazon sales performance across different product categories, regions, and time periods. Key objectives include analyzing sales trends, evaluating product performance, identifying growth opportunities, and understanding customer behavior. By developing an intuitive and interactive dashboard using Power BI, we aim to equip stakeholders with the tools necessary for data-driven decision-making, ultimately driving business growth and enhancing competitiveness in the e-commerce space.

---

### Empowering Insights:

Created 3 major pages which are "Overview", "Product", and "Product View" and all these pages have the following functionalities:

1. **Overview:**

![Screenshot 2024-02-18 163127](https://github.com/Prajwal-101/Amazon-Sales-Insights-Dashboard-Power-BI/assets/159109640/4cadbcd5-63aa-41eb-9ef2-546d77a77a5f)

   - Serves as the homepage of the dashboard.
   - Includes a slicer displaying product categories.
   - Features cards showing KPIs for specific product categories such as Boys Jackets, Ethnic Wears, Sarees, etc.
   - Incorporates a switch button for toggling between "Sales" and "Units".
   - Utilizes a slicer as a filter for delivery status.
   - Presents 2 bar graphs illustrating "Sale by State" and "Sale by City".
   - Showcases an Area chart displaying monthly generated revenue for specific products.

2. **Product:**
   
![Screenshot 2024-02-18 163300](https://github.com/Prajwal-101/Amazon-Sales-Insights-Dashboard-Power-BI/assets/159109640/665fd131-cb60-4a56-b198-d6ae13d7d2e6)

   - Displays all products available in each category.
   - I have created a Tooltip for the "Product View" page, which allows users to view detailed data for a specific product by hovering their cursor over it. 

   The tooltip displays the following key performance indicators (KPIs) for the selected product:
   - Product Full Name
   - Product ID
   - Sales Amount
   - Sales Units
   - Number of Returns
   - Number of Reviews

   Additionally, the tooltip includes an area chart depicting the number of units sold monthly for the selected product. This interactive feature provides users with comprehensive insights into the performance and sales trends of individual products.

   - Includes an area chart showing the number of units sold monthly.

3. **Product View:**
   

![Screenshot 2024-02-18 163349](https://github.com/Prajwal-101/Amazon-Sales-Insights-Dashboard-Power-BI/assets/159109640/f85fdd7e-ad0b-4530-81f6-c8075e993666)



   - Acts as a zoomed-out version of the tooltip.
   - Enables filtering of product sales details using a date calendar to choose the desired duration for sales and units data.
