# Real Estate Project

## Results

* We analysed the real estate data base of ads for the sale of apartments in St. Petersburg and the region for several years.
* We prepared the data cutting around 5% of raw data due to anomalies in prices, area, number of rooms, and ceiling height.
* We managed not to shift significantly the mean and median of price/m2 compared to an original data which is great. Moreover, those measures even became closer to each other which shows the robustness of the clean data.
* Analysing the duration of the postings we came to a conclusion that the fast sale takes around 1,5 months, and super long sale is more than 1,5 years.
* Comparing St.Petersburg center to the whole data base, we got to the point that an average price for a posting is 33% higher for the central flats, the price/m2 is 11% higher, and the duration of the posting is 22% longer on average.
* Both datasets have clear positive linear dependencies on total area and number of rooms.
* As expected, the median price of the posting depending on the distance to city center is going down the farer it is.
* Everywhere the highest median prices/m2 are not for the first or last floors.

## Scope of the project

**The goal**:
- Determine the market value of real estate. 
- Set the right parameters for the automated system that tracks anomalies and fraudulent activity.

**Input data**: real estate data base of ads for the sale of apartments in St. Petersburg and the region for several years.  
Two types of data are available for each apartment for sale:
- The first ones are entered by the user.
- The second ones are obtained automatically on the basis of cartographic data (the distance to the center, airport, nearest park and pond).

**Analysis structure**:
* Data overview
* Data preparation
* Exploratory data analysis
