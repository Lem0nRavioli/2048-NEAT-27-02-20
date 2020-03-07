# 2048-NEAT-27-02-20
Python 2048 with pygame &amp; neat module

- Need to adjust the fitness function to train it properly
- clock.tick() is currently commented, uncomment and add a small amount of fps if you want to follow the evolution
- Completly new to github, and not a veteran coder either, sorry for the very probable rookie mistakes that i've made in this project.


fixed issues :
- Current issue is with the single-board deleting code, when i compare the state of the board before & after a move is called
- Might have to move the big-board declaration inside the eval_genome def after resolution of the bug above, never completed a whole run yet
