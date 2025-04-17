# OPTIMIZATION-MODEL

# Optimization Models: Profit Maximization vs Cost Minimization

This project demonstrates the use of **Linear Programming (LP)** using Python and PuLP to solve a real-world business optimization problem: maximizing profit and minimizing cost in a manufacturing scenario.

## Problem Statement

A company produces four products: A, B, C, and D. Each product has:
- Specific profit and cost per unit
- Different usage of machine hours and raw materials
- Capacity constraints on three machines
- A total raw material limit
- A minimum production requirement

We solve two linear programming models:
1. **Profit Maximization**
2. **Cost Minimization**

Each model determines the optimal number of units to produce for each product.

## Features

- Uses PuLP for linear optimization
- Parameterized constraints (`min_production`, `raw_material_limit`)
- Shadow price and reduced cost analysis
- Matplotlib visualization comparing the two models

## Visualization

A side-by-side bar chart shows production plans from both models.

## Technologies Used

- Python 3
- PulP
- Matplotlib

  ## Output
  ![Image](https://github.com/user-attachments/assets/0e129b07-76ee-4782-a6d8-794c72041050)
