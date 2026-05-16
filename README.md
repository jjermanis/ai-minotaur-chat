# ai-minotaur-chat
3D Maze game. Escape the Minotaur!


## Overview
You are trapped in a maze. After some time, The Minotaur will chase you. Escape the maze as fast as you can, before you are caught.

When you escape a maze, you end up in a bigger maze. Escape five mazes in a row to truly escape.


## Description
Looking at the 2D map, the player will always start in the upper-left corner of the map. The goal is to get to the lower-right corner of the map. The exit stands out - it is green.

The Minotaur also starts in the upper-left corner of the map. The Minotaur starts several seconds after you start moving. The Minotaur always goes down the correct path to get to the player. He speaks during the game to help let you know where he is. He says "Awake" when he first appears. He says "Go" when he starts to chase you. He says "Food" when he sees you. He says something else if he catches you.

There are two windows to look at on the screen. On the left-side is a 3D view of the maze, seen from the perspective of the player. On the right-side is a 2D view, looking top-down on the maze. 

The controls for the game are the arrow keys. Left and right arrow turn 90 degrees in the matching direction. The up arrow steps one square forward. You cannot walk through walls, and there are no ways to get through a wall.

When you reach the exit of a maze, press the Next Level button to proceed. There are five levels to the game. Each level gets larger, and The Minotaur moves quicker.

There is a mute button in the lower-left corner to silence noise from this game.

## Details
Interesting design note. Yes, The Minotaur appears on the 3D screen. Yes, you look forward on the 3D screen. So, yes, you very often have your back to The Minotaur and don't see him.

The Minotaur uses a breadth-first algorithm to chase the player. The Minotaur will always chase you efficiently.

The movement of The Minotaur is fair. The speed is how many milliseconds it takes for The Minotaur to make each move. Taking a step forward or turning: each of those is considered a move.

For a modeling standpoint, your point-of-view is 5 feet tall. The walls are 12 feet tall. The Minotaur is 10 feet tall.


## From Release #1 (Build 15 on 5/18/26)
Initial version of the game, based on ai-3d-maze

