# Amazon_Vine_Analysis
## Overview of the analysis of the Vine program
### What is Amazon Vine?

* Amazon Vine is an invitation-only program that selects influential reviewers to serve as "Vine Voices". 
* Vine Voices can request products to be shipped to their door free of charge so that they can review the products and give their "unbiased opions".

### The Analysis

* To see whether or not Vine Voice reviewers are truly unbiased, I selected a dataset of Outdoor equipment that contains reviews of products from both Vine Voices and regular reviewers.
* I hypothesize that people who get paid to leave reviews are more likely to leave 5 star reviews for products than regular reviewers are, which is biased. 
* To perform this analysis, I filtered the dataset to create two new data frames, one of regular customer reviews, and one of Vine Voice reviews. I then calculated the percentage of reviews that were 5 stars for each dataframe.

## Results

### Number of Reviews

* Total Number of Reviews
  * Amazon Vine: 107
  * Regular: 39,869

![Vine_Review_Count](https://user-images.githubusercontent.com/104707395/222545547-92ab7c8e-6a28-41c0-bbe4-009721cb130c.png)

![Non_Vine_Review_Count](https://user-images.githubusercontent.com/104707395/222545585-b3431cb7-b5dd-4f6c-88ac-c0176e87d87a.png)

### Number of 5-Star Reviews

* Number of 5-Star Reviews
  * Amazon Vine: 56
  * Regular: 21,005

![Vine_5_Star_Count](https://user-images.githubusercontent.com/104707395/222545740-40c41224-8c1d-4d77-b3d4-449c7430781b.png)

![Non_Vine_5_Star_Count](https://user-images.githubusercontent.com/104707395/222545773-6fd1d570-f662-4f3f-9908-26db7479f22e.png)

### Percentage of 5-Star Reviews

* Percentage of 5-Star Reviews
  * Amazon Vine: 52.3%
  * Regular: 52.7%

![Vine_5_Star_Percent](https://user-images.githubusercontent.com/104707395/222545824-d4283589-c3d0-477e-a3bb-b2f09fb60332.png)

![Non_Vine_5_Star_Percent](https://user-images.githubusercontent.com/104707395/222545852-b312ee7b-b259-4c51-8a65-0063edeeaebd.png)

## Summary

* The results of the analysis of this dataset shows that the probability of a reviewer leaving a 5-Star review is not influenced by whether or not they are a member of Amazon Vine. There is less than a percent difference between the percentage of 5-Star reviews left by both reviewer category. 

* Further analysis to ensure that our conclusion is correct can be performed via statistical testing using a T-Test.
