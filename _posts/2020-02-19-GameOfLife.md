---
layout: post
title: Game of Life
bigimg: /img/GameOfLife.png
---

In this project I created the Game of Life invented by John Conway - a famous british mathematician. This [wikipedia article](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) does a great job explaining what the Game of Life is all about. 

In a nutshell it is grid of cells which can be either alive or dead. If a cell survives, dies or is reborn is determined by the state of its neghboring cells. This process can go on indefinitely but normally the grid reaches a stable state after a while. 

To make my Gme of Life prettier I made the cells change their color as they age and in true Darwinistic spirit I gave them an increased chance to die the older they got. This however made the game reach a stable state way too quickly so I commented those lines out. 

There are two grids available - a flat plane and ball-shaped surface - and everything is made interactive and visualised with Pygame. 

{: .box-note}
**Check out my** [Github](https://github.com/RobinSrimal/GameOfLife) for the code. 
