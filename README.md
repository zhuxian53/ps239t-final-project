# ps239t-final-project

## Short Description

A text analysis on tweets about blacklivesmatter and whitelivesmatter 

There arise many counter-statements such as white lives matter against black lives matter and male lives matter against female lives matter. (cf. The reddit page called the red pill is the exemplary of male lives matter group. They argue that they live in a culture increasingly lacking a positive identity for men in a very anti-feminist way.) These statements caught me because they argue “universal” formulations against the argument for the underprivileged groups. 


## Dependencies

R, version 3.3.1

Python, version 3, Anaconda distribution.


## Files

### Data

Two csv files exported from Twitter with TwitterSearch library

November 20th 2016 - November 26th 2016

blacklivesmatter.csv: 8100 user IDs(user) and tweets(text)

whitelivesmatter.csv: 2846 user IDs(user) and tweets(text)

cf. vacationlocation.csv: I tried to get location infos of blacklivesmatter and whitelivesmatter, but got no infos back with these keywords. The keyword 'vacaton' gave me 18 locations out of 2000 tweets. (I guess people do not share their location infos, which is optional in Twitter, as much as they do in other SNS platforms. But it might be helpful for those who want to analyze the (Twitter) location infos available.)

### Code

1-Tweet to csv.ipynb

2-Pre-processing.Rmd

3-Wordclouds.Rmd

4-Discriminating.Rmd

5-Sentiment.Rmd

6.1-Vacation_location to csv.ipynb

6.2-Vacation_location_Rlot.Rmd

(In your scripts, includes commands that install required packages.)
01_collect-nyt.py: Collects data from New York Times API and exports data to the file nyt.csv
02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

blm_wordcloud.jpeg: Plots the most frequent words in the Tweets of 'blacklivesmatter'

wlm_wordcloud.jpeg: Plots the most frequent words in the Tweets of 'whitelivesmatter'

discriminating1.jpeg: Shows the words with highest difference in average rates per documents

discriminating2.jpeg: Shows the words with highest difference in average rates per documents by the average rate across all documents

blm_sentiment.jpeg: Plots the polarizing sentiments used in the Tweets of 'blacklivesmatter'

wlm_sentiment.jpeg: Plots the polarizing sentiments used in the Tweets of 'whitelivesmatter'

vacation_location.jpeg: Plots the Twitterers who used the word of 'vacation' over the countries. 


## More Information

contact info: jp53@berkeley.edu
