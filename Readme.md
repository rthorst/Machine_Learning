# Machine Learning Projects

This repository - currently being populated - houses some of my machine learning projects. I also use machine learning in many of my publications such as https://link.springer.com/article/10.3758/s13428-019-01235-z (un-paywalled link: https://psyarxiv.com/arf4t)

## Kinds of Mobile Strategy Games

![alt_text](https://raw.githubusercontent.com/rthorst/Machine_Learning/master/mobile_games/clusters.png)

There are more than a hundred thousand strategy games on the app store, more than any human can understand and summarize. A game developer may want to know about the kinds of games available to inform game design, marketing, and pricing. I find that there are 8 main kinds of strategy games on the app store. I find this by performing natural language processing analyses on the text descriptions of these games, specifically using: 

* Word embeddings (spacy)
* Dimensionality reduction (using a new neural network-based technique: Ivis, Szubert et al 2019, Nature Human Behav., https://www.nature.com/articles/s41598-019-45301-0) 
* Clustering (kmeans++)

