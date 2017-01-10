## Analysing statistics in videogames
> The goal of this project is to create a clear, but still useful website for players of Overwatch, who are interested in improving their gameplay.
 
Andrea van den Hooff
January 2017

#### Game Analytics in E-sports
Multiple studies have said that [a lot of people play video games in the 21st century.](http://www.theesa.com/wp-content/uploads/2015/04/ESA-Essential-Facts-2015.pdf) With the diversity of the current industry in mind, there is a game for everyone. The gaming industry has developed itself so far, that there are enormous gaming tournaments and LAN parties held across the globe. Videogaming as a professional is a valid job for our generation. Money is invested: there are coaches, world cups and serious sponsors, just like any physical sport. One of the essentials to become a better player? Analysing your playstyle, behavior and other statistics created by your videogaming. By analysing these numbers, weaknesses and strengths can be found and improved if necessary. This is critical for any kind of sports, physical or digital. Examples of statistics websites in video gaming are [CS:GO](https://csgosquad.com/top), [LoL](http://www.lolking.net/leaderboards#/na/1) and [Hearthstone](http://www.gosugamers.net/hearthstone/rankings). 

Overwatch is a game by Blizzard, published in 2016. It's relatively young and it's still unclear if the game will be a success competitive-wise. There is a growing e-Sports community. There have been played some tournaments, but it has to be seen if Overwatch could become as big as League of Legends or Counterstrike. (I hope so! :) ) My plan is to create such a website (simplified) for this project. 

#### Similar Projects
Blizzard recently (only a few weeks old) published [Overbuff](https://www.overbuff.com/), a website for the game analytics of Overwatch. This website, however, a lot of information and I find it overwhelming for people new to the game. I would like to use the same statistics, but make it more clear for the user. When looking at a profile at Overbuff, the amount of data is makes it look like there is no clear overview. There is too much data in one view. I would like to make a similar website, which focuses more on the fun part of visualisation and user-friendly usage. Overbuff might be useful for the exact numbers. I want to create something that is simpler to use, while still showing enough data to be interesting to use for players.

#### Sketches & Usage

The main visualisation will be a bilevel partition for the overview of classes, with interactivity for details per class. The idea is as follows: 
![Bilevel partition](/Images/4.png)

Then the overview of the website looks like this:
![like this](/Images/3.png)

I want to compare the user's data with the top 10 players, while being able to choose specific statistics like amount of time played, KDA, etcetera. Most of it will be interactive with each other, but I don't know how distracting that will be and if all the data visualised will be interesting to see. So I'll have to look into that the following days.

#### Obstacles

There is no official API out for Overwatch. There is, however, an [unofficial one](https://api.lootbox.eu/documentation). It will be a challenge to find out how to get it working and then use it's data. The idea is to make a call to this API with a given username by the user and then use that information in the visualisations. It will also be a challenge to decide how to visualise the selected data exactly.

Next to the difficult API usage, a problem that might arise is the amount of data that will be available. It's not well organised and it will b a challenge to consider what categories I want to use. I can look at other game analytics websites to find out what's most important and what they prioritise.

It would be cool to also look at when someone was playing, or how long, and how that affects the numbers, but I'm not sure if that data is available. 

#### Steps to be taken

1. Collect data from the unofficial API
2. Process data to different data structures
  * Bilevel Partition for classes
  * Multiple bar charts for different categories of that class
  * Something to show progress over time
  * Add details like possible comparison with other users and/or current rankings
3. Add interactivity
4. Create user interface
5. Improve overall design

MVP: A simple working website with atleast the personal information working. The parts that compare to other players can be optional. It could be simpler visualised with just a general text on the professional players, which is not interactive.
