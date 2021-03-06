# Conway's Game Of Life using React

The Game of Life (sometimes known as Life) is an example of a [cellular automaton](https://en.wikipedia.org/wiki/Cellular_automaton) and zero-player game. It takes place on a two-dimensional grid in which cells can be 'alive' or 'dead'. The status of said cells is defined by a set of rules that takes into consideration the status of the cells neighbors. Patterns evolve over time across the grid with no real user input.

![Game of Life Project](https://media.giphy.com/media/8KXrAXGhBAOv1m1sU0/giphy.gif)

This project uses ReactJS and CSS. The board is rendered with a single `<div>` while the grid utilizes CSS linear-gradient.
The cells are a seperate component that accept x and y as inputs in order to specify its position.

## Installation

``` 
cd game-of-life
npm install
npm start
```

