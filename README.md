# Amazon_Vine_Analysis

## Overview
   - For this week we are charged with the responsibility to analyze a large data set from Amazon's Vine program.  My analyisis covered reviews from the video game category of Amazon.  Using big data tools such as PySpark, AWS RDS, and Postgres to query the data.  After our tools have been set up we then peform analysis to determine the level of bias between paid reviews and non-paid reviews for 5-star reviews.


## Results:

   - There were a total of 94 vine reviews; and 40,471 non-vine reviews (see image).

![This is an image](https://github.com/BMoreland20/Amazon_Vine_Analysis/blob/main/Resources/total_reviews.png)


   - There were a total of 48 five start vine reviews; and a total of 15,663 five star non-Vine reviews (see image).

![This is an image](https://github.com/BMoreland20/Amazon_Vine_Analysis/blob/main/Resources/total_5_star_reviews.png)


   - Of the five star reviews 0.3% of the reviews were Vine reviews, with the overwellming amount of reviews being the non-Vine reviews at 99.7% (see image).

![This is an image](https://github.com/BMoreland20/Amazon_Vine_Analysis/blob/main/Resources/5_star_percentage.png)



## Summary:
   - When looking at the results of the overall percentage of five-star reviews we do not see a disproportionate amount of the five-star reviews being paid.  In fact, we see that the majority are non-paid reviews, showing that the bias is on the side on non-paid reviews.  Which when looking at purchasing items from Amazon would be the kind of bias you would prefer to see rather than seeing too many paid reviews; as these may not be as truthful as those that are non-paid.
   - To statistically confirm that there wasn't bias towards the Vine reviews, we could perform a two sample T-test to compare the means and determine if there is any significant difference in the means or if it is all up to chance.  Here our Null hypothesis would be that there is no difference in the means and our alternate hypothesis would be that Vine reviews have a higher mean than non-vine reviews.