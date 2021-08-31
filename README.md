# Perspectron

insert gif of game

## Idea
You have limited movements to reach the goal. To do so you will have to change your perspective:
Instead of moving the player, move the goal. Instead of moving the goal, move the block it rests on. Instead of going to the right, turn the playing field clockwise and move down. From these simple rules a lot of interesting, levels can be designed, which challenge the players intuitions and

## Future Graphics
The prototype of the game is not really aethetically interesting, so I am in the process of polishing the graphics. 
Sadly the transfer to the more compelling system is not done yet, but here is an outlook to the future visuals of the game.

![](gifs/future.gif)

## Mechanics
Turn the playing fields and collect additional resources

![](gifs/rotate_collect.gif)

Have more then one player, so that you have to coordinate their movement.

![](gifs/2_player.gif)

Move blocks to form path/move players/move goals

![](gifs/blocking.gif)

Your movement resources are tied to a color -> Change the color of your player and tile, so that you can bridge the gap by moving the tiles.

![](gifs/color_swap.gif)

### Future Mechanics
Turn the playing field to from a 3 dimensions to 2, so that height differences disappear and you move over block
(You can also generate the effect of Esher paintings this way)

## Content
Right now their are around 50 interesting levels.

## Sequences
Levels are organized into sequences/chapters, which riff off the same concept. I want to explore the "idea-space" of a mechanic in this way.
Examples of this are:
- Have the same layout, but vastly different solutions, caused by small differences
- Have different layouts but similar solutions
- etc.

This sequence explores the ways of transporting the player across a gap, by arranging the black blocks in the right sequence.

![](gifs/sequence2.gif)

1. Your are limited on your ability to move upward with the black blocks, but can go through the middle with two blocks.
2. The only difference is that the path to the middle is closed, but that small change means you have to block differently.
3. The level seems impossible at first, you simply do not have enough moves with the black blocks. But you can solve it in a different way, then the first two, and use the unmoveable blocks as a bridge to the other side. (subverting the expectation of the solution)

## Complications
When combining the different gameplay elements, arbitrarily hard levels can be constructed: a combinatorial explosion of possiblilities occurs. Here is a more complicated level, which has block moving and a four players.

![](gifs/complicated.gif)

## Game Engine
Since the game is limited in scope and graphics, I wrote the game engine for this project myself. Features of it are:
- automatic playback of solutions
- a custom level editor, which makes it easy to construct new levels
- etc.
