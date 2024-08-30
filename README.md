# Binomial Asset Pricing Model

This project implements the Binomial Asset Pricing Model in Python. It provides methods to price European call options using a binomial tree approach, with two different implementations: using loops and using nodes.

## Overview

The Binomial Asset Pricing Model is a popular method for pricing options. It models the possible price evolution of the underlying asset over time, represented as a tree with nodes corresponding to possible future prices. The final payoff of the option is calculated at the terminal nodes, and the price is determined by working backward through the tree.

## Features

- **Binomial Tree Representation**: The stock price tree is represented using nodes in a coordinate system \((i, j)\), where \(i\) dictates the time step, and \(j\) dictates the node.
- **European Call Option Pricing**: The project specifically prices European call options using the binomial tree model.

## Installation

### Prerequisites

- Python 3.11 or above
- `numpy` package

#### Inspiration
I followed this tutorial to understand and implement the code:
https://www.youtube.com/watch?v=a3906k9C0fM
