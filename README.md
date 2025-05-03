# lab-report-5
# N-Queens Problem Solver using Genetic Algorithm 🧬♛

This project solves the classic **N-Queens problem** using a **Genetic Algorithm** written in Python. The N-Queens problem asks: _How can N queens be placed on an N×N chessboard so that no two queens attack each other?_

This solution evolves a population of potential solutions over generations, using natural selection, crossover, and mutation to find a configuration with no conflicts.

## 📌 Features

- Customizable board size (`N`)
- Simple and clean implementation
- Tournament selection and single-point crossover
- Mutation for diversity
- Fast convergence on typical board sizes (e.g., 8x8)

## 🧠 Genetic Algorithm Overview

- **Chromosome Representation**: A list of length `N`, where the index represents the column and the value represents the row of the queen.
- **Fitness Function**: Counts the number of non-attacking queen pairs.
- **Selection**: Tournament selection (size = 3).
- **Crossover**: Single-point crossover.
- **Mutation**: Random gene mutation with a small probability.

## 🧪 Example Output

Solution found in generation 47
One solution: [0, 4, 7, 5, 2, 6, 1, 3]
github link:
