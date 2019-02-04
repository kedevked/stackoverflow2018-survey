# Stackoverflow 2018 analysis

This notebook contains an analysis for the data gathered during the 2018 stackoverflow survey. The dataset used can be found [here](https://insights.stackoverflow.com/survey).

## Motivation <a name="motivation">

The motivation of this notebook is to provide an insight to this question
**What is the top 3 languages ? **

To get the answer the analysis performed is as follows:

    - Plotting the kmeans elbow curbe to get the number of cluster of the dataset
    - Using kmeans to get a number of cluster
    - From each cluster, identify the top 3 languages.

Interestingly, some of the top 3 languages can be linked to some fields of programming. The notebook is discussed in this [blog article](https://medium.com/@edoh.dev/stackoverflow-survey-2018-top-3-languages-656f34d6704c)

## Repository description

This repo contains a notebook that goes through the steps described in [motivation](#motivation).

## Acknowledgements

All the credits of the survey goes to [stackoverflow](https://insights.stackoverflow.com/survey) with this rich dataset that allows to get some insights of what it is to be developper. Feel free to use the work here if you see fit.