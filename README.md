# ps239t-final-project

## Short Description

There arise many counter-statements such as white lives matter against black lives matter. These statements caught me because they argue “universal” formulations against the arguments for the underprivileged groups. Text analysis of word frequency, discriminating word, sentiment, and the location information of two statements will reveal us how different/similar their word usages are. I am conducting a text analysis on tweets about blacklivesmatter and whitelivesmatter.  


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

1-Tweet to csv.ipynb: Collects data about 'blacklivesmatter'/'whitelivesmatter' from Twitter API and exports data to the csv files.

2-Pre-processing.Rmd: Loads and cleans the raw Twitter datasets into the Analysis Dataset.

3-Wordclouds.Rmd: Produces wordclouds of data 

4-Discriminating.Rmd: Conducts analysis of the discriminating words between 'blacklivesmatter' and 'whitelivesmatter' data

5-Sentiment.Rmd: Conducts sentiment analysis of the data

6.1-Vacation_location to csv.ipynb: Collects location data about 'vacation' from Twitter API and exports data to the csv files.

6.2-Vacation_location_Rplot.Rmd: Produces visualization of location data about 'vacation' from Twitter API on the world map. 


### Results

blm_wordcloud.jpeg: Plots the most frequent words in the Tweets of 'blacklivesmatter'

wlm_wordcloud.jpeg: Plots the most frequent words in the Tweets of 'whitelivesmatter'

discriminating1.jpeg: Shows the words with highest difference in average rates per documents

discriminating2.jpeg: Shows the words with highest difference in average rates per documents by the average rate across all documents

blm_sentiment.jpeg: Plots the polarizing sentiments used in the Tweets of 'blacklivesmatter'

wlm_sentiment.jpeg: Plots the polarizing sentiments used in the Tweets of 'whitelivesmatter'

vacation_location.jpeg: Plots the Twitterers who used the word of 'vacation' over the countries. 


## More Information

contact info: Joohyun Park, jp53@berkeley.edu
