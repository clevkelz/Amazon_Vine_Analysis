# Amazon Vine Analysis

## Overview of the Analysis


The purpose of this analysis was to determine whether reviews written by members of the paid Amazon Vine program (https://www.amazon.com/vine/about) contain favorable bias compared to reviews from other individuals.  To test this, a dataset was selected from a list housing information on reviews from 50 product types sold on Amazon (https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).  These datasets contain the following information:
* Reviewer Country
* Identifier Information
  * Customer
  * Review
  * Product
* Product Title
* Product Category
* Star Rating (based on a 1-5 scale)
* Number of Helpful Votes (Amazon users can identify which reviews are the most helpful when making a decision whether to purchase an item)
* Number of Total Votes
* Indicator if the Review was Written as Part of the Vine Program (Y/N indicator)
* Indicator if the Purchase was Verified (Y/N indicator, this shows that Amazon verified the individual writing the review actually purchased the item being reviewed)
* Title of the Review
* Text of the Review
* Date of Review

