# PBLE 1: Smart Delivery Planning – Fractional Knapsack

## Aim
To implement the Fractional Knapsack algorithm using a menu-driven C program to maximize the total value of packages within a given weight capacity.

## Problem Statement
Given a set of packages, each having a value and weight, select packages to maximize the total value without exceeding the knapsack capacity. Packages can be selected partially.

## Algorithm
1. Accept the number of packages, their values, weights, and knapsack capacity.
2. Calculate the value-to-weight ratio of each package.
3. Sort packages in descending order of their value-to-weight ratios.
4. Select packages with the highest ratios first.
5. If a package cannot fit completely, select the required fraction of it.
6. Display the selected packages, total weight used, and maximum value.

## Technologies Used
- Programming Language: C
- Algorithm: Greedy Algorithm
- Sorting Technique: Bubble Sort

## Time Complexity
The overall time complexity is O(n²), due to Bubble Sort. The remaining operations take O(n) time.

## How to Run
1. Download or clone this repository.
2. Compile the program using a C compiler:

   `gcc fractional_knapsack.c -o fractional_knapsack`

3. Run the program:

   `./fractional_knapsack`

   On Windows, run `fractional_knapsack.exe`.

## Features
- Menu-driven interface
- Package details input and display
- Value-to-weight ratio calculation
- Sorting by ratio
- Maximum value calculation using the Fractional Knapsack greedy approach
- Display of selected packages and their fractions

## Result
The Fractional Knapsack problem is implemented successfully using a menu-driven C program and a greedy approach.
