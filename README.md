# Amazon_Sales_Analysis

# 1.	Data Quality and Cleansing:
# Missing Values Identified: 
Several columns in the dataset, including Ship City, State, Postal Code, Country, Promotional Ads, Fulfillment Status, and an unnamed column, had significant blanks. These missing values were addressed to ensure accurate analysis.
# City Name Cleansing: 
The City column initially contained special characters and extraneous spaces
# Currency and Amount Corrections: 
The Currency column had blanks that were replaced with 'NA,' indicating that these orders were canceled. Similarly, the Amount column, which also had blanks, was cleaned by replacing these with a value of 0.
# Duplicate Handling:
Duplicates were checked and addressed.
# Data Type Conversion: 
The data was thoroughly reviewed for correct data types, with necessary conversions made to relevant formats
# Blanks Handling: 
Blanks in critical columns like Courier Status were replaced with 'NA,' and other categorical columns with blanks, such as City, State, Country, Promotional Ads, Fulfillment, and Postal Code, were appropriately handled by replacing blanks with 'NA' or 0 where applicable.
# Final Data Readiness:
The dataset is now cleaned and prepped, with all necessary corrections made. The data is ready for further analysis and visualization, providing a strong foundation for developing an interactive and insightful Amazon Sales dashboard in Power BI.
These steps have ensured the data is clean, well-structured, and ready for detailed analysis.

# Overall Insights and Recommendations for Amazon Sales Dashboard

# Insights for Amazon Sales Dashboard
# 1.Overall Sales Performance:
# Total Sales:
1)The platform generated a total of 76.03M in sales.
# Top Categories:
1) The most popular categories are Set (38.99% of total sales), Kurta (38.67% of total sales), and Western Dress.

# 2.Sales Channels Breakdown:
# Amazon.in:
1) Contributed the entire sales amount of 76.03M.
# Non-Amazon.in:
1) No sales were reported through this channel.

# 3.B2B vs. Non-B2B Sales:
# Non-B2B Sales:
1) 75.42M was generated, with the fulfillment split as follows:
   Fulfillment by Amazon: 54.32M in sales from 88,993 orders. 
   Fulfillment by Merchant: 21.10M in sales from 38,987 orders.
# B2B Sales:
1) Total B2B sales amounted to 617.18K.
   Fulfillment by Amazon: 392.36K in sales.  
   Fulfillment by Merchant: 224.82K in sales.

# 4) Fulfillment Insights:
# Amazon Fulfillment (Non-B2B):
# Top Categories:
1) Kurta and Set lead, with Kurta contributing 39.73% and Set 39.62% of total sales.  
# Shipments:
 1) 30,500 Kurtas and 30,370 Sets were shipped, with the highest sales recorded in April 2022, especially in Karnataka, Telangana, and Maharashtra.

# Merchant Fulfillment (Non-B2B):
# Top Categories:
 1) Set and Kurta, with Set accounting for 37.52% and Kurta 36.28% of total sales.  
# Shipments:
1) 11,808 Sets and 11,406 Kurtas shipped, with most orders placed in Maharashtra, Karnataka, and Telangana.

# B2B Sales Insights:
# Amazon Fulfillment (B2B):
# Top Categories:
1) Set (39.59% of sales) and Kurta (37.52% of sales).  
# Shipments:
 1) 207 Sets and 202 Kurtas shipped, with Uttar Pradesh, Karnataka, and Maharashtra leading in order placements.

# Merchant Fulfillment (B2B):
# Top Categories:
 1) Kurta (37.93% of sales) and Set (37.93% of sales). 
# Shipments:
 1) 104 Sets and 96 Kurtas shipped, with the highest sales in April 2022 from Punjab, Maharashtra, and Telangana.

# 6.Correlation Between Sales and Promotions:
A strong correlation (0.94) was found between total sales and promotional IDs. The correlation analysis, segmented by city and category, reveals significant insights into how promotions drive sales across different regions and product categories.

# Final Recommendations
# Prioritize Top Categories:
Focus marketing and inventory strategies on the top-performing categories, Set and Kurta. Consider expanding these product lines and offering exclusive promotions to further boost sales in these categories.

# Maximize the Impact of Promotions:
Given the strong correlation between promotional IDs and sales, refine promotional strategies by analyzing past successes. Tailor promotions to specific cities and categories, ensuring they are deployed where they will have the most significant impact.

# Enhance Shipping and Fulfillment Efficiency:
Optimize shipping processes, particularly for expedited orders, to reduce cancellations and improve customer satisfaction. Consider offering more flexible shipping options and improving fulfillment practices, especially for high-volume categories like Set and Kurta.

# Strengthen Fulfillment Channels:
Evaluate the performance of both Amazon Fulfillment and Merchant Fulfillment channels. Focus on optimizing the most successful channels, while also exploring ways to enhance the efficiency of those underperforming.

# Target Key Regions with Tailored Strategies:
Concentrate marketing efforts in high-performing regions such as Karnataka, Telangana, and Maharashtra. Analyze sales patterns to identify peak seasons and align promotional activities to capitalize on these periods.

# By implementing these recommendations, the business can enhance its overall sales performance, improve operational efficiency, and effectively target key market segments.

# Final Dashboard View 

![Screenshot 2024-08-17 014611](https://github.com/user-attachments/assets/e97f6164-d03a-4c0f-9356-959d8b5d85fc)

# Correlation Analysis 
![Screenshot 2024-08-17 014623](https://github.com/user-attachments/assets/9afe918c-d8ec-48e3-b3f0-693f01e2903e)

# Tool tip with top 5 cities and states that place highest orders 
![Screenshot 2024-08-17 021832](https://github.com/user-attachments/assets/d8259140-c801-489c-95bd-b27c171885c8)


# Shipping type Graph
![Screenshot 2024-08-17 021758](https://github.com/user-attachments/assets/bd598d77-6463-4e1f-9e0f-4d55134081a4)


# Category and total orders placed 
![Screenshot 2024-08-17 021822](https://github.com/user-attachments/assets/9a2ff033-aab3-4695-99bf-35d7c50d4845)

# Percentage of orders placed by each category 
![Screenshot 2024-08-17 021717](https://github.com/user-attachments/assets/9469f7b3-4913-49d4-8632-5f14f6beb1fb)

# overall sales analysis over time 
![Screenshot 2024-08-17 021810](https://github.com/user-attachments/assets/260262fb-8054-407a-b5a6-632d6e6feec4)

# Courier Status by Category 
![Screenshot 2024-08-17 021746](https://github.com/user-attachments/assets/5a601c03-e085-41df-94eb-0426bd61a036)

# Total order under B2b by category
![Screenshot 2024-08-17 021731](https://github.com/user-attachments/assets/d5c73d3b-6c93-4c6b-a513-5bc073a943df)






