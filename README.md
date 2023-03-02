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

* Total Number of Reviews
  * Amazon Vine: 107
  * Regular: 39,869

![Vine_Review_Count](https://user-images.githubusercontent.com/104707395/222545547-92ab7c8e-6a28-41c0-bbe4-009721cb130c.png)

![Non_Vine_Review_Count](https://user-images.githubusercontent.com/104707395/222545585-b3431cb7-b5dd-4f6c-88ac-c0176e87d87a.png)




* Number of 5-Star Reviews
  * Amazon Vine: 56
  * Regular: 21,005

* Percentage of 5-Star Reviews
  * Amazon Vine: 52.3%
  * Regular: 52.7%
