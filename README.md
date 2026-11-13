# Conway's Game of Life

A Python implementation of Conway's Game of Life, based on Project #13 from
*The Big Book of Small Python Projects* by Al Sweigart.

The board is a 79×20 grid of cells that starts out randomly alive or dead.
Each step, every cell updates at once using three rules:

- A living cell with 2 or 3 living neighbors stays alive.
- A dead cell with exactly 3 living neighbors becomes alive.
- Every other cell dies or stays dead.

The grid wraps around at the edges, so every cell has exactly 8 neighbors.

## Run it

    python conwaysgameoflife.py

Press Ctrl-C to quit.

## Files

- `conwaysgameoflife.py`: the simulation
- `conways_game_of_life.pptx`: slides explaining how the code works
