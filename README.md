# Data_cleaning_Chicago_Food_Inspection
The Chicago Department of Public Health has performed sanitation inspections for more than 15,000 food facilities across the City of Chicago each year, and has systematically collected the results of over 150,000 sanitation inspections from 2010 to 2017. These food inspections are beneficial to promote public health in areas of food safety and prevent the occurrence of food-borne illness. This project aims at cleaning the Chicago_Food_Inspection dataset and further analyzing the relationship between the food establishment types and locations in Chicago and the critical violations so as to assist the consumers in selecting the least risky food facilities and areas in Chicago.

## Check Risk Type
We use bar charts to examine risk types. More than 80,000 facilities are in low risk level, whereas only less than 20,000 are in low risk level.
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/22491f9d-8695-4e73-ada7-6866b72a34a3)

## Create separate data frame for visualizing risk percentage distributions by Zipcode
**Graph 1 - Choropleth map of risk distributions by Zip Code**
   
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/6f561d9f-fd9e-441e-bbb0-9f6f462b2875)![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/429e63bf-6091-4cb2-9bc4-9c5d8289a8ad)![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/18babc9d-0334-4522-bb86-4a370ae5be41)

Graph 1 shows the distribution of high, medium and low risk level by percentage of each risk level by Zip code in the map. Each area is labeled by Zip code and risk percentage. The proportion of high risk is more than 50% in most areas, and medium risk is about 10% ~ 20% correspondingly. The proportion of low risk is less than 10% in most areas. Only in the 60501 area, the low risk percentage reaches 75% which represents the most safe inspection area.

## Top 10 facility types and top 10 inspection types
Restaurant, grocery store and school are the top 3 facility types; canvass, License and canvass re-inspection are the top 3 inspection types.
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/faa52f4f-36c9-486c-9812-c32c255e303b)
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/cb0c1e01-0964-4af7-a666-ad3a0f7ebaee)

## Overall workflow
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/6a833f21-4474-4b68-a478-8a552506b666)

## Detailed representation of the inner data cleaning workflow
![image](https://github.com/xiaoyu-wen-1118/Data_cleaning_Chicago_Food_Inspection/assets/57936592/fb2052e7-500c-4d61-b971-4cca636330c7)
