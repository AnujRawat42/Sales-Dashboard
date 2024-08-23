# Amazon Sales Data -Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMjdkYTlmODMtN2QzZi00OTc3LThlZTQtNWZkMDcyOTNlNDA1IiwidCI6IjE1NTE1N2M3LTc5MzUtNDkxYi04OWQxLWY5NTJhYWQ1YzYwOSJ9 

## Problem Statement

The management team requires comprehensive insights into Amazon product sales across various categories and regions in India. We have two [CSV files](https://drive.google.com/drive/folders/1FascOQVc615Egn_Oc8D4wqPnvFCErvmi?usp=drive_link)containing sales data, and the goal is to utilize Power BI to analyze and visualize this information effectively. Key insights to be derived include:
-	The number of units sold within each product category
-	Total sales revenue generated per category
-	The count of sellers associated with each category
-	Monthly sales trends, highlighting the peak sales month
-	The current status and performance of each product category
-	The number of customer reviews for each category
These insights will enable the management to gain a clear understanding of the top-selling products, their distribution across states and cities, and the overall sales trends over time. This information will be crucial for strategic decision-making and optimizing product offerings in various regions.



### Steps followed 
- Step 1: Data Loading: Imported two CSV files containing Amazon product sales data into Power BI.

- Step 2: Data Cleaning and Transformation: Used Power Query to clean and format the data, focusing on refining the category column by inserting spaces between words that were previously joined.

- Step 3: Slicer Customization: Developed an advanced slicer incorporating both product names and images, enhancing the filtering options for a more interactive experience.

Report Page Design:

- Overview Page: Displays key metrics such as product status, total sales, sales by state and city, and seller count using card visuals. A column chart visualizes sales distribution across different states and cities.
- Product Page: Includes detailed product insights such as images, units sold, customer reviews, and sales trends by month, presented through tooltips for a more dynamic user experience.
- Product View Page: Offers an in-depth view of product performance with a custom date filter and a line chart that enables users to track sales trends over time.
  
# Key Insights from the Dashboard

## Total Units Sold Across Categories
A total of **120,000 units** were sold. The slicer can be utilized to filter and view the number of units sold for each specific category.

## Overall Sales Value
Total sales amounted to **$89.08 million**. The slicer allows further breakdown to view sales figures per category.

## Seller Count per Category
The dashboard reveals a total of **19,250 sellers**. Users can apply the slicer to explore the count of sellers for each category individually.

## Monthly Sales and Top-Selling Month
Sales trends are visualized using a line chart. **April** stands out as the top-selling month, with over **45,582 units sold**.

## Status of Product Orders
Product order statuses include:
- **80,480 orders shipped**
- **678 orders pending**
- **5,840 orders canceled**

The slicer can refine these numbers for each category.

## Customer Reviews by Category
There were a total of **4 million reviews**. The slicer can be applied to see the number of reviews for each category.

## Returned Items by State
**Maharashtra** and **Uttar Pradesh** recorded the highest number of returned items, with **259** and **230 items** respectively being returned to sellers.

## Top-Selling Category
The **"Women Kurta Kurtis"** category had the highest sales volume, with **15,053 units sold**, highlighting it as a key performer.

## Snapshot of the dashboard
![Screenshot 2024-08-23 122048](https://github.com/user-attachments/assets/47f4f8e9-fe3b-4988-b75e-8a65e230a140)
