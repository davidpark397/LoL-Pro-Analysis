# League of Legends Professional Player Analysis
## Introduction
The 2019 League of Legends World Championship (Worlds 2019) has sparked discussion on the skill level and effectiveness of its players. There is relative disagreement among casual fans, analysts, and even the professional players themselves on how good the Worlds competitors are.

One interesting element of this discussion is player "uniqueness". An idea that gets thrown around a lot in this discourse is how players are irreplaceable, or how players contribute to their teams in untraditional ways. Doinb, the midlaner for FunPlus Phoenix, for example, is said to be better at roaming and being there for his team - something that doesn't form the precipice of gameplay patterns for the more traditional mid lane superstars in Faker and Rookie who are much more lane-dominant, teamfighting mid laners.

This poses an interesting question: how do we first define player uniqueness and how do we best capture what we're talking about when we think of how Doinb affects games in a different way? 

## Overview
This repository contains the versions of data, figures generated, and Python notebook comprise an analysis of 400+ League of Legends players in all major regions (EU, NA, CN, KR) and their performance statistics. Here, I attempt to develop a uniqueness index by looking at player performance statistics, transforming them using PCA, and then comparing them with those of other player sacross regions and roles in order to add to this discussion.

## Data
The data that I will be using for this set of analyses was scraped from https://gol.gg/esports/, which contains different statistics such as win rate, KDA, CSM, Avg WPM, etc. for players from all professional leagues. 

## How to Run
Create a virtual environment and install the packages listed in `requirements.txt` using:
```
pip install -r requirements.txt
```
Download the Python notebook and see what's up!
