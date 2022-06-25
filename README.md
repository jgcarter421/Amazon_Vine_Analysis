# Amazon Vine Analysis

## Overview
The purpose of this project was to analyze Amazon Vine program for potential bias in Amazon reviews from the Vine Reviewers. 

Per Amazon's website, "Amazon Vine invites the most trusted reviewers on Amazon to post opinions about products to help their fellow customers make informed purchase decisions. Amazon invites customers to become Vine Voices based on the insightful reviews they published on their past purchases and helpfulness of their reviews. Amazon offers Vine members free products that have been submitted to the program by participating selling partners. Vine reviews are the independent opinions of the Vine Voices and the selling partners cannot influence, modify or edit the reviews. Amazon does not modify or edit Vine reviews, as long as they comply with our posting guidelines."

This analysis looks into whether the Vine members have a bias towards 5-Star ratings in their reviews.

This analysis ustilized ETL (Extract, Transform, Load) to import the data from Amazon servers, transform the data, and load the data into DataFrames.  The analysis analyzes the Amazon "Outdoors" Reviews dataset.

## Results

### Paid Reviews

* There were **107** paid Amazon Vine reviews
* There were **56** paid 5-Star reviews
* The percentage of paidn5-Star reviews was approximately **52%**

### Unpaid Reviews
* There were **39869** unpaid Amazon Vine reviews
* There were **21005** unpaid 5-Star reviews
* The percentage of unpaid 5-Star reviews was approximately **53%**

## Summary
