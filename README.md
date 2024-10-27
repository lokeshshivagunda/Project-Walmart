# Project-Walmart
Walmart Black Friday Sales 
About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.  


Business Problem  

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).  

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:  
Dataset link: Walmart_data.csv  

User_ID:	User ID  
Product_ID:	Product ID  
Gender:	Sex of User  
Age:	Age in bins  
Occupation:	Occupation(Masked)    
City_Category:	Category of the City (A,B,C)  
StayInCurrentCityYears:	Number of years stay in current city  
Marital_Status:	Marital Status  
ProductCategory:	Product Category (Masked)  
Purchase:	Purchase Amount  

INSIGHTS   
1.The data doesn't contain null values.  
2.We can detect outliers in purchases in gender wise, marital status and occupation by using box plot.  
3.We can see that married people are buying and spending products when compared to single, but the difference is not much.  
4.purchase of male is more likely than female and male bought more products than female.  
5.The Walmart female average purchase is an outlier, so it does not lie under the confidence interval in population data.  
6.unmarried purchase average is slightly more than married purchase average.  
7.Few of the age purchases of a confidence interval overlap so few of them are significant and not significant.  
8.Customer whose age is more than 17 are purchasing less products than other category age.  
9.customers who are living in C category are spending more than other followed by B and A.  
10.The most no of purchases made in city B.  
11.product_category 1,5 and 8 is the top leading product categories in 100 million customers worldwide.  
12.Customer whose occupation is 4,0,7,1 and 17 are likely to purchase more products.  
13.Customer who are staying 1 and 2 years in the city are purchasing more products than others.  

Recommendations   
1.The purchase of male is comparatively higher than female so it's better to recommend more different products and stocks for male.    
2.Similarly, we can recommend more different types of products for married customers and customers whose age is more than 17.    
3.We can put more no of departmental stores and grocery stores in city C and B as their avg spending and no of customers is more.     
