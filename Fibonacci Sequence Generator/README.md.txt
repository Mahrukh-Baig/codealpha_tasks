# Fibonacci Sequence Generator

This is a Python-based Fibonacci sequence generator that generates a sequence of Fibonacci numbers based on user input. The script also plots the Fibonacci sequence for a better visual representation of how the sequence grows.

## Fibonacci Sequence

The Fibonacci sequence is a series of numbers where each number is the sum of the two preceding ones, usually starting with 0 and 1. That is:


The sequence starts with 0 and 1, and each subsequent number is the sum of the previous two.

## How the Generator Works

The Fibonacci generator in this notebook takes an integer `n` as input, where `n` is the number of terms in the Fibonacci sequence the user wants to generate. The generator follows these steps:
1. Starts with `0` and `1` as the first two terms.
2. Uses a loop to calculate each subsequent number by summing the last two terms in the sequence.
3. Adds each calculated number to a list that holds the Fibonacci sequence.
4. After the sequence is generated, the notebook displays the Fibonacci sequence and plots it for visualization.

## How to Use the Script

1. Clone or download the repository to your local machine.
2. Open the `Fibonacci_Generator.ipynb` notebook in Jupyter Notebook.
3. The notebook will prompt you to input the number of Fibonacci terms you want to generate.
4. Enter an integer when prompted.
5. The Fibonacci sequence will be displayed, and a graph of the sequence will be shown.

### Requirements

- Python 3.x
- Matplotlib (`pip install matplotlib`)

## File Extensions

- The main script for generating the Fibonacci sequence is a Jupyter notebook file: `Code_APLHA TASK-1.ipynb`
- The `README.md` file should be placed in the same directory as the notebook.

## Example

If you input `10` as the number of terms, the output will be:

Fibonacci Sequence: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]

A plot of the Fibonacci sequence will also be displayed.

