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

The goal of this project is to predict which factor that caractherize a quote contributes for make it viral. For this purpose we use the Quotebank dataset complemented with the informations collected from Wikidata. Quotebank consist of a dataset of 178 million unique quotations, extracted from 196 million Engish news papers pubished between Agoust 2008 and April 2020. Wikidata is a databese containing information about a subjects being in Wikimedia. Therefore we will use it to gather the charactheristics about the speaker of each of the quotes.
 
Before diving into the question we will start by exploring the data extracted from both dataset. The first t 
hat we will do is to define what is a virae quote. For doing so we have analyzed the number of occurences of all the quotes present in Quotebank.(picture quotes distribution)
We see that the majority of the quotes occurs one time and that the 99% of them occures less than 100 times. For this reason we decided to set the threshold for defining a vira quote at 100 occurences. Therefore we obtained that in our dataset only the 0.5% of quotes are viral.

After difining the notion of virality, we are interested into finding the relevant features that may have an impact on the virality of the quote. Initially. we explored the raw distribution of the speaker's features as well as the distributions obtained when weighting by the number of different quotes of the speaker and by the total number of occurrences of all his quotes. (picture age distribtion) By observing the age distributions we can see that more than half of the speakre in our dataset have an age that ranges between 19 and 66. This is expected since the speakers benefitting from media coverage are mainly young adults and middle-aged men.

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
