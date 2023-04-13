# Banking project

## Results

* We had users data from regional bank having offices in 3 cities
* Our main goal was to understand how to lower the churn rate with the help of users segmentation


* We fixed columns names and cases
* We checked for full and implicit duplicates and didn't find any
* We tried to understand the issue of missing values for 35% of cases of `balance` but didn't find any strong dependencies and decided to leave them as is
* We converted categorical values into quant ones for corr matrix further on


* The overall churn rate is 20.37%
* The majority of our users below 40 years old have churn rate way lower the average
* However, 44-65 years old people leave the bank significantly more often
* As previously assumed, active users have significantly lower churn rate
* Rejecting the primary assumption, credit card posession does not bring churn rate way lower
* Women are more inclined to leave/change the bank
* In Rostov the churn rate is way above the average and peer cities
* For users who have 2 products, the churn rate is way lower than for those users who have just 1 product and for overall churn rate
* There is no strong connections among `churn` and `objects`, `score`, and `estimated_salary`


* We have formed 24 segments of users based on the age range, gender, city, and number of bank products
* When ordering the segments by weighted churn rate (as on the last chart), we came to conclusion that there are 3 priority stages to bring the overall churn rate lower:  
    1) Primary focus on the middle age group in all the cities of both genders with only 1 product  
    2) Target female users in Rostov in young and pensioneers age groups with both 1 and 2 products  
    3) Push the second product to users who have just 1 product in all other segments, as having 2 products brings the churn rate significantly lower
    

* We tested 2 hypothesis in both of which H0 can not be rejected:  
    1) We have no reason to believe that the average estimated salaries of users having 2 and 1 bank products are significantly different  
    2) We have no reason to believe that the churn rates of users having a credit card and not are significantly different
    
## Recommendations

As stated above, we see that the work on lowering the churn rate should be done in 3 stages.

Here are some ideas:
1. **Push the second product** to all the segments, especially in the middle age of 41-65 years old
2. As in some segments with even 2 products, churn rates for women in Rostov in the middle and pensioneers age groups are higher than on average, **get partnerships with local businesses** focused on travel and cultural events, home and gardering, and child and grandchild care **to provide more cashback and/or special discounts when bank products are used**
3. It might be that the bank is mostly done by and for youngsters, so some concepts can be not-easily understandable to people in middle and pensioneer age ranges, so it might be appropriate to **generate more stories in the bank app and/or write more articles in the bank blog and social media** explaining how banking products work and what benefits they bring
4. **Create new debit product for juniors (under 18 years old)** which can have significant effect on women having children, as junior card would be connected to the parent one and it would be harder to churn 
5. **Develop new joint family accounts** which can hook both genders to stay longer in the bank


## Scope of the project

**The goal**:
- To reduce churn rate with the help of user segmentation

**Input data**: 
- User data of a regional bank represented in 3 cities
- Remark: there is some data when client is both marked as active and churned; and there is both some balance and client churned. In such a case, it means that when client churned he was still active and/or had some balance different from 0 


**Analysis structure**:
* Data overview
    * Download data
    * General view (head, info, describe, corr)
* Data preparation
    * Fix columns' names and cases
    * Check for full duplicates
    * Try to workaround with missing values
    * Convert categorical values into quant ones
* EDA
    * Start with corr matrix to see the highest linear dependencies
    * Then dig deeper other aspects
* Users segmentation
    * By age group, gender, city, and number of products
* Hypothesis testing
    * Users estimated salary and number of bank products
    * Credit card posession and churn rate
* Results
* Recommendations
* Presentation
