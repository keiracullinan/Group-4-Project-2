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
How was the housing market affected by the Housing Recession in 2008? Display this using data from 2005 to 2012.

## Question 2
For residential property types, how does proximity to New York City affect the average sale price of homes in 2020 and 2021? List the 10 towns with the highest average residential sale price on a bar graph as well.
