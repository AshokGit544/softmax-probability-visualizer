# Softmax Probability Visualizer

I built this project to understand how Softmax works in multi-class classification.

In this project, I used Python, NumPy, and Matplotlib to take raw output scores from a model and convert them into probabilities.

## What I did

I started with raw scores for 3 classes:

- Apple
- Banana
- Orange

Then I applied the Softmax function to convert those scores into probabilities.

I also printed the steps clearly, including:

- raw scores
- shifted scores
- exponential values
- final probabilities

After that, I plotted the probabilities using a bar chart.

## Why I did this project

I did this project to understand:

- what logits are
- how Softmax converts logits into probabilities
- why probabilities sum to 1
- why the largest score gets the highest probability
- why subtracting the maximum value helps numerical stability

## What I learned

From this project, I learned that:

- Softmax is used for multi-class classification
- raw scores are not probabilities
- Softmax makes model output easier to understand
- subtracting the max score helps avoid overflow
- the final output always sums to 1

## Tools I used

- Python
- NumPy
- Matplotlib

## Output of the project

This project gives:

- raw score values
- Softmax probabilities
- step-by-step calculation
- probability bar chart

## How to run

1. Open the code in Google Colab or Jupyter Notebook
2. Run the cell
3. View the printed output and chart

## Project goal

I made this project to understand the basics of Softmax in a practical and visual way.
