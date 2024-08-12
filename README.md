# Sales Analysis for Adidas 📊

## Company Overview  🏢
Company Name: **Adidas**

### Background:
<div align="justify"> Adidas is a globally recognized leader in the sportswear and athletic footwear industry. Established with a focus on innovation and quality, Adidas has expanded its product lines and market presence significantly over the years. The company operates a broad network of retail partners and maintains a strong global brand presence.</div>

### Operational Model
**Retail Network:** Extensive network of retail partners and direct-to-consumer sales channels.

**Product Range:** Diverse portfolio including footwear, apparel, and accessories.

**Sales Channels:** Sales through various methods, including physical retail stores, online platforms, and third-party retailer

### Role and objective: 👩‍💻
As a Junior Data Analyst at Adidas, my main objective is to leverage the sales dataset to support the development of marketing strategies and sales improvements.

In order process further steps, we follow these steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.

### **Data Analysis Process** 🔍
1. **Ask:** Define key questions to guide the analysis, focusing on product profitability, sales method performance, and geographic sales distribution.

2. **Prepare:** Load and organize the Adidas sales dataset, ensuring data quality through cleaning and transformation.

3. **Process:** Clean and transform data using tools like Power BI, addressing duplicates, missing values, and ensuring valid sales metrics.

4. **Analyze:** Generate insights from the data, including sales performance, product demand, and regional trends, using visualizations and metrics.

5. **Share:** Present findings through interactive dashboards and key visualizations to communicate insights effectively.

6. **Act:** Implement recommendations based on analysis, track performance, and continuously refine strategies for improved sales and profitability.

### Detailed Steps
## Stage 1: Ask ❓
The final list of questions to analyze are:
1. Which product category contributes the most to overall profit, and how can we leverage this information to enhance our sales strategy?
2. How does the performance of different sales methods (in-store, online, outlet) compare, and what strategies can we implement to improve the performance of the least profitable method?
3. Which regions and states show the highest sales performance, and how can we tailor our marketing efforts to further boost sales in these high-performing areas?

## Stage 2: Prepare 🛠️
For this analysis, we are using the Adidas Sales Dataset in United States [link of dataset](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset/data) from year 2021 to 2022. After that, we extract the file and relocate it to the "Adidas_Sales_Analysis" folder. The csv file is now called "Adidas_US_Sales." To address any future accidents, we duplicate the folder and files to another folder.

### Metadata Description 🗃️
The dataset includes the following fields:
- **Retailer:** Name or identifier of the retail store.
- **Retailer ID:** Unique identifier assigned to each retailer.
- **Invoice Date:** The date when the invoice was issued for the transaction.
- **Region:** Geographic region where the retailer operates.
- **State:** State within the region where the sale occurred.
- **City:** City within the state where the sale took place.
- **Product:** Description or name of the product sold.
- **Price per Unit:** The price of a single unit of the product.
- **Units Sold:** Number of units of the product sold.
- **Total Sales:** Total revenue generated from the sale of the product.
- **Operating Profit:** Profit earned from the sale of the product, calculated as Total Sales minus the cost of goods sold and operating expenses related to the product.
- **Operating Margin:** Ratio of Operating Profit to Total Sales, expressed as a percentage, indicating the profitability of the product.
- **Sales Method:** The method used to sell the product.

