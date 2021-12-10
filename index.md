## What makes a quote in the newspaper viral ?


### Introduction
(BRIEF CATCHY DESCRIPTION OF THE PROJECT, TO DO (here just readme copy-paste))
In a world where the internet allows speaking to millions of people, we want to identify what factors can be linked to someone effectively reaching huge audiences. 
To measure how many people are reached by a quote we will use the number of repetition of said quote in newspapers. 
By analysing the characteristics of extremely viral quotes we want to try building guidelines to optimize the chance of a quote reaching a wider range of people. 
These guidelines would constitute very interesting tools for politicians and influencers as they would allow to better choose the topic and the speaker delivering a concept to increate the likelihood of being heavily quoted.

### Data

- where does it come from ? How is it useful to answer our question ? (Quotebank, Wikidata)
- what is in the raw data ? (show EDA of raw features)

### Feature Extraction

- How do we extract features that can be useful to answer our question, how do we enrich the raw data ? (output -> num_occurrences, speaker -> age, nationality,.../ quote text -> word count, topic, sentiment analysis,...) (we can show plots from EDA etc...)
- What features do we select for the resgression and how we encode it to train our models (one-hot encoding, keep only most frequent classes, discretization,...)

### Predict Virality
(SHORT INTRO)

#### Regress the occurrences of quotes

- Linear Regression using the features, feature selection, analysis of the coefficients

#### Classify the quotes

- First trial -> fail, why ?
- Other strategy, better ?

### Improvements

- How can we improve our models, better extract/select features ?

### Summary

- Key points
- What we can conclude from our analysis
