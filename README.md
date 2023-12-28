# Perceptron-Based Logic Gates Visualization
Overview
This Python script visualizes the basic logic gates (AND, OR, NAND, NOR, XOR) using perceptrons. It demonstrates how simple neural networks (perceptrons) can simulate these gates by plotting their decision boundaries and the classification of input points.

## Features
Implements perceptron function for binary classification.
Visualizes decision boundaries for AND, OR, NAND, and NOR gates.
Special implementation for XOR gate using a combination of AND, OR, and NAND gates.
Plots input points and their classification on a 2D plot for each gate.
## Dependencies
Python 3.x
NumPy
Matplotlib

To run this script, you need to have Python installed along with the NumPy and Matplotlib libraries. If you don't have these libraries installed, you can install them via pip:

pip install numpy matplotlib


## Usage
To run the script, simply execute it in your Python environment:

python logic_gates_perceptron.py

The script will display a series of plots, each corresponding to a different logic gate, showing how the perceptron classifies different input combinations.

## Inputs and Outputs
The script processes a set of predefined inputs (combinations of 0 and 1) and shows how each logic gate classifies these inputs. The output is a set of plots visualizing the decision boundaries and the classifications.

## Customization
You can modify the script to test different input combinations or even add other types of logic gates by adjusting the perceptron weights and biases.