### Data Reliability and Quality 📉
- **Reliability:**  The dataset includes different category of data.
- **Originality:** The dataset is unique and provide new insights, under this [license](https://creativecommons.org/publicdomain/zero/1.0/).
- **Comprehensive:** The dataset covers various aspects of sales, including price per unit, total sales, units sold, operating profit etc.
- **Current:** The dataset is from 2023, but it lacks update.
- **Cited:** The dataset is cited.

## Stage 3: Process ⚙️
The following steps were performed to clean and prepare the data for analysis:
1. Loading Data: The data was loaded for further analysis in Power BI.
2. Data Inspection: The structure and contents of each data frame were inspected to ensure consistency.
3. Data Cleaning:
   -	We transform the loaded data using Power Query.
   -	We checked for duplicate and missing values in every column.
   -	We detect the datatype of every column and change the datatype if necessary.
   -	We also ensured all sales value were valid and verify if there are any negative values and zeros in ‘price per unit’, ‘unit sold’ column which may need correction.
4. Data Transformation:
   - Aggregated sales data to the required details (profit margin in percentage, sales, units sold)

## Stage 4: Analyze 📈
### Data Insights 🔍

### Sales Performance:

![image](https://github.com/user-attachments/assets/98053a7c-1b1e-4131-96bb-56b8dd6d29ba)

Findings from the plot:
- Adidas has achieved a total sale of $899.90 million.
- The total profit is $332.1 million with profit margin of 36.9%
- There is total 9648 retailers.

### Demand by Product Category:

![image](https://github.com/user-attachments/assets/4080d8e0-e267-43f6-ac3b-fa5117790071)

Findings from the plot:
- Men's Street Footwear is the leading category with around 593,000 units sold, accounting for 23.94% of total sales.
- Men's Athletic Footwear and Women's Apparel follow, with around 436,000 units (17.57%) and around 434,000 units (17.5%) sold respectively.
- Men’s Apparel is the least sold item with around 307,000 units (12.37%).

### Product Performance:

![image](https://github.com/user-attachments/assets/152ab41e-0978-4452-b950-f11d7e6c95fa)

Findings from the plot:
- Men’s Street Footwear generate highest sales amount with over 208 million with profit margin of 39.7%.
- Women’s Apparel and Women’s Athletic Footwear follow, with over 179 million (profit margin of 38.3%) and 106 million (profit margin of 36.6%).
- Men’s Athletic Footwear generates substantial revenue, but it has lowest profit margin of 33.7% with total sales over 153 million compared to others.

### Sales by Quarter:

![image](https://github.com/user-attachments/assets/4576d820-e086-4de9-911f-cd452587ee62)

Findings from the plot:
- The sales peak in Q3 at 265 million followed by 218 million in Q4. This suggests a season trend.
- Q2 peaks at 228 million and Q1 at 189 million which is also the least sales quarter.

### Geographic Sales:

![image](https://github.com/user-attachments/assets/cdf1dab1-3bbc-4f05-9ff2-b1d6ac637b9a)

Findings from the plot:
- New York, California and Florida are the top-performing states in terms of sales.
- North Carolina and Louisiana are the least-performing states in terms of sales.
  
> [!NOTE]
> These screenshots represent only a small sample of the total data available.

![image](https://github.com/user-attachments/assets/38256b89-c8c7-4692-b137-6e696406ef63)

Findings from the plot:  
- The units sold are well-distributed across regions, with the West leading at 686,985 units and Midwest with least at 391,337 units.

### Retailer Performance:

![image](https://github.com/user-attachments/assets/638f4c67-80dd-48ac-84b6-178daac10f53)

Findings from the plot:
- Retailer ‘Foot Locker’ gains highest total profit of around 10.9 million with a profit margin 38.9% which is located in Charleston.
- West Gear and Sports Direct follow, with over 9.8 million (profit margin of 29.5%) in San Francisco and over 9 million (profit margin of 52.3%) in Birmingham which is also highest profit margin.
- Retailer ‘Foot Locker’, located at Knoxville, generate low profit around 122 thousand with profit margin of 38.2%.

> [!NOTE]
> These screenshots represent only a small sample of the total data available.

### Sales Method Analysis

![image](https://github.com/user-attachments/assets/051cd7a3-12f2-499d-83a7-3900e9253e39)

Findings from the plot:
- The majority used sales method is in-store sales (39.63%), followed by outlet sales (32.85%) and online sales (27.52%).

### Sales by Retailer

![image](https://github.com/user-attachments/assets/e84cdd32-01b1-483b-9299-98b92d4781f6)

Findings from the plot:
- West Gear (243 million) and Foot Locker (220 million) are the leading retailers by total sales, followed by Sports Direct (182 million) and Kohl’s (102 million).
- Amazon (78 million) and Walmart (75 million) are the least retailers by total sales

## Stage 5: Share 📤
### Dashboard Visuals 📊
**Interactive Dashboard:** Created using Power BI, providing insights into sales performance.

### Key Visuals:
- Pie charts for product category demand and sales methods.
- Bar charts for sales by state and retailer performance.
- Line chart for sales by quarter.
- Map visualization for geographical sales distribution.

Here is the sample of dashboard:

![image](https://github.com/user-attachments/assets/7931844d-504f-4ca3-b477-06577d500abc)

<p align="center"><strong> Fig: Landing Page </strong></p>

![image](https://github.com/user-attachments/assets/f76d1367-0942-47f5-9cea-a5844cc38bdd)

<p align="center"><strong> Fig: Home Page </strong></p>

![image](https://github.com/user-attachments/assets/1183d89f-50b7-4d41-8d34-b5a8f01b0df1)

<p align="center"><strong> Fig: Retailer Page </strong></p>

The dashboard provides a comprehensive view of Adidas’ sales performance, highlighting key areas of strength and opportunities for growth. By leveraging these insights, Adidas can refine its strategies to drive higher sales, improve profitability, and enhance customer satisfaction.

You can download and access the dashboard from the following link: [Power BI Dashboard](https://github.com/SaileshBasnet/Sales-Analysis-for-Adidas/blob/main/Adidas%20Sales%20Analysis.pbix)

## Stage 6: Act 🚀
### Recommendations & Suggestions
After analyzing everything we conclude to this decision for further improvement:

- **Enhance Sales Strategy:**
Focus marketing efforts on top-performing product categories like Women's Apparel and Men's Street Footwear to leverage their high profit margins and sales figures.

- **Improve Sales Method Performance:**
Analyze the underperformance of the online sales method and develop targeted strategies such as online promotions, better user experience, and exclusive online product offerings to boost online sales.

- **Tailor Marketing Efforts:**
Concentrate marketing campaigns in high-performing states like New York, California, and Florida.

- **Customer Engagement:**
Enhance or introduce loyalty programs to encourage repeat purchases and increase customer retention.

- **Local Events and Sponsorships:**
Participate in or sponsor local events to increase brand visibility and connect with the community.

### Next Steps 📅
- **Implement Recommendations:** Begin executing targeted marketing campaigns for high-profit product categories (e.g., Men's Street Footwear and Women's Apparel). Focus on enhancing the online shopping experience and local marketing efforts in high-performing states (New York, California, Florida).
  
- **Track Performance:** Monitor KPIs such as sales growth, profit margins, and conversion rates on an ongoing basis, with regular updates. Adjust strategies based on performance data.
  
- **Continuous Improvement:** Regularly review marketing and operational strategies based on data and feedback. Make monthly reviews and quarterly adjustments to optimize results and address emerging issues

## Executive Summary 📝
<div align="justify"> This analysis provides an in-depth look into Adidas’ sales performance from 2021 to 2022. Key findings include the leading product categories and sales methods, regional performance variations, and retailer effectiveness. Recommendations focus on enhancing sales strategies, improving underperforming sales methods, and leveraging high-performing states for targeted marketing. The proposed actions aim to drive higher sales, improve profitability, and enhance customer engagement.</div>


