# ps239t-final-project

## Short Description

Racist ‘blacklivesmatter’?
: A text analysis on tweets about blacklivesmatter and alllivesmatter 

There arise many counter-statements such as white lives matter against black lives matter and male lives matter against female lives matter. This reddit page called the red pill is the exemplary of male lives matter group. They argue that they live in a culture increasingly lacking a positive identity for men in a very anti-feminist way. These statements caught me because they argue “universal” formulation against those emphasize the traditionally underprivileged groups.

## Dependencies

List what software your code depends on, as well as version numbers, like so:.

R, version 3.1
Python, version 2.7, Anaconda distribution.
(In your scripts, includes commands that install required packages.)

## Files


### Data

polity.csv: The PolityVI dataset, available here: http://www.systemicpeace.org/inscrdata.html

nyt.csv: Contains data from the New York Times API collected via collect-nyt.ipynb . Includes information on all articles containing the term "Programmer Cat", 1980-2010.

analysis-dataset.csv: The final Analysis Dataset derived from the raw data above. It includes country-year values for all UN countries 1980-2010, with observations for the following variables:

ccode: Correlates of War numeric code for country observation
year: Year of observation
polity: PolityVI score
nyt: Number of New York Times articles about "Programmer Cat"

### Code

01_collect-nyt.py: Collects data from New York Times API and exports data to the file nyt.csv
02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

### Results

coverage-over-time.jpeg: Graphs the number of articles about each region over time.
regression-table.txt: Summarizes the results of OLS regression, modelling nyt on a number of covariates.

## More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
