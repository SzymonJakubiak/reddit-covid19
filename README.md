# Description

This project consists of exploratory data analysis of posts from subreddit r/wordnews. All posts' titles are processed for their emotions with help of DeepMoji pretrained model. Special emphasis was placed on analysis of COVID-19 related posts, including a comparison of number of posts vs total active cases. Subreddit dataset has been acquired through Pushshift API. COVID-19 statistics comes from [Open Word in Data](https://ourworldindata.org/coronavirus-source-data)

## How to follow the project

This is exploratory data analysis. Interesting visualisation and takeaways are all included in this readme. Additionally, the repository contains datasets and source code.<br/>
Processed datasets from intermidiate and final steps can be found in 'datasets.zip'.<br/>
The source code is shared in form of separated Jupyter Notebooks divided into 3 groups:
1. SCRAPING... - downloading posts data
2. PROCESSING... - processing data (language detection and emoji assignment)
3. VISUAL... - final visualisation and summaries

## Analysis

Posts dataset comes from subreddit 'wordnews'. It contains over 250 000 records dating from December 2019 to July 2020.

### Post's data structure

A sample of collected data can be seen below.<br/>
![source data](img/original_data.png)<br/>
From available fields 'Title', 'Publish Date' and 'Flair' are to be used for further analysis.
- Title - Set of words briefly describing a news
- Publish Date - Datetime based on UTC timezone
- Flair - Tag assigned by the original poster (optional)

### Language detection

Every post has been...

### Posts division

<!-- Conditions -->

### Emoji assignment & comparison


### COVID posts vs total cases

