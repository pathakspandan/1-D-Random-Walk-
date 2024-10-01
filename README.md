## 1D Random Walk with and without Reflective Boundaries
This repository contains simulations of **1D random walks** with two different conditions:

1. *A normal random walk* where the particle can move indefinitely in either direction. 

2. *A reflective boundary random walk* where the particle is confined within a range and "bounces" off the boundaries when it reaches them.

## What is a 'Random Walk'?
A random walk is a mathematical model used to describe a path consisting of a series of random steps. Imagine standing on a straight line (like a number line) and flipping a coin to decide whether to take a step to the left or right. Over time, the particle's position evolves based on these random movements.

'Random Walk' in Physics
In physics, random walks can describe the erratic motion of particles that are frequently bombarded by molecules in a fluid. Traditional methods involving force, velocity, and position equations (like Newton's laws) are often too complicated for such systems. Instead, random walks provide a simple way to model the overall effect of random forces acting on a particle.

In this repository, we explore two types of 1D random walks: a normal random walk and a walk with reflective boundaries.

## Project Files
1. 1-D Random Walk.ipynb:

* This Jupyter Notebook simulates a normal random walk in one dimension.
* The particle moves left or right randomly at each step, with no boundaries.

2. Reflecting Boundary Random Walk.ipynb:

* This notebook simulates a random walk with reflective boundaries.
* The particle is confined between x_min = 0 and x_max = L. If it attempts to move beyond these boundaries, it "bounces" back, reversing its direction.
* Over time, the particle spends an equal amount of time near both boundaries, leading to a probability distribution that differs from the unbounded case.

## Getting Started
1. Clone this repository:
* git clone https://github.com/yourusername/1D-random-walk-with-boundaries.git
2. Open the notebooks:

* For a normal random walk, open *'1-D Random Walk.ipynb'*.
* For a random walk with reflective boundaries, open *'Reflecting Boundary Random Walk.ipynb'*.
3. Run the simulations:
Follow the instructions in the notebooks to simulate both types of random walks.
**Note:** Make your own copy of the notebook before making any changes or starting exercises.

## Simulation Details
### 1-D Random Walk
#### In the normal random walk:

* The particle starts at position 0.
* At each step, the particle has an equal chance of moving left or right.
* The particle can move indefinitely in either direction.

#### In the reflective boundary random walk:

* The particle starts at position 0 on a line bounded by x_min = 0 and x_max = L.
* At each step, the particle moves left or right, but if it reaches a boundary, it "bounces" and is forced to move in the opposite direction.

## Installation
Make sure you have the required Python libraries installed:

* numpy
* matplotlib
  
You can install them via pip:

pip install numpy matplotlib

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!MM

Explore both normal and reflective boundary random walks to see how boundary conditions affect the particle's behavior!
