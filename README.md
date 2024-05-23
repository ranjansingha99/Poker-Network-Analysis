# Social Network Analysis of Online Poker Games

This repository contains the code and documentation for the course project of ELL-880 Social Network Analysis, where we conducted a network analysis of online played poker games and predicted the likelihood of winning for any two random players matched against each other.

## Overview

In this project, we analyzed the network of online poker games, focusing on understanding the patterns of player interactions and their impact on game outcomes. Using social network analysis techniques, we aimed to uncover key players, influential communities, and predictors of winning in player matchups.

## Data

The dataset used in this project consists of records of online poker games, including information about player ID, games played, outcomes, and interactions.

## Analysis

### 1. Network Construction
We constructed a network representation of the online poker games, where players are nodes and interactions (e.g., playing together in a game) are edges. This network provides insights into the structure of player connections and the formation of communities.

### 2. Centrality Analysis
We computed centrality measures such as degree centrality, betweenness centrality, and eigenvector centrality to identify influential players in the network. These measures help in understanding the importance of players in shaping game outcomes.

### 3. Community Detection
We applied community detection algorithms to partition the network into cohesive groups of players. Understanding these communities can provide insights into player behaviors, strategies, and potential collaborations.

### 4. Predictive Modeling
Using machine learning techniques, we built predictive models to estimate the likelihood of winning for any two random players matched against each other. Features such as player characteristics, network metrics, and community affiliations were used to train the models.
