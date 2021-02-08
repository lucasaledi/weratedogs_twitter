# WeRateDogs Twitter archive exploration
## by Lucas Aledi

# Dataset Overview
This is the fifth project of the Data Analyst Nanodegree on Udacity. This time, we have been asked to wrangle and investigate WeRateDogs' Twitter data as it contains basic tweet data for all 5000+ of their tweets as they stood on August 1, 2017, including [this memorable exchange](https://knowyourmeme.com/memes/theyre-good-dogs-brent). After all the wrangling, the *master_df* contains information on +2300 tweets, ranging from the id of a particular tweet, its date of creation, text and length, as well as the number of times it has been liked or retweeted.


# Summary of findings
So, we could summarise our findings as follows:
   * 1\. It could be interesting to reviw the neural network used to identify the dogs on all tweets. It seems that it could be improved, given that many images with p1_dog value set as "False" actually depicted a dog;
   * 2\. The engagement distribution is heavily skewed to the right following a log-normal distribution. The bulk of the distribution is within the 3k-10k range;
   * 3\. Tweets which depict a dog perform better in terms of engagement and, yes, different dog breeds perform differently, with *golden retrievers* being the most engaging dogs;
   * 4\. Finally, rates have a surprisingly moderate correlation with engagement. This could be indicative of the fact that there are some hidden variables out there influencing the level of engagement (e.g., dog breed, text sentiment, etc). As curiosity is a inherently human characteristic, we are very likely to dive into those hypothesis soon.

# Key Insights for Presentation
A presentation for this project has not yet been made. We'll look into it after further investigating the database for some ML models.


# Credits
[Linkedin - Lucas Aledi](https://www.linkedin.com/in/lucasaledi/)

[GitHub - lucasaledi](https://github.com/lucasaledi)

udacity.com
