# A Simple Coin Game, First Step Analysis and Simulation
This work analyzes a simple coin game involving two players, a pot, several coins, and a die. First step analysis is used to determine the expected length of the game in cycles and the distribution of cycle counts is estimated using parametric probability density estimation on the output of a game simulated with Python. 

The rules of the game will be defined as follows: if a player rolls a 1, nothing happens, if a player rolls a 2, the player takes all the coins in the pot, if a player rolls a 3, the player takes half of the coins in the pot (rounded down), and if a player rolls a 4, 5, or 6, the player puts 1 coin in the pot. If the pot is empty and a player rolls a 2 or 3, nothing happens (the game continues). If a player rolls a 4, 5, or 6 and the player doesn’t have any coins, the game ends. A cycle is defined as a set of two turns, one by player A, then one by player B. If the game ends on player A’s turn, that turn is counted as a full cycle. 

The final write-up is included in: <br>
* **report.pdf** 

The Python code is broken out into two Jupyter notebooks focusing on first step analysis and simulation:<br>
* **code/first_step_analysis.ipynb** <br>
* **code/simulation.ipynb**
