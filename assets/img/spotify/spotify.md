---
layout: page
title: Recommending Songs on Spotify through Python
description: >
  This project used a logistic regression model to create a recommendation model for songs using SciKit-Learn, Pandas and SciPy through Python.
hide_description: true
sitemap: false
---

* This unordered list will be replaced by the table of contents
{:toc}

![Spotify Cover](/assets/img/spotify/spotify_cover.jpg){:.center}

### Overview

In this project, I used a logistic regression model to create a recommendation model for songs using SciKit-Learn, Pandas and SciPy through Python. I have always had a great interest in music and have used Spotify for years, but always wondered how their algorithms for recommendations were always superior to their competition. With this idea in mind, I set out to investigate how they suggested music to users to gain a better understanding of their process.

### Data

Thankfully, Spotify is extremely transparent with their song data and grants access to developers for parts of it. After searching Kaggle, I found a relevant dataset that another user had scraped and parsed to begin my analysis. The data set consisted of just over 2,000 instances and consisted of 17 variables with 14 being relevant.

As the information was compiled directly from Spotify, it was already clean, so little preprocessing was needed. Instead, I focused on exploring the data, noticing irregularities in variables and the general shape of it to determine my best approach. While some of the variables, such as danceability, seemed subjective and required greater explanation, others were less complicated, such as time signature. Most of the variables were float data ranging from 0 to 1, with a few integers, such as duration in milliseconds. These facts made the summary statistics relatively straightforward and only a few outliers appeared.

### Analysis

Although the data was straightforward, evaluating it was more complicated. Beginning with a correlation matrix, I observed the variables to get an estimate on which ones should be focused on, but few were strongly correlated. However, I was able to determine a few to work with and looked at their distributions. Some were extremely straightforward, such as valence, but others, like instrumentalness, were not Gaussian and required normalization.

Next, I used dbscan from sklearn to perform outlier detection, but most values fit inside the normal distribution. Speechiness, or how much speech without music, had the most outliers, but was extremely low with only 46 out of 2,017 values or 2.28%. I hypothesized that these values could come from podcasts and removed them as they affected the distribution and trend lines without providing a significant impact on the data.

To perform the analysis, I used RFE, or recursive feature elimination, from sklearn to automatically tune the model, finding the best result based on cross validation. Once optimized, the logistic regression model reached 67.6% accuracy on the train data and 63% on the test data. While the results were not exceedingly excellent, the model did outperform the naïve approach making it a success, especially considering how complex musical tastes are.

### Outcome

Overall, completing the project gave me a greater respect for recommendation algorithms. Although we use them daily, it is often with little thought into how they affect our lives for the better, whether it is with recommendations for movies on Netflix or shopping on Amazon. I also gained a respect into how difficult it is to classify nebulous and hard to define values into actionable data, such as song characteristics, and showcased Spotify’s expertise on the subject.

If I were to do this project again, I would make two major changes. First, I would have liked to use my own Spotify data instead of pre-existing data from other users. Although I created a developer account and pulled information from their API, I did not have the skills with Node.js for preexisting solutions and was not familiar enough with dictionaries to scrape it with Python at the time. Second, as this was a project for my Master degree, I was required to use a multi-linear or logistic regression model which was not the ideal method. If I were to use a KNN or gradient boosted random forest approach with machine learning, I predict that the accuracy would greatly rise due to how relations to variables are formed. From making these two changes, I would have a more individualistic project that I could personally compare results to and their accuracy could improve when using the more complex models.
<br><br>

____

### Supporting Figures
