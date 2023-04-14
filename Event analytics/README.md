# Event analytics project

## Results

* We had raw data from the food-tech app log  
* Data was in the time period from 2019-07-25 to 2019-08-07  
* There were initially 243713 events and 7551 unique users in the log  
* We have sliced the data starting from 2019-08-01 due to the significantly low number of events in the first week
* We have also deleted the duplicated rows  


* We found out that there is a clear sales funnel: **Main screen -> Offers screen -> Cart screen -> Payment success screen**
* Around 48% of users who entered the Main screen successfully proceeded to the payment
* Almost all the users who got to the Cart stage proceed to the payment: only 5% of users stop at this moment
* The biggest stuck point is going from stage 1 to stage 2, i.e. from Main to Offers screen, - almost 40% of users stop there  


* Having checked the results of A/A test, we could not reject H0 hypothesis as there is no statistical significant difference in data both on combined and on each step level; meaning that the test was done properly
* We have done 3 full A/B tests (i.e. comparing groups 246 and 248, groups 247 and 248, groups 246+247 combined and 248)
* We have done 12 A/B tests for each step with the same groups as above
* Nevertheless, **we have also not found stat. significant diff. between both control groups and experimental group** both on combined and on each step levels
* Moreover, after combining 2 control groups together we still **we have not found stat. significant diff. between combined control groups and experimental group** both on total and on each step levels
* As a main conclusion, there is no statistically significant difference in users' behaviour with the new font, so there is no need to get the new font in the full production

## Scope of the project

**The goal**:
- We need to understand users' behaviour in the app
- We need to analyse sales funnel and get an idea of how many users get to the sale and how many get stuck in the previous steps
- We also need to interpret A/A/B tests results

**Input data**: 
- We are analysts in the food tech start-up
- We have raw data from the app log

**Analysis structure**:
* Data overview
* Data preparation
* Basic EDA
* Sales funnel
* A/A/B tests
* Results
