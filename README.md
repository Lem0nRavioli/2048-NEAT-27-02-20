# 2048-NEAT-27-02-20
Python 2048 with pygame &amp; neat module

- Need to adjust the fitness function to train it properly
- clock.tick() is currently commented, uncomment and add a small amount of fps if you want to follow the evolution
- Completly new to github, and not a veteran coder either, sorry for the very probable rookie mistakes that i've made in this project.

Fitness currently used:
- input : the 16 tiles of each board with a value going from 0(tile n2) to 13(tile8192)
- -1 fitness and removal if the board state did not change between 2 frames
- +0.1 fitness every frame passed
- +x, x beeing the difference of value between the board of the previous frame and the new one, value beeing the summ of all tiles value, this for every frame also


fixed issues :
- Current issue is with the single-board deleting code, when i compare the state of the board before & after a move is called
- Might have to move the big-board declaration inside the eval_genome def after resolution of the bug above, never completed a whole run yet
