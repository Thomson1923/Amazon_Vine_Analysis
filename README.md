# Amazon_Vine_Analysis
#
# MEMORANDUM

# To: Marketing Department – Healthcare Products
# From: Bob
# Re: Impact of Payments on Reviews

#Overview of Project
##Based on the analysis of Vine and non-Vine reviews on Amazon, we found that payments to product reviewers actually decreased the likelihood of receiving five-star reviews. Our findings suggest that results from the Vine program may serve as a worst-case scenario during market research.
#
#Results
##Methodology – We used an attenuated data set to assess the influence of payments on reviews. From all available data, we limited this analysis to products having at least 20 total votes, thereby eliminating the potential for low-interest products skewing the results. Among this subset, we retained only those products having at 50% helpful votes among the total votes to concentrate our focus on meaningful responses. The work presented in this report focuses on five-star ratings since our greatest concern is for reviewers giving highest ratings based on payment. All data analysis was performed using PySpark ().
##
##Sample Set – Even with the total vote and helpful vote filters described above, we had 497 Vine reviews and 120,863 non-Vine reviews as the basis for our analysis. We feel that these values represent a statistically significant sample set.
##
##Number of Five-Star Ratings – Within the sample set, Vine reviewers gave 220 five-star reviews and non-Vine reviewers gave 74,470 five-star ratings.
##
##Comparative Percentages – Vine reviewers submitted five-star ratings at the rate of 44% while non-Vine reviewers submitted five-star responses 62% of the time.
#
#Summary
##The lower incidence of five-star ratings from the Vine reviewers suggest that this group may have more demanding criteria for the highest rating than the public at large. We recommend a follow-up study examining Vine and non-Vine reviews at the lower end of the rating scale (zero-stars or one-star) to see if our conjecture about the more demanding Vine reviewers is correct.  

