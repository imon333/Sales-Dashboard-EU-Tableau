
# Sales dashboard
This interactive Sales Dashboard provides a detailed and comprehensive overview of sales and profit performance for the years 2023, 2022, 2021, and 2020. The dashboard is designed to offer actionable insights into key metrics, trends, and year-over-year comparisons. Users can filter data based on selected parameters, such as year, and the dashboard dynamically updates to reflect the chosen time period, providing an efficient way to track performance.



## Problem Statement
The task was to create an interactive dashboard that tracks Key Performance Indicators (KPIs) and visualizes sales and profit data across multiple years. The dashboard must enable users to filter data by year, location, and product categories, and automatically update based on selected filters. The ultimate goal is to allow users to make data-driven decisions by comparing metrics such as sales and profits, both on an aggregate level and by subcategories


### Steps followed 

- Step 1 : The sales dataset, in CSV format, was loaded into Tableau. The data covers sales and profit figures across multiple years, and various regions, including Europe and the USA.

- Step 2 : The dataset was thoroughly checked to ensure that columns containing numerical values were formatted correctly. Any discrepancies, such as string values in numeric fields, were addressed. Special attention was paid to different number formats—comma (',') is used in Europe, while the period ('.') is used internationally. This difference was handled to maintain data consistency. 

- Step 3 : A clear and informative title was added to the dashboard, along with appropriate labels for charts, KPIs, and filters. The layout was designed to be intuitive and user-friendly.

- Step 4 : The first KPI chart was created to show Total Sales for the selected year, with a comparison to the previous year. Users can filter the data based on year, category, and region. The chart also highlights the highest and lowest sales months, with the ability to track month-over-month performance trends.

![Screenshot 2024-10-06 at 16 31 40](https://github.com/user-attachments/assets/9a8c4db1-a5df-438a-be71-31ce0f17741c)


- Step 5 : A similar KPI chart was created for Total Profit. This chart shows profit performance by month, including current year profits, previous year profits, and the percentage difference between the two. Like the sales KPI, this chart can be filtered based on different parameters such as Order Month, Profit, Location, and Product Category.

![Screenshot 2024-10-06 at 16 33 34](https://github.com/user-attachments/assets/c5320eec-12d5-41aa-92f5-e429d74faeb9)



- Step 6 : Filter buttons were added to the top corner of the dashboard. When clicked, these buttons reveal filtering options for Year, Category, Sub-Category, and Location. This functionality makes the dashboard interactive and allows users to drill down into specific data points with ease. 

![Screenshot 2024-10-06 at 16 38 32](https://github.com/user-attachments/assets/bde3fc77-584d-481b-af93-786467e224c5)

- Step 7 : This bar chart visualizes Sales and Profit by Subcategory, with side-by-side comparisons between the current year (dark bars) and the previous year (light gray bars). The chart provides an overview of which subcategories performed well or underperformed compared to the previous year. On the right-hand side, the chart also displays profit margins or losses for the current year. Like other elements in the dashboard, this chart is also filterable. 

![Screenshot 2024-10-06 at 16 44 52](https://github.com/user-attachments/assets/da77a5b2-3fcb-4ac8-b3b3-961bc819582f)


- Step 8 : Lastly, a trend chart was created to show Sales and Profit Trends over time. This chart uses color coding to differentiate between performance above and below the average. Above-average performance is marked in blue, while below-average performance is marked in dark orange. This visual helps quickly identify high and low-performing periods throughout the year.

![Screenshot 2024-10-06 at 16 47 37](https://github.com/user-attachments/assets/4b893b15-a894-4d5d-a2da-720feb875b87)



# Final Dashboard View : 
The final dashboard integrates all of the above elements, providing users with a powerful tool to monitor and analyze sales and profit data over multiple years. The layout includes KPIs, filter buttons, and detailed charts that allow for easy comparison and trend analysis.

![Screenshot 2024-10-06 at 16 48 16](https://github.com/user-attachments/assets/87e0e62b-7520-404e-bf9c-61931109a397)
