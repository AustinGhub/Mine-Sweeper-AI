# Mine-Sweeper-AI Solver

This project aims to develop an AI-powered solver for the popular game Minesweeper. The AI algorithm is designed to tackle maps of varying difficulties, including easy, medium, and hard levels. By leveraging the principles of machine learning and data mining, the AI solver can analyze the game board, make intelligent decisions, and uncover safe squares while avoiding mines.

# Features
Intelligent AI solver capable of handling easy, medium, and hard levels of Minesweeper maps.
Automatic identification of safe cells based on logical deductions and probability calculations.
Efficient exploration strategy to minimize the risk of hitting a mine.
User-friendly command-line interface for interacting with the Minesweeper AI solver.


# Algorithm Overview
The Minesweeper AI solver employs a combination of techniques to solve the game:

1. Safe Cell Identification: The AI identifies safe cells based on logical deductions derived from neighboring cells. It examines the number of adjacent mines and the number of unrevealed cells to make informed decisions.

2. Probability Calculation: In scenarios where logical deductions alone are insufficient, the AI assigns probabilities to unrevealed cells to assess the likelihood of containing mines. It uses statistical analysis and data mining techniques to estimate these probabilities.

3. Exploration Strategy: The AI follows an exploration strategy that prioritizes the cells with the lowest probability of containing mines. This approach minimizes the risk of hitting a mine early in the game and maximizes the chances of revealing safe cells.
