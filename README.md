# The Haunted House

## Aim of the game
The aim is to avoid the ghost(s) and collect the key randomly displayed on the screen.
There are 7 levels. For the 1st level, there is only 1 ghost. For the 2nd level, there are 2 steps: 1 ghost for the first step and 2 ghosts for the 2nd steps.
For the level 7, there are 7 steps (1 ghost for the 1st step to 7 ghosts for the 7th step).
You win if you achieve to get the right number of keys according to the level.
You lose as soon as you are touched by a ghost.

## Structure

**1. JavaScript**

Main.js: contains the main variables and functions to play and update the game

Key.js: contains the code for the creation of the key (thanks to a class). The key is randomly displayed on the screen in every new game (and step within a game). 

Player.js : contains the code for the creation of the player (thanks to a class). The player's position is always the same for every new game (and step within a game).

Ghosts.js : contains the code for the creation of the ghosts (thanks to a class). The number of ghosts depends on the level of the game. The position of each ghost is renewed for every new step and/ or game.


**2. HTML**

Where the canvas is defined (width = 850px, height = 450px)


**3. CSS**

Contains the style to apply.

![alt text](/images/image-game.jpg)


## Link
[haunted-game](https://sandrine8304.github.io/haunted-house/)
