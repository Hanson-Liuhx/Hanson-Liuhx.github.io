---
layout:     post
title:      Algorithmic Game Theory
subtitle:   Chapter 1 Basic Solution Concepts and Computational Issues
date:       2020-08-13
author:     Haoxin
header-img: img/post-bg-coffee.jpeg
catalog: true
tags:
    - Algorithmic game theory
---




## 1.1 Games, Old and New  
**The Prisoner's Dilemma:**  
There are two choices for each player, one is better from a selfish perspective, but hurts the other player.  

**The Tragedy of the Commons**:  
The games (including Prisoner's Dilemma, ISP routing game, Pollution game, etc.) share the feature that there is a unique optimal "selfish" strategy for each player, independent of what other players do. No matter what strategy the opponent plays, each player is better off playing his or her selfish strategy.  

**Coordination Games:**  
There will be multiple outcomes that can be stable. A simple coordination game involves two players choosing between two options, wanting to choose the same (Battle of the sexes).  

**Randomized(Mixed) Strategies:**  
This kind of game which has no stable solutions.  

## Games, Strategies, Costs and Payoffs  
The games we considered above were all *one-shot simultaneous move games*, in that all players simultaneously chose an action from their set of possible strategies.  

**Definition of Simultaneous Move Game**  
Such a game consists of a set of *n* of players.  
*Si* denotes player *i*'s set of possible strategies.  
*si* denotes the strategy selected by player *i* to play this game.  
*s=(s1,...,sn)* denotes the *vector of strategies* selected by all players.  
*S* denotes the set of all possible ways in which players can pick strategies and it is the cardinal product of *Si*.  
*preference ordering*: a complete, transitive, reflexive binary relation on the se tof all strategy vectors S.  

