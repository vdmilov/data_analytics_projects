# Telecom Project

## Results

- We had a sample of monthly actions of 500 users in 2018 year (so in total could get 500x12=6000 data points)
- In only 54% of cases the revenue was generated due to the fact that some users joined the tariff when the year already started and some quited the tariff before the year end
- Out of the cases above the split between "Smart" and "Ultra" tariffs were around 70% and 30%, respectively
- Under "Smart" tariff users pay 1225 rubles on average monthly, while in 50% of cases they pay 950; both numbers are higher then the monthly tariff price due to the fact that users break the 'free' limits for everything quite a lot: calls, messages, and internet
- Under "Ultra" tariff users pay 2067 rubles on average monthly, while in 50% of cases they pay 1950 rubles; all the additional revenue generated above the tariff price comes only from the fees from the traffic being used above the limits
- "Ultra" tariff seems more preferrable for the telecom company due to the higher monthly mean revenue
- Comparing average revenues for "Smart" and "Ultra" tariffs samples, we can not conclude that they are equal (i.e. H0 is rejected)
- Comparing average revenues for both tariffs together in Moscow and other cities, we can not conclude that they are not equal (i.e. H0 is not rejected) as the t-test shows the statistically significant p-value

## Scope of the project

**The goal**:
- Find out which tariff is more profitable: "Smart" or "Ultra"

**Input data**: 
- Sample of 500 users' data points: who they are, where from, what tariff use, how many messages send and how much traffic use

**Tariffs description**  

*Smart*
- Price: 550 rub
- Includes 500 min, 50 messages, 15GB traffic
- Above this:
    - 3 rub/min
    - 3 rub/message
    - 200 rub/GB
  
*Ultra*
- Price: 1950 rub
- Includes 3000 min, 1000 messages, 30GB traffic
- Above this:
    - 1 rub/min
    - 1 rub/message
    - 150 rub/GB

**Important note**  
- Seconds are always rounded to minutes
- Megabytes are always rounded to gigabytes
- Traffic is summed for one month
- Unused minutes, messages, and traffic can not be shifted to new month

**Analysis structure**:
* Data overview
* Data preparation
* Data analysis
* Hypothesis testing
* Results
