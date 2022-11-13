# Banking project
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
