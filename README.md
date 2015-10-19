# pathfinder.js
Pathfinder genetic algorithm in javascript.
---

Given a 2D map containing obstacles, a start position and a target (exit) position, pathfinder attempts to discover a route through the map using a genetic algorithm. 

It does this by creating a population of strategies called Programs. Each program has a randomly encoded solution composed of movements (N/E/S/W). A new generation of programs is created using a genetic recombination crossover function. Parent programs are selected using roulette-wheel selection.

