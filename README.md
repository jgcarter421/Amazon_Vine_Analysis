# Amazon Vine Analysis

## Overview
The purpose of this project was to analyze Amazon Vine program for potential bias in Amazon reviews from the Vine Reviewers. 

Per Amazon's website, "Amazon Vine invites the most trusted reviewers on Amazon to post opinions about products to help their fellow customers make informed purchase decisions. Amazon invites customers to become Vine Voices based on the insightful reviews they published on their past purchases and helpfulness of their reviews. Amazon offers Vine members free products that have been submitted to the program by participating selling partners. Vine reviews are the independent opinions of the Vine Voices and the selling partners cannot influence, modify or edit the reviews. Amazon does not modify or edit Vine reviews, as long as they comply with our posting guidelines."

This analysis looks into whether the Vine members have a bias towards 5-Star ratings in their reviews.

This analysis ustilized ETL (Extract, Transform, Load) to import the data from Amazon servers, transform the data, and load the data into DataFrames.  The analysis analyzes the Amazon "Outdoors" Reviews dataset.

## Results

### Image
<img width="617" alt="Screen Shot 2022-06-25 at 3 14 06 PM" src="https://user-images.githubusercontent.com/99417460/175789254-24dce019-da1a-4cc1-9ad3-33946e2e3d69.png">

### Paid Reviews
* There were **107** paid Amazon Vine reviews
* There were **56** paid 5-Star reviews
* The percentage of paid 5-Star reviews was approximately **52%**
### Unpaid Reviews
* There were **39869** unpaid Amazon Vine reviews
* There were **21005** unpaid 5-Star reviews
* The percentage of unpaid 5-Star reviews was approximately **53%**

## Summary
Out of the nearly 40,000 reviews in the Amazon "Outdoors" dataset, there were only 107 **paid** reviews.  Of those 107, there were **56** five star reviews.  This gives a percentage of 52% of paid 5-Star Reviews.  Due to 52 % of the reviews being 5-Star, one would conclude that there is a bias towards 5-Star reviews from paid Amazon Vine reviewers.  

However, when we look at the Unpaid (Non-Vine) reviews, there were 39869 **unpaid** reviews.  Of those, there were **21005** unpaid 5-Star reviews.  This actually gives us percentage of 53 % of unpaid 5-Star Reviews.  Based on these percentages, the 5-Star reviews from Vine reviewers is relatively the same percentage of 5-Star reviews from Non-Vine reviewers.

In conclusion, the data shows that there is not an implicit bias towards 5-Star reviews from Vine reviewers in the Amazon "Outdoors" dataset.  One could conclude that there is a tendency for all reviewers to give a 5-Star towards their reviews.  

An additional analysis to support this conclusion would be to analyze the statistical distribution of star ratings for Vine members versus non-Vine members.
