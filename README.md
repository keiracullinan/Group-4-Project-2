# **MIST4610 Group 4 Project 2**

## Team Name:
**61608 Group 4**

## Team Members:
1. Devin Davis [@dvndavis](https://github.com/dvndavis)
2. Hadden Peel [@hmpeel](https://github.com/hmpeel)
3. Kate Macken [@katemacken](https://github.com/katemacken)
4. Keira Cullinan [@keiracullinan](https://github.com/keiracullinan)
5. Lleyton Poole [@lleytonpoole10](https://github.com/lleytonpoole10)
6. Luke Burnett [@lukeburnett16](https://github.com/lukeburnett16)

## Description of DataSet
The dataset describes the real estate sales in Connecticut from 2001 to 2021. To obtain this data, we used the website provided, https://catalog.data.gov/dataset/real-estate-sales-2001-2018.  The dimensions of this dataset are 1,048,575 rows and 14 columns. Within this dataset, there are a variety of descriptions to explain each of the sales, such as a town, property address, and date of sale. Seven columns have the dimension type string: town, property address, property type, property assessment, assessor remarks, OPM remarks, residential type, and location. Within location, there are a couple with latitude and longitude coordinates. Within city, the data type was a string, but we edited the geographic role to city. In addition, two columns have the dimension of data: date recorded and list year. Sale amount, sale ratio, and difference are number (decimal). Serial number is number (whole). 

The first column, serial number, describes the serial number of the property listed. Following the serial number, list year describes the year that the property was listed on the market. Connected with this, the date recorded highlights the date, in month, day, and year, that the property was formally sold. Town, represented by a geographic role, lists the town in Connecticut where the property is located. More specifically, the address includes the specific street name and number. The assessed value is the price that the state of Connecticut assigns to the property. Assessed value takes into consideration location and property sales, along with many other factors. On the other hand, sale amount is the price that the property was sold for, which could be higher or lower than the assessed value. The sales ratio is the ratio of assessed value to market value, or sale amount, for the property that has been sold. Property types include many categories, such as residential, commercial, and vacant land. Residential type also includes many different categories of residential properties, such as multi-family homes, condos, and apartments. Non-use codes are used for properties that do not comply with zoning regulations, and it include explanations such as foreclosure, tax, and non-buildable lot. Assessor and OPM remarks include written notes about the properties that are in the market. Lastly, location includes the latitude and longitude of some of the properties. 


## Question 1
Question: How was the housing market affected by the Housing Recession in 2008? Display this using data from 2005 to 2012.

Importance: This question is important as it shows how the devastating recession of 2007 and 2008 affected the property market in the state of Connecticut. This question helps depict how the real estate market looked before, during, and after the recession. This can help the entire financial real estate industry by looking at how their past decisions can affect the housing market. By seeing the downward spiral in property prices as the economy headed into the recession, it is visible that the mistakes made by the banks on Wall Street had external effects on the real estate market. To illustrate this change, we chose to use a line graph that could represent a continuation in the property prices, and the difference in sale amount and assessed value. 

## Question 2
Question: For residential property types, how does proximity to New York City affect the average sale price of homes in 2020 and 2021? List the 10 towns with the highest average residential sale price on a bar graph as well.

Importance: This question is important as it can not only allow customers, but realtors as well to analyze the residential Connecticut real estate market as a whole across 2020 and 2021. This is valuable for realtors because it can show them the towns that they should focus their efforts to maximize their sales. This question is valuable for customers as it allows them to see how far their budget can stretch them in the market and also allows them to see how much they prioritize their distance from New York City. Customers can then have a discussion with their realtor to determine where they can realistically purchase their future home in Connecticut. To illustrate this, we chose to use a symbol map. 
