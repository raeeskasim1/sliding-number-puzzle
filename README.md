# Sliding Number Puzzle

Eight tiles, one empty square, and a shuffled board that always has a solution.



## Try it

Play with tile clicks and arrow keys, undo a move, and start a fresh puzzle.

## How it works

The initial board is shuffled by legal moves from the solved state, preserving solvability. Legal moves use Manhattan adjacency to the gap. Undo stores earlier board states and removes the corresponding move count. No external puzzle generator is used.

