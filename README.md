# Amazon_Vine_Analysis

### Overview of the analysis: Explain the purpose of this analysis.

The reason for this analysis was to use PySpark in order to perform the ETL proess using big data with AWS. The ETL process entails:
    - extracting the dataset
    - transforming the data
    - connecting the data to AWS RDS
    - loading he data that was transformed
    - run calcualtions
For this specific analysis, we focsed on video games

### Results:

## Reviews
- Vine reviews
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/paid%20total%20number%20of%20reviews.png)

- Non-Vine reviews
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/unpaid%20total%20number%20of%20reviews.png)

## 5 Star
- 5 stars Vine reviews
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/paid%205-star%20reviews.png)

- 5 stars non-Vine reviews
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/unpaid%205-star%20reviews.png)

## Percentage
- Percentage of Vine reviews
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/paid%205-star%20reviews%20percentage.png)

- Percentage of non-Vine 
![](https://github.com/mquimi/Amazon_Vine_Analysis/blob/main/images/unpaid%205-star%20reviews%20percentage.png)


### Summary: 
 A positive bias that we can review for the Vine program is that 51% of the reviews were 5 Star versus the 39% reviews of non-vine 5 Star.

 In order to find out more information, we could run a statistical analysis for both non-vine and vine reviews. With this information, we would be able to make hypothesis based on the reviews.