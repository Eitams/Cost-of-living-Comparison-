# Cost of living Comparison
Cost of living comparison from Basel worker perspective living in Basel, Freiburg or Colmar.    
A complete ETL process as part of the Data Collection, Integration and Pre-processing course. 
  
The high cost of leaving and the constant increase in rental prices in Switzerland leads people to look for alternative accommodation options. The unique feature of Basel city, located at the corner of three countries, allows people to look for rental apartments not only within the country borders, but also in the nearby cities in France and Germany, in the hope for better accommodations.  
In this project we will gather data from three different rental agency websites, located in Switzerland, France and Germany. For a better comparison we will examine the rental prices in three major cities located within an hour from each other: Basel (CH), Colmar (FR) and Freiburg (DE).   

Key insights:  
![image](https://user-images.githubusercontent.com/62335786/152244312-b9e4c046-86d6-4e5b-bb5d-f8a21a1d7536.png)  

 ![image](https://user-images.githubusercontent.com/62335786/152243573-be46f1b2-6ff2-4db2-8313-d587bcc1aea4.png)  
 
We can see that although the apartment prices in Basel are higher,the net salary a person who earns 100,000 chf/year after deductions of the taxes, commuting costs and renting prices for the smaller size apartments is higher in Basel.  
The bigger the apartment gets the differences are getting smaller, where for apartments sized 105-154 [m2] the net salary is preety even between all 3 cities(small advantage for leaving in colmar). * Bigger apartments at the range of 154-202 [m2] will result in significant higher net salary for a person leaving in Freiburg then in basel.  

One importent thing to mention- the data we have for bigger apartments is limited. A bigger data source should be examine for a more relaible comperession in this range.  
Additional factors such as health insurance prices and daily expances that may effect those reasults were not taking into considuration in our calculation


Tools: mariadb, python including pandas, BeautifulSoup, mysql.connector and sqlalchemy
 
