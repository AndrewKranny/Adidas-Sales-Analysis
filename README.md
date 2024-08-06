# Adidas Sales Analysis and Dashboard (2020-2021)
Analyzing Adidas sales trends from 2020-2021. Interactive PowerBI dashboard can be found [here](https://app.powerbi.com/reportEmbed?reportId=8a5dd84b-684c-4ad2-a01a-696131947d45&autoAuth=true&ctid=f5222e6c-5fc6-48eb-8f03-73db18203b63).

![image](https://github.com/user-attachments/assets/c97d9d5f-a670-429d-b23a-8e0ea70ca048)

## North Star Metrics and Dimensions
- *Sales*: Total sales from all product categories
- *Profit*: Net income generated to Adidas
- *Units Sold*: Total number of products sold
- *Sales Methods*: In-Store, Online, or Outlet
- *Product Type*: Men's Street Footwear, Men's Athletic Footwear, Men's Apparel, Woman's Street Footwear, Woman's Athletic Footwear, and Woman's Apparel
- *Regions*: Midwest, Northeast, South, Southeast, and West
- *States*: All 50 U.S. states
- *Retailers*: Amazon, Foot Locker, Kohl's, Sports Direct, Walmart, and West Gear

## Summary of Insights
### Monthly Sales
- At the beginning of the pandemic, sales breifly spiked in April 2020, generating the most sales and profit of 2020. Shortly after, however, the sales and profit in June significantly decreased to around half of the previous month. 
- Total sales in in 2020 made up only 20% of the total sales across 2020 and 2021, with sales in 2021 making up the other 80% - investigate whether or not this is consistent with other athletic brands, or is an issue with marketing, faulty products, etc...

### Sales Methods
- Interestingly enough, Online sales made up only 2% of the profit during the height of the pandemic in 2020.
- Over both 2020 and 2021, Online sales generated the least amount of profit while being the most utilized sales method according to units sold.

### Sales Region
- The West region of the U.S. was by far the largest consumer of Adidas products, bringing in around 30% of the total sales. The west region also has the largest profit margins of all the regions at 66.8%

## Recommendations & Next Steps
- Investigate why online sales are lacking behind both in-store and outlet sales in terms of profit while online sales are ahead in units sold - consider altering operating margins for online sales
- Investigate why online sales did so poorly during the height of the pandemic in 2020, consider checking to see if our data is consistent with other athletic brands
- Holiday season sales in 2020 were of some of the lowest across both 2020 and 2021, while holiday season sales in 2021 were some of the highest profit generating months, consider obtaining more detailed data from late 2020 to understand the lack of sales

## Data Cleaning in Python
Data cleaning and initial EDA in Python can be found [here](https://github.com/AndrewKranny/Adidas-Sales-Analysis/blob/main/Adidas%20Sales%20EDA.ipynb)
