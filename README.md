# Amazon_Sales_Analysis

1.	Data Quality and Cleansing:
o	Missing Values Identified: Several columns in the dataset, including Ship City, State, Postal Code, Country, Promotional Ads, Fulfillment Status, and an unnamed column, had significant blanks. These missing values were addressed to ensure accurate analysis.
o	City Name Cleansing: The City column initially contained special characters and extraneous spaces
o	Currency and Amount Corrections: The Currency column had blanks that were replaced with 'NA,' indicating that these orders were canceled. Similarly, the Amount column, which also had blanks, was cleaned by replacing these with a value of 0.
o	Duplicate Handling: Duplicates were checked and addressed.
o	Data Type Conversion: The data was thoroughly reviewed for correct data types, with necessary conversions made to relevant formats
o	Blanks Handling: Blanks in critical columns like Courier Status were replaced with 'NA,' and other categorical columns with blanks, such as City, State, Country, Promotional Ads, Fulfillment, and Postal Code, were appropriately handled by replacing blanks with 'NA' or 0 where applicable.
2.	Final Data Readiness:
o	The dataset is now cleaned and prepped, with all necessary corrections made. The data is ready for further analysis and visualization, providing a strong foundation for developing an interactive and insightful Amazon Sales dashboard in Power BI.
These steps have ensured the data is clean, well-structured, and ready for detailed analysis.

Overall Insights and Recommendations for Amazon Sales Dashboard

Insights 

Insights for Amazon Sales Dashboard



1.Overall Sales Performance:

 Total Sales:

 The platform generated a total of 76.03M in sales.
Top Categories:

  The most popular categories are Set (38.99% of total sales), Kurta (38.67% of total sales), and Western Dress.


2.Sales Channels Breakdown:

 Amazon.in:

 Contributed the entire sales amount of 76.03M.
Non-Amazon.in:

 No sales were reported through this channel.


3.B2B vs. Non-B2B Sales:

 Non-B2B Sales:

 75.42M was generated, with the fulfillment split as follows:
          Fulfillment by Amazon: 54.32M in sales from 88,993 orders. 

          Fulfillment by Merchant: 21.10M in sales from 38,987 orders.

B2B Sales:

 Total B2B sales amounted to 617.18K.
         Fulfillment by Amazon: 392.36K in sales.  

         Fulfillment by Merchant: 224.82K in sales.


         4) Fulfillment Insights:

Amazon Fulfillment (Non-B2B):

Top Categories:
 Kurta and Set lead, with Kurta contributing 39.73% and Set 39.62% of total sales.  
Shipments:
 30,500 Kurtas and 30,370 Sets were shipped, with the highest sales recorded in April 2022, especially in Karnataka, Telangana, and Maharashtra.


Merchant Fulfillment (Non-B2B):

Top Categories:
 Set and Kurta, with Set accounting for 37.52% and Kurta 36.28% of total sales.  
Shipments:

  11,808 Sets and 11,406 Kurtas shipped, with most orders placed in Maharashtra, Karnataka, and Telangana.


B2B Sales Insights:



Amazon Fulfillment (B2B):

Top Categories:
 Set (39.59% of sales) and Kurta (37.52% of sales).  
Shipments:
  207 Sets and 202 Kurtas shipped, with Uttar Pradesh, Karnataka, and Maharashtra leading in order placements.


Merchant Fulfillment (B2B):

Top Categories:
 Kurta (37.93% of sales) and Set (37.93% of sales). 
Shipments:
 104 Sets and 96 Kurtas shipped, with the highest sales in April 2022 from Punjab, Maharashtra, and Telangana.


6.Correlation Between Sales and Promotions:

A strong correlation (0.94) was found between total sales and promotional IDs. The correlation analysis, segmented by city and category, reveals significant insights into how promotions drive sales across different regions and product categories.


Final Recommendations

Prioritize Top Categories:

Focus marketing and inventory strategies on the top-performing categories, Set and Kurta. Consider expanding these product lines and offering exclusive promotions to further boost sales in these categories.

Maximize the Impact of Promotions:

Given the strong correlation between promotional IDs and sales, refine promotional strategies by analyzing past successes. Tailor promotions to specific cities and categories, ensuring they are deployed where they will have the most significant impact.

Enhance Shipping and Fulfillment Efficiency:

Optimize shipping processes, particularly for expedited orders, to reduce cancellations and improve customer satisfaction. Consider offering more flexible shipping options and improving fulfillment practices, especially for high-volume categories like Set and Kurta.

Strengthen Fulfillment Channels:

Evaluate the performance of both Amazon Fulfillment and Merchant Fulfillment channels. Focus on optimizing the most successful channels, while also exploring ways to enhance the efficiency of those underperforming.

Target Key Regions with Tailored Strategies:

Concentrate marketing efforts in high-performing regions such as Karnataka, Telangana, and Maharashtra. Analyze sales patterns to identify peak seasons and align promotional activities to capitalize on these periods.



By implementing these recommendations, the business can enhance its overall sales performance, improve operational efficiency, and effectively target key market segments.
