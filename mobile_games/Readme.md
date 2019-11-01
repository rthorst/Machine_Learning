# There are 8 Main Types of Strategy Games on the Apple Store

The best way to view this analysis is in a Jupyter notebook in this repository: https://github.com/rthorst/Machine_Learning/blob/master/mobile_games/Clustering_Mobile_Strategy_Games.ipynb

## I Find That

I find that there are 8 main types of strategy games on the App Store! 

![alt_text](https://github.com/rthorst/Machine_Learning/blob/master/mobile_games/clusters.png)

* **Classic Strategy Games** (Sudoku, Chess, Tic-Tac-Toe) - Dark Blue
* **Combat Games** (Merc Wars, Jet Battle Combat, Vicious Tanks) - Light Blue
* **Lifestyle Games** (Pocket Clothier, Crazy BBQ, Ada's Fitness Center) - Purple
* **Mind Games** (Master-mind, Guess Who, Number Enigma) - Dark Pink
* **Tower Defense Games** (Bloons TD 4, Tiny Defense, Zombie Tower Shooting Defense) - Salmon
* **Puzzle Games** (2048 Jewels, Soda Pop Match 3, Shape Slide) - Dark Orange
* **Arcade-Strategy Games** (Crazy Pizzeria Kitchen Chef, Bouncy Fat Hungry Panda Jump) - Light Orange
* **Idle/Tycoon Games** (Idle 3Q, Transit King Tycoon) - Yellow

## Problem

There are hundreds of thousands of mobile games - more than any human can understand and summarize. When developing a game, it would be useful to know about the **types of games that already exist** to inform decisions about game design, marketing, and pricing.

## Approach

I **build a model** to learn the types of games that already exist. I do this by **analyzing > 17,000 games** on the Apple Store.

## Techniques

I use **several machine learning techniques** including:

* **Word embeddings** (to represent text in terms of its high-level semantics)
* **Dimensionality reduction** (using a new **neural-network based techinque: Ivis** https://www.nature.com/articles/s41598-019-45301-0)
* **Clustering** (kmeans++)
