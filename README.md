# Uber-Market_Analysis


## Author
**[Leah_Shin][https://github.com/Shinleah]**


# Uber Market Analysis from Statistics Canada data with Excel and Power-Bi 
![alt text](https://github.com/Shinleah/Uber-Market_Analysis/blob/main/Uber%20Market%20Analysis/Uber.PNG)
* (Image from Uber)

## Project Objective
* This report explores how Uber can leverage data to understand customer behaviour, preferences, and regional trends in Canada, enabling informed decisions for service expansion and diversification.

## Dataset
* The dataset can be accessed from Statistics Canada: 
[Household spending by household type](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1110022401),
[Population and dwelling counts: Canada, provinces and territories](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=9810000101),
[New motor vehicle sales](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=2010000101&pickMembers%5B0%5D=1.1&pickMembers%5B1%5D=2.1&pickMembers%5B2%5D=3.1&pickMembers%5B3%5D=5.1&cubeTimeFrame.startMonth=04&cubeTimeFrame.startYear=2019&cubeTimeFrame.endMonth=08&cubeTimeFrame.endYear=2023&referencePeriods=20190401%2C20230801)
[Main mode of commuting by commuting duration, time leaving for work, age and gender: Canada, provinces and territories, census metropolitan areas and census agglomerations with parts](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=9810045701)

## ERD Model
* Created primary key using the composite method.
* Referenced original query to create new queries with keep granularity.
* Created one-to-many relationships, using star schema. (one fact table with multiple dimensions table)
![alt text](https://github.com/Shinleah/Uber-Market_Analysis/blob/main/Uber%20Market%20Analysis/ERD.PNG)

## Data Analysis
* Data cleaning is performed by power query (M query) and DAX measures.
* Made sure data was normalized and kept granularity, dropping unnecessary rows, and cleaning individual rows.
* Developed the interactive Dashboard based on relevance, appropriate visualizations, colour and data labels, and narrative.
* By adhering to these principles, the Power BI dashboard aided in communicating intricate information to facilitate meaningful data analysis and informed decision-making for stakeholders.


## Questions
The following questions are identified to capture key measurements:

* What are the provincial and regional trends in commuting hours within Canada?
* What trends can be observed in transportation preferences and customer behaviour between provinces and regions?  
* What are Canada's provincial and regional trends in average household spending?
* What is the relationship between vehicle sales and the usage of alternative transportation methods across different provinces/regions in Canada?
* Which province or region has the highest population growth in Canada? 


## Dashboard
![alt text](https://github.com/Shinleah/Uber-Market_Analysis/blob/main/Uber%20Market%20Analysis/Summary%20Dashboard.PNG)


## Conclusion

* Peak transportation demand occurs between 7 am and 8:59 a.m., signalling the need for tailored strategies. 
* Shorter commutes are becoming prevalent, impacting consumer preferences. Private transportation remains favoured across regions, with cars, trucks, or vans being the top choices. 
* Further research is crucial to understand Uber’s market presence accurately. Householding spending priorities highlight transportation expenses at 14.55%, informing Uber’s pricing strategies. 
* Provinces like Ontario, Quebec, and Nova Scotia show higher vehicle sales and reliance on private vehicles for commuting, guiding Uber’s expansion plans.
* Prince Edward Island and British Columbia’s rapid population growth signals increasing transportation needs, prompting strategic resource allocation for Uber. 
* Overall, Uber can use the relationships between the data sets to help strategically expand their services in different provinces.
