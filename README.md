# LEMIPC

> Electronic Arts(c) (hereafter referred to as EA), a small comapany specialized in maple syrup import/export, has decided to widen its circle of activities in order to increase its gain.
In order to do this, they have chosen to enter the emerging market for video game applications.
EA is not planning on taking the easy way out. They want to make a huge splash, and release the first innovative, immersive, addictive (and most importantly) profitable game to ever hit the market.
They are calling upon you to create this masterpiece, which will go down in the history of of video games.

The mission is to develop a program that meets the following requirements:
- The goal is to fight players (divided between several teams) on a two-dimensional game board.
- The last team standing wins.
- To kill a player, a minimum of two players from the same team (and different from the first) must be in contact with the other player. This means on a square next to the one where the player you want to kill is standing (including diagonally).
- The players will be able to move both vertically and horizontally.
- When a player realizes he/she is surrounded by at least 2 players from the opposing team, he/she must leave the game board (yes, because it is well-known that NPC are honest in games. They scrupulously follow the rules. Yep, ask the mustached plumber on his kart if he sometimes cheats. . . nope!)
- A square cannot hold more than one player at a time.

# Language
  - C Programming

### Run

```sh
$ make
$ ./lemipc PATH TEAM_NUMBER
```

PATH: path you’ll give to ftok
TEAM_NUMBER: team number of the current champion (greater than 0)

You need to run the program in 4 different terminal at least (2 equipe of 2) to start the game

### Miscellaneous

There are a few tests in criteirion for this project.
To run, type "make tests_run"

**Authors**

Thibault HEBERT
Charly DAI
