# trade-dice-cpp
cpp core of trade dice

UNDER DEVELOP

# Introduction
This project, named 'Trade-Dice', is a practical implementation based on my recent study of system design. Utilizing C++ as the core framework and Python scripts for algorithm execution, each Python script acts as an individual dice, predicting the future trend of a stock or cryptocurrency within a given time period. The prediction results are then used for reverse training to determine the weight of each dice, aiming to achieve more accurate predictions. Of course, this project is primarily for entertainment purposes, and it is not intended to be used as a real trading tool. The main focus is to learn how to handle data processing and concurrency.

Roll the dice, and do the trade.

The system will run on a single machine, 
# Design
## functional requirement:
<ol>
<li>fetch live price data</li>
<li>calculate indicators with price</li>
<li>put each indicator into a dice</li>
<li>roll the dice and generate prediction according to each indicators</li>
<li>data visualization</li>
<li>weight each dice</li>
</ol>

![flow](https://github.com/metazyc/trade-dice-cpp/assets/20816770/d556158f-8648-438e-add0-a7ea7b1fca98)
