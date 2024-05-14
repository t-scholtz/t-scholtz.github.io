---
title: "Rubik’s Cube - Arm - Lab 7"
layout: post
categories: media
---


## Rubik’s Cube in Arm Assembly

![Tiva Board](/assets/images/tiva_board.png)

Me and my [teamate][tom] created our own version of the [1982 Atari 2600 video game Rubik’s Cube™][lab7] game written entierly in Arm assembly for the [tiva board][board]

## Program Overview

We implemented the classic 1982 Atari 2600 game Rubik’s Cube. The program lets a user move a character around the board trying to solve the cube by moving a player character which can carry one tile/color at a time. 

There is also a menu in which the player can choose game mode options and a pause menu where the player can reset the game if they wish. Once a player looses or wins a game mode they will have the option to reset.
## Program Summary

# Start Up
When the program first loads, a starting animation plays. Then the game boots into the main menu.
Menu
In the menu, the user can press buttons sw2-sw5 to change the game length timer. The user is also able to start the game by pressing the space bar

# Game
The player is able to move the player character using WASD, and is able to pick up tiles by pressing the space bar. The player can also choose to pause the game by pressing sw1

# Pause
In the pause menu the player can chose to restart the game by pressing space, or return to the game by pressing sw1

# Win/Lose
When the player either wins or loses the game they will be presented with a screen showing their score. They can then press space to return to the menu


Below are some flowcharts of the project layout and design
![Flowchart 1](/assets/images/flow1.png)
![Flowchart 2](/assets/images/flow2.png)
![Flowchart 3](/assets/images/flow3.png)


Below is hopefully a demo of the project(if not, sorry I don't know how video embedings works)
<video controls>
  <source src="/assets/images/Lab7ProjectDemo.mov" type="video/mp4">
  Your browser does not support the video tag :/
</video>


[lab7]: https://github.com/t-scholtz/CSE-379_Lab/tree/main/Lab7
[tom]: https://www.linkedin.com/in/tom-mehok-0926b6272/
[board]: https://www.ti.com/tool/EK-TM4C123GXL