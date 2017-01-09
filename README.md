# ProgrammeerProject 

#### Game Analytics in E-sports
Multiple studies have said that [a lot of people play video games in the 21st century.](http://www.theesa.com/wp-content/uploads/2015/04/ESA-Essential-Facts-2015.pdf) With the diversity of the current industry in mind, there is a game for everyone. The gaming industry has developed itself so far, that there are enormous gaming tournaments and LAN parties held across the globe. Videogaming as a professional is a valid job for our generation. Money is invested: there are coaches, world cups and serious sponsors, just like any fysical sport. One of the essentials to become a better player? Analysing your playstyle, behavior and other statistics created by your videogaming. By analysing these numbers, weaknesses and strengths can be found and improved if necessary. This is critical for any sports. Examples are [CS:GO](https://csgosquad.com/top), [LoL](http://www.lolking.net/leaderboards#/na/1) and [Hearthstone](http://www.gosugamers.net/hearthstone/rankings). 

Overwatch is a game by Blizzard, published in 2016. It's relatively young and it's still unclear if the game will be a success competitive-wise. There is a growing e-Sports community. There have been played some tournaments, but it has to be seen if Overwatch could become as big as League of Legends or Counterstrike. (I hope so! :) )

#### Similar Projects
Blizzard recently (only a few weeks old) published [Overbuff](https://www.overbuff.com/), a website for the game analytics of Overwatch. This website, however, a lot of information and I find it overwhelming for new people. I would like to use the same statistics, but make it more clear for the user. When looking at a profile at Overbuff, the amount of data is makes it look like there is no clear overview. There is too much data in one view. I would like to make a similar website, which focuses more on the fun part of visualisation and usage. Overbuff might be useful for the exact numbers. I want to create something that is simpler to use, while still showing enough data to be interesting to use.

#### Sketches & Usage

#### Obstacles

There is no official API out for Overwatch. There is however an [unofficial one](https://api.lootbox.eu/documentation). It will be a challenge to find out how to get it working and then use it's data. It will also be a challenge to decide how to visualise the selected data exactly. A lot of statistics can 

It would be cool to also look at when someone was playing, or how long, and how that affects the numbers, but I'm not sure if that data is available. 

#### Steps to be taken

1. Collect data from the unofficial API
2. Process data to different data structures
  * Bilevel Partition for classes
  * Multiple bar charts for different categories of that class
  * Something to show progress over time
  * Add details like possible comparison with other users, search history, current rankings
3. Create user interface
