---
title: "Data exploring & Manipulation Project"
date: 2018-10-31
tags: [Pandas , data science , simple project , beginner , DataFrame , seaborn , matplotlib , Data Manipulation]
excerpt: " Pandas , Data Manipulation , seaborn , matplotlib "
---

# Simple Data cleaning & Manipulation project

## Using a Dataset from Kaggle:
### League of Legends Ranked Matches
Data about 184070 League of Legends ranked solo games, spanning across several years and after cleaning 148638 games.

### Content:
* Matches.
* Player and team stats.

## Okay! let's go on a quick tour on what's the Notebook about:

### Introduction
* this project is about Data Cleaning & Manipulation using Pandas from python library and Data visualizations using seaborn and matplotlib libraries.
* a dataset from Kaggle was used, {League of Legends Ranked} Matches access it from [HERE](https://www.kaggle.com/paololol/league-of-legends-ranked-matches).
* Exploratory Data Analysis was implemented to find some correlations to gain more insight about some pick strategies.

### Doing some Exploratory Data Analysis(EDA):

<img src="{{ site.url }}{{ site.baseurl }}/images/art2/gameslessthan25mins.PNG" alt="">

#### previous heatmap included only first 25mins of the game and so correlations here are:
* kills & deaths affect strongly the winning process.
* also assits & turretkills affect the winning process.
* kills has strong relation with goldspent.
* more goldspent means more totdamagetochamp means more likely to earn kills.

__

<img src="{{ site.url }}{{ site.baseurl }}/images/art2/gamesmorethan40mins.PNG" alt="">

#### So in the late game as gamers call it OR after 40 mins of game time we find that:
* deaths & kills doesnt even matter alot and have very poor correlation with game winning.
* inhibkills & turretkills have about 25% chance of winning the game(still not big correlation).
* kills have high correlation with goldspent & totdmgtochamp.
* assists have 40% corr with wardsplaced ( as this is the support's job) also -43% with totminionkilled( supports don't farm alot) and -32% with kills.

__

<img src="{{ site.url }}{{ site.baseurl }}/images/art2/topwinratechamps.PNG" alt="">

#### Playing with pandas to get top & least win rate champions in each role and printing the results looks like this:

<img src="{{ site.url }}{{ site.baseurl }}/images/art2/champsresult.PNG" alt="">

__

## Time for some Counter picks advices!

After creating a Dataframe for each role(lane) picks, doing it in seaborn's barplot and it was huge as there was alot of binary picks.
So showing here some of the big differences in each role(lane) as following:

## for TOP lane:
<img src="{{ site.url }}{{ site.baseurl }}/images/art2/top.PNG" alt="">

__
## for JUNGLE lane:
<img src="{{ site.url }}{{ site.baseurl }}/images/art2/jungle.PNG" alt="">

__
## for MID lane:
<img src="{{ site.url }}{{ site.baseurl }}/images/art2/mid.PNG" alt="">

__
## for AD CARRY lane:
<img src="{{ site.url }}{{ site.baseurl }}/images/art2/adc.PNG" alt="">

__
## for SUPPORT lane:
<img src="{{ site.url }}{{ site.baseurl }}/images/art2/supp.PNG" alt="">

__

# That's all Thanks!

## The link to the Github repository [HERE](https://github.com/manaminer/League-of-Legends-analysis)

## The link to the Kaggle kernel [HERE](https://www.kaggle.com/manaminer/league-of-legends-visualizations-and-cleaning)
