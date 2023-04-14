# A/B testing

## Results

1. Looking at cumulative data for two groups, we spotted some **large outliers in data points**
2. Thus, later on, **we filtered the data by number of orders per user (not more than 1) and by order amount (not more than 26,8k)**
3. **Closer to the end of the test, cumulative conversions got some stability**, although not with straight lines
4. Having done the statistical tests (Mann Whitney U-test) we found out that: 
    * There is a **statistically significant difference in the conversions in two groups both on the raw and filtered data**
    * However, on the other hand, there is **no statistically significant difference in the orders' amounts both on the raw and filtered data**
    * Actually, after the filtration, the **lift in the average orders' amounts (group B to group A) became even negative (of 5,9%)**
5. As a result, we **stop the test and mark it as a negative one** due to the fact that we believe the revenue is more important than just the conversions
6. The **version B should not go into production**

## Scope of the project

**The goal**:
- Analyse the results of A/B tests

**Input data**: 
- We are analysts in the large e-commerce company
- We have data for visitors and orders from A/B tests

**Analysis structure**:
* Data overview
* Data preparation
* A/B tests interpretation
