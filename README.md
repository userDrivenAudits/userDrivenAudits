### Hi there 👋

This page lists software, data (forthcoming), and instructions (forthcoming) for replicating a research study that examined the level of participantion in four user-driven auditing cases, including in 5 common roles users played in these audits.

### Python Scripts and notebooks for retrieving data from Twitter

snsscrape script: snscrape twitter-search "HASHTAGE since:2022-10-01 until:2022-11-20" > FILE_NAME.txt

Python notebook for retrieving data from Twitter API:
<a href=https://github.com/userDrivenAudits/userDrivenAudits.github.io/blob/e41980dbca13ff87c5f626cdbf466f2883a62976/twitter_data_rate.ipynb </a>


### Software for building and testing the Relevance and Division of Labor Classifiers
We used the open-source software LightSide to train and test 2 classifiers: (1) Relevance classifier and (2) Division of Labor Classifier. The software can be downloaded at this page: http://ankara.lti.cs.cmu.edu/side/ 

### Relevance Classifier -- Model Selection and Features

Model: Naive Bayes
Settings Selected: 10-fold cross-validation
Features: unigrams, bigrams, trigrams, no punctuation

Model: Support Vector Machines
Settings Selected: Normalize, LibLinear, 10-fold cross-validation
Features: unigrams, bigrams, trigrams, no punctuation

### Division of Labor Classifier -- Model Selection and Features

Models: 
Settings:



### Training, Test and Data-sets
(These will be posted at publication pending review)
