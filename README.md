# ps239t-final-project

## Short Description

A text analysis on tweets about blacklivesmatter and whitelivesmatter 

There arise many counter-statements such as white lives matter against black lives matter and male lives matter against female lives matter. (cf. The reddit page called the red pill is the exemplary of male lives matter group. They argue that they live in a culture increasingly lacking a positive identity for men in a very anti-feminist way.) These statements caught me because they argue “universal” formulations against the argument for the underprivileged groups. 


## Dependencies

R, version 3.3.1

Python, version 3, Anaconda distribution.


## Files

### Data

Two csv files converted from Twitter using TwitterSearch library
November 20th 2016 - November 26th 2016

blacklivesmatter.csv: 8100 user IDs(user) and tweets(text)
whitelivesmatter.csv: 2846 user IDs(user) and tweets(text)

cf. vacationlocation.csv: I tried to get location infos of blacklivesmatter and whitelivesmatter, but got no infos back with these keywords. The keyword 'vacaton' gave me 18 locations out of 2000 tweets. (I guess people do not share their location infos, which is optional in Twitter, as much as they do in other SNS platforms. But it might be helpful for those who want to analyze the (Twitter) location infos available.)

### Code

(In your scripts, includes commands that install required packages.)
01_collect-nyt.py: Collects data from New York Times API and exports data to the file nyt.csv
02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

coverage-over-time.jpeg: Graphs the number of articles about each region over time.
regression-table.txt: Summarizes the results of OLS regression, modelling nyt on a number of covariates.

## More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
