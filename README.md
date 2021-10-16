# Parks

Solver for **Parks** logic game.

## Rules

In **Parks** there are differently coloured areas - each of them represents a **park**.
The goal of the game is to plant **trees** using the following rules:

1. Put exactly one **tree** in each **park**, row and column. 
2. The **tree** cannot touch another **tree**.


![img](./data/selva_2.png)

## Solver 

### Data

We exported the image data from the [Parks ∞ Cantica](http://www.andreasabbatini.com/LogicGames.aspx) application for iOS.

The data is located in the `data` directory.

### Data processing

We use `openCV` library for image preprocessing in order to extract the board representing the **parks**.

### Solver

* *brute force* solution - `parks_solver_brute_force.ipynb`

