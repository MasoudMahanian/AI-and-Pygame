# AI and Pygame

Have you ever wanted to **create a game** and implement your own **artificial intelligence**?

In this repository, I plan to make a game and play with artificial intelligence. Cats always follow mouse But my mouse has a sword ...

Includes two parts:
> tutorial Pygame

> Implementation of the algorithm

# Tutorial File

Follow the tutorial file in order. It is written in a notebook and you can learn it easily. At the end, create the wormy game.

# Pygame and Reinforcement Learning

## multiplayer

>The game is made in this mod.

>Making game graphics.

>How to move with the keyboard.

>Game requirements (collision check, etc.).

## AI implementations

We have several AI implementations for a game:

- The intelligent agent **learns during the game**.
- The intelligent agent has learned **before** starting to play.
- In addition to **learning before** starting the game, the intelligent agent also **learns during the game**.

### Algorithm and Training

>Algorithm: Q_Learning

>in the game: agent also learns in the game

>Before the game:
>- We can only train the mouse (computer).
>- In addition to the mouse, we can also train the cat (the player).
> 

> The second mode is to train the mouse more efficiently The second mode is to train the mouse more efficiently
The cat is not training in the during game.
The advantage of the second case is observed in the game.

### Reward

|mouse:                                             |cat:                         |
|---------------------------------------------------|-----------------------------|
|`'+100 if arrive cat'`                             |-100 if arrive mouse            |
|`"-100 If it falls into a hole"`                   |-100 If it falls into a hole            |
|`-1 In situations that are not in the above state` |+100 if arrive goal|
 |~~~~~~~~|-1 In situations that are not in the above state|


# Saved Data

You can use saved data for convenience and not doing calculations..

# how ot run

1.Clone the repository.

2.Change parameters of  files if you want.

3.Run. 


