# Marketing project

## Results

* We had data for new users who registered in the period from 2019-05-01 to 2019-10-27
* Our observation date was 2019-11-01 and analysis horizon 14 days
* In this period there were a bit more than 150k unique users
  
  
* The highest number of **unique users are coming from the US (around 2/3)**
* The **US has also the highest portion of paying users** - around 7%
* Most of the unique users are using **iPhone**, while among the **Mac** users - the highest proportion of paying ones
* The highest proportions of paying users are coming from **FaceBoom, AdNonSense, and lambdaMediaAds** channels: around 12%, 11%, and 10%, respectively
* Organic source, not surprisingly, has the lowest proportion of payers with **a bit more than 2%**
  
    
* Total marketing costs in the period of analysis were 105497
* Costs across channels were not distributed uniformly: two channels - **TipTop and FaceBoom** - got the biggest portions of total marketing costs (52% and 31%, respectively)
  
  
* Overall, the advertising in the period of analysis was **not paying back within 14 days horizon**
* This is **due to skyrocketed CACs over time** (as LTV was pretty stable = over time going up and down within the channel)
* The advertising on **TipTop, FaceBoom, and AdNonSense platforms were not profitable**
* Across countries, the **United States had the biggest downward pressure on ROI** and didn't reach a profit
* **FaceBoom and AdNonSense platforms** have significantly low retentions while having the highest conversion rates

## Recommendation to the marketing team

* We did some filtering out different regions and channels and came to the conclusion that it would be appropriate to stop advertising on **TipTop, FaceBoom, and AdNonSense** platforms
* By "killing" these two platforms we **lose around 56% of all our non-organic users**, but improve the marketing financials significantly
* In such a case, the pay back is happening on the **4th day already**
* On the 14th day the ROI is **around 2** 
* Moreover, that would **save up to 87% of marketing costs**

When we look at the payback without three unprofitable platforms (TipTop, FaceBoom, and AdNonSense), we see that:

* In terms of countries, advertising in the USA even turns out to be the most profitable due to the lowest CAC; advertising in other countries is just as profitable and pays off quickly
* Of the European countries, the United Kingdom stands out - there the figures are slightly higher than in Germany and France
* In terms of devices, advertising pays off everywhere, although there is a large variability in LTV on all devices
  
  
* In terms of platforms, in the USA **YRabbit** is the most profitable platform due to lowest CAC
* Also **there is a great downward trend in CAC on the RocketSuperAds platform** in the US, despite the fact that it generates the highest LTV = should be further observed in the dynamics of CAC, as it has the chance to become very profitable
* In Europe, the most profitable platform is **lambdaMediaAds**, even though it has the highest CAC
* We also need to keep an eye on the **LeapBob platform** as it has great potential

**The goal**:
- Analyse the marketing to see whether advertising pays off
- Understand which devices, countries, and advertising channels can negatively impact ads ROI
- Investigate what can cause payback problems
- Explore conversion and retention by device, country, advertising channel

**Input data**: 
- We are marketing analysts for the entertainment app Procrastinate Pro+
- For new users who registered in the period from 2019-05-01 to 2019-10-27 we have server log data with:
    - Visits
    - Purchases 
    - Advertising costs
- The date of analysis: 2019-11-01
- It is generally accepted that payback should occur no later than **2 weeks** after user acquisition

**Analysis structure**:
* Data overview
* Creating functions to calculate main metrics
* EDA
* Marketing analysis
* Return on advertising
* Results
* Recommendation to the marketing team
