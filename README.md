# Project Title
# ADVENTUREWORKS-Dashboard

https://github.com/Lognath2002/Powerbi/blob/main/powerbi%20project.pbix

## Problem Statement

This dashboard helps the ADVENTUREWORKS understand their customers better. It helps the ADVENTUREWORKS know if their customers are satisfied with their services. Through different returns, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average delay & departure time, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted delays.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab  to understand Insert a (KPI) card in the Exec Dashboard report page to show REVENUE,PROFIT,TOTALORDER,RETURNS Using Card visualizations.
![Image](https://github.com/user-attachments/assets/f04faeae-56f7-4bac-8b68-97e7b9d2d7b5)
- Step 3 :Add a background shape and match the formatting of the cards in the Exec Dashboard tab.
- Step 4 :Copy and paste to create a First card showing using a measure(DAX)function calculate The Total REVENUE and rename as Revenue.Measure:Revenue='Sales Data'[Retail Price]*'Sales Data'[OrderQuantity]
Total Revenue=Sum('Sales Data'[Revenue])

![Image](https://github.com/user-attachments/assets/e84a4da8-961a-46ff-8c32-df1bc512ecb3)
- Step 5 : Copy and paste to create a Second card showing using a measure(DAX)function calculate The Total PROFIT and rename as Profit.
- 
![Image](https://github.com/user-attachments/assets/8752871b-9290-4734-b772-103090a7f004)

- Step 6 :Copy and paste to create a Third card showing using a measure(DAX)function calculate The ORDER and rename as TotalOrder.Measure:Total Orders=DISTINCTCOUNT('Sales Data'[OrderNumber])
- 
![Image](https://github.com/user-attachments/assets/6666ca9c-d5cb-49a8-83ee-b07e4a15d3da)

- Step 7 :Copy and paste to create a Fourth card showing using a measure(DAX)function calculate The Total Return and rename as Return.Measure:return=Count('returns Data'[ReturnQuantity])
- 
![Image](https://github.com/user-attachments/assets/6e81aa5c-c9c3-43f3-85dc-ca66e77ce892)

- Step 8 :creating a LineChart to generate weekly Revenue in xaxis we a adding a start of week and in yaxis we are adding Total Revenue and rename as RevenueTrending and applying a zoom slider and apply the trend lines indicate the line is in up words or down words and applying forecast is the predicting analysis.
- 
![Image](https://github.com/user-attachments/assets/61d40766-68fa-4f87-90c4-89107da6ac43)
- Step 9 : For changing the tooltip background colour we need to go to properties and press the tooltip then we can customize according to dashboard colour.
- 
- Step 10 : A bar chart was also added to the report design area representing the number of Total orders in Accessories,Bikes,Clothing and changing the colour bar line to black and enable the data labels.
![Image](https://github.com/user-attachments/assets/799fdaef-5142-46b0-a4ef-9152500cb509)

- Step 11 : create a matrix to display a top 10 products in the matrix i rows i am adding ProductName in values i am going to add TotalOrder,TotalRevenue,ReturnRate converting basic filters to  top 10 productname in the By value terms of TotalOrders and press the applyfilter and applying cellelements and apply the databars for TotalOrder change the colour and applying icons and applying for returnrate and change the background colour.
- 
![Image](https://github.com/user-attachments/assets/34c6b66e-d053-49f1-8d09-b73504e829be)
- Step 12 : creating a KPI for previous month Revenue in value we are adding TotalRevenue and in TrendAxis we are adding start of month and in Target we are adding Previous month Revenue and rename as monthly revenue.
- 
![Image](https://github.com/user-attachments/assets/f2e6e0f0-60d5-4e5b-9de3-8a0f1c1beaef)
- Step 13 : creating a KPI for previous month orders in value we are adding TotalRevenue and in TrendAxis we are adding start of month and in Target we are adding Previous month orders and rename as monthly orders.
- 
![Image](https://github.com/user-attachments/assets/fbca20a1-1500-4aab-b818-5a6559234a99)
- Step 14 : creating a KPI for previous month Returns in value we are adding TotalRevenue and in TrendAxis we are adding start of month and in Target we are adding Previous month Returns and rename as monthly returns.
- 
![Image](https://github.com/user-attachments/assets/ac9b3a79-994b-4524-852c-0fb50e4c7210)
- Step 15 : creating a card in (KPI) and i am displaying the top sales subcategory product Name and applying visual level filter for top 1st product name in terms of Total Orders in the card and rename as Most Ordered Product Type.
- 
![Image](https://github.com/user-attachments/assets/29abeaa1-f84c-4600-b071-fa8f3c4fb720)
 - Step 16 : creating a card in (KPI) and i am displaying the top sales subcategory Name and applying visual level filter for top 1st subcategory name in terms of Return Rate in the card and rename as Most Returned Product Type.
 - 
 ![Image](https://github.com/user-attachments/assets/9b2cf8b4-d5b3-4c53-bfb9-75de21211fb0)
 - Step 17 : create a map visualizations and adding a country in locations and create a bubble size to increase a bubble size on the basics of total orders it will increase the size and creating a slicer is used for filtering in that i am adding the continent.
 - 
![Image](https://github.com/user-attachments/assets/94513be7-055d-4169-8cc1-59118be37591)
  - Step 19 : creating a gauge to generate a we achieved a target or not using a gauge visualization in values i am adding the total Revenue and maximum values adding the RevenueTarget and creating a visual filter adding the start of month and updating top 1 and values as last start of month and rename as Revenue.
  - 
  ![Image](https://github.com/user-attachments/assets/4d66977c-d895-4c5a-8173-34b91b49fc1f)
  - Step 20 : creating a gauge to generate a we achieved a target or not using a gauge visualization in values i am adding the total Profit in  maximum values adding the profit target and values as last start of month and rename as Profit.
  - 
  ![Image](https://github.com/user-attachments/assets/4dfe16b7-6dc0-4659-a53b-193b262523f4)
  - Step 21 : creating a gauge to generate a we achieved a target or not using a gauge visualization in values i am adding the total orders in  maximum values adding the orders target and values as last start of month and rename as Orders.
  - 
  ![Image](https://github.com/user-attachments/assets/77f0817c-d384-4463-bd08-b1388c290ff4)
  - Step 22 : creating a area chat to check the monthly profit in axis i am adding the start of month and in yaxis i am adding the total profit and rename as Profit Trends.
  - 
  ![Image](https://github.com/user-attachments/assets/6e968b11-54e1-4074-942a-d1b38c03a942)
  - Step 23 : creating a area chat to check the monthly profit in axis i am adding the start of month and in yaxis i am adding the total Returns and rename as  Returns Trends.
  - 
  ![Image](https://github.com/user-attachments/assets/b8527b9a-5a22-47dc-9980-52c9f80c3384)
  - Step 24 : creating a card in that card i am inserting a product name to display the name of the product.
  - 
  ![Image](https://github.com/user-attachments/assets/743e81c0-1828-4f0c-90d0-7547be2d1cfe)
  - Step 25 : create a visual level filter and in this format by default their is page information press and change the page type to drillthrough according to product name.
  - 
  ![Image](https://github.com/user-attachments/assets/ebcbf92b-9341-41fd-b1d1-41aa81c9d74c)
  ![Image](https://github.com/user-attachments/assets/a8daf419-360c-40f1-b6ec-e6930eb171f7)
  - Step 26 :create a button first we need to create a book mark in that and change the name to clear exec dashboard i am creating a button and in default the colour will be white on onhover stage the button colour will be different.
  - 
  ![Image](https://github.com/user-attachments/assets/a7384b78-b468-48e6-a2fb-101693379cf3)
  - Step 27 : creating a blank button and customize a button image and turn on the action choose the page navigation and change the destination to map.
  - 
  ![Image](https://github.com/user-attachments/assets/ad31d3b3-d324-4f76-a867-180cfcfdf7cd)
  - Step 28 : creating a blank button and customize a button image and turn on the action choose the page navigation and change the destination to productdetails.
  - 
  ![Image](https://github.com/user-attachments/assets/83fe71f3-dede-4e0b-823e-bb87acd70ffd)
  - Step 29 :create a numeric range and field parameter and create a measure for adjusted profit and add the adjusted profit in the area chat and creating a field parameter i am adding total revenue,total orders,total profit,total returns,return rate and customize the return trends in yaxis add the parameter.
  - 
  ![Image](https://github.com/user-attachments/assets/866197d4-ffcb-4499-b38b-a65cac4815b5)
  ![Image](https://github.com/user-attachments/assets/244536e5-0e4d-44e9-8009-747d95526aaf)
  - Step 30 : creating a multi row card for creating a tooltip i am adding total TotalRevenue,TotalOrders,TotalProfit,TotalReturns,ReturnRate and creating a area chart in the multirow card in xaxis we are adding the start of month and in yaxis total orders. 
![Image](https://github.com/user-attachments/assets/6f684e12-b5ad-4eb8-ab66-c87b42c52a3c)
 

 New measure was created to find  % of customers,
 
 Following DAX expression was written.,
 Total Revenue = SUMX('Sales Data','Sales Data'[OrderQuantity]*RELATED('Product Lookup'[ProductPrice]))
 Total Profit = [Total Revenue]-[Total Cost]
 Total Orders = DISTINCTCOUNT('Sales Data'[OrderNumber])
 Total Returns = COUNT('Returns Data'[ReturnQuantity])
 % of All Orders = [Total Orders]/[All Orders]
 10 Days rolling revenue = CALCULATE([Total Revenue],DATESINPERIOD('Calendar Lookup'[Date],MAX('Calendar Lookup'[Date]),-10,DAY))
 90-day Rolling Profit = CALCULATE([Total Profit],DATESINPERIOD('Calendar Lookup'[Date],LASTDATE('Calendar Lookup'[Date]),-90,DAY))
 adjusted price = [Avg Retail Price]*(1+'price Adjustment(%)'[price Adjustment(%) Value])
 adjusted profit = [adjusted revenue]-[Total Cost]
 adjusted revenue = SUMX('Sales Data','Sales Data'[OrderQuantity]*[adjusted price])
 All Orders = CALCULATE([Total Orders],ALL('Sales Data'))
 Avg Retail Price = AVERAGE('Product Lookup'[ProductPrice])
 Bulk Orders = CALCULATE([Total Orders],'Sales Data'[OrderQuantity]>1)
 Orders Profit = [Previous Month Profit]*1.1
 Overall Average = CALCULATE([Avg Retail Price],ALL('Product Lookup'))
 Orders Target = [Prev Month Orders]*1.1
 Prev Month Orders = CALCULATE([Total Orders],DATEADD('Calendar Lookup'[Date],-1,MONTH))
 Prev Month Returns = CALCULATE([Total Returns],DATEADD('Calendar Lookup'[Date],-1,MONTH))
 Prev Month Revenue = CALCULATE([Total Revenue],DATEADD('Calendar Lookup'[Date],-1,MONTH))
 Previous Month Profit = CALCULATE([Total Profit],DATEADD('Calendar Lookup'[Date],-1,MONTH))
 Weekend Orders = CALCULATE([Total Orders],'Calendar Lookup'[Weekend]="weekend")
 
 ![execDashboard](https://github.com/user-attachments/assets/9c538075-3821-40e1-9cc9-21dda02dd784)

# Map of Dashboard (Power BI Service)

![Map](https://github.com/user-attachments/assets/2ae36bb1-0b6c-4ce0-ae38-7dd869100b86)

 
 # Product Details Snapshot (Power BI DESKTOP)

![ProductDetails](https://github.com/user-attachments/assets/c341f5a8-adc1-4a10-bb72-9edc0aacfdda) 

