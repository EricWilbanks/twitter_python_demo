# Twitter Basics for Linguists

## Introduction

This workshop is a brief introduction to working with Twitter data using the `tweepy` python library. The example code and instructions were put together by Eric Wilbanks (EricWilbanks.github.io) for the Sociolinguistics Lab at Berkeley (http://linguistics.berkeley.edu/slab/) on October 28, 2020. If you have any questions about the code or troubleshooting issues, please contact me by email at *wilbanks.ericw at gmail.com*.


## Outline

This workshop will cover the basics for people interested in interacting with Twitter data via their API and Python. We'll work through some introductory examples on:

- Creating a Developer Account
- Making API requests and exporting data
- Visualizing basic information about tweets
- Basic Sentiment Analysis
- Analyzing geotagged tweets

## Requirements

This workshop was initially developed in `Python 3.8.6` and the `Twitter Api v1.1`. Additionally, it requires the following Python libraries:

1. os
1. csv
1. tweepy
1. pandas
1. matplotlib
1. nltk
1. geopandas
1. descartes

Most of the modules are distributed as Jupyter iPython notebooks (.ipynb). You can find more information about installing and using Jupyter notebooks at (https://jupyter.org/).

Because of Twitter Terms of Service, we won't be distributing the twitter corpora mentioned in the . Please find instructions for collecting comparable corpora in `01_querying_twitter.ipynb`.

## Other Resources

I'm by no means an expert in this area, so let me point you towards resources for more in-depth explanations!



1. Afham (2019). Twitter Sentiment Analysis using NLTK, Python. (https://towardsdatascience.com/twitter-sentiment-analysis-classification-using-nltk-python-fa912578614c).
1. D'Arcy and Young (2012). Ethics and social media: Implications for sociolinguistics in the networked public. *Journal of Sociolinguistics*, 16.4, p. 532-546.
1. Huang, Guo, Kasakoff, and Grieve (2016). Understanding U.S. regional linguistic variation with Twitter data analysis. *Computers, Environment and Urban Systems*, 59, p. 244-255. (https://doi.org/10.1016/j.compenvurbsys.2015.12.003).
1. Jurafsky and Martin (2009). Speech and Language Processing. 2nd Edition.
	- 3rd Edition draft chapters available online (https://web.stanford.edu/~jurafsky/slp3/).
1. Munir (2019) Basic Sentiment Analysis using NLTK. (https://towardsdatascience.com/basic-binary-sentiment-analysis-using-nltk-c94ba17ae386).
1. Tenkanen and Heikinheimo (2019). Automating GIS processes. (https://automating-gis-processes.github.io/site/).
1. Wood (2020). Online learning resources: Python GeoPandas. (https://sites.northwestern.edu/researchcomputing/2020/04/23/online-learning-resources-python-geopandas/).

The Shapefiles for the US State Boundaries are from: https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html

The AFINN-111 valency ratings are from: Lars Kai Hansen, Adam Arvidsson, Finn Årup Nielsen, Elanor Colleoni, Michael Etter, "Good Friends, Bad News - Affect and Virality in Twitter", The 2011 International Workshop on Social Computing, Network, and Services (SocialComNet 2011).