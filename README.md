## Prediction of movie popularity 
Read my publication about movie popularity project on Medium:  
[Movie Popularity]()

## Introduction
Movie popularity can help people to decide which movie to watch, or whether they want to go the cinema to watch it or wait till the DVD is release and watch it at home. Consequently, it could also help theater owner to choose which movies to show or how many times to show it or for how long.

## Purpose
The purpose of this project is to analysis a dataset containing information about movies and create a linear model to 
predict movie popularity. 

This repository includes the following main files:

* a dataset `movies.RData` used to perform the analysis.
* a code book that describes the variables and the data called `CodeBook.md`. 
* a `README.md` that explains how all of the scripts work and how they are connected.
* a htlm file that shows the analysis that was performed called . 

## Data Set Information

In the movies dataset, there is randomly sampled movies which were released in United States movie theater in the period of 1970-2014. The data was obtained from Rotten Tomatoes and IMDB. The dataset contains features of each movie, including genre, MPAA rating, production studio, and whether they recieved Oscar nominations.

Even though there is no detailed information about the exact sampling methods used, the movies included in this dataset were randomly sampled from the above two mentioned sources and no bias were created by the sampling method so we can assume that the results obtained can be generalized to all U.S movies released between 1970 and 2014. On the other hand, because this is an observational study, the relationships that could be find from this data indicate association, but not causation

## Analysis

perform the following tasks:

* Reads the `movies.Rdata`
* *Exploratory Data Analysis*:
    - Obtains descriptive statistics summarizing central tendency, dispersion and shape of the dataset’s distribution
    - Creates visuals in order to explore the relationships existent in the dataset
