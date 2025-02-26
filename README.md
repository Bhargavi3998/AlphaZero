# AlphaZero Implementation

This repository contains an implementation of AlphaZero, a Deep Reinforcement Learning (DRL) algorithm for playing complex strategy games. 
AlphaZero, developed by DeepMind, is known for its impressive performance in games like Go, Chess, and Shogi.

## Introduction

AlphaZero combines deep neural networks with Monte Carlo Tree Search (MCTS) to achieve superhuman performance in various board games. 
This implementation aims to provide a clear and adaptable codebase for experimenting with AlphaZero in different games.

## Features

* Modular Design: The implementation is designed to be modular, allowing easy integration with different board games.
* Efficient Training: Utilizes parallelism and GPU acceleration for efficient training of neural networks.
* Self-Play: Implements self-play mechanism to generate training data.
* Model Evaluation: Evaluates the trained models against baseline agents or human players.
* Visualization: Provides tools for visualizing gameplay and training progress. (In-progress)

## Supported Games

- [x] Tic-Tac-Toe
- [x] Connect Four
- [ ] Chess
- [ ] Go
- [ ] Shogi

## Requirements

* Python 3.x
* PyTorch
* NumPy

## Getting Started

1. Clone this repository:
```
git clone https://github.com/yourusername/AlphaZero-Implementation.git'
```
2. Create and activate a new environment:
```
conda create -n alphazero
conda activate alphazero
```
3. Install dependencies:
```
conda env update -f environment.yml
```
4. Run AlphaZero.ipynb notebook
```
python AlphaZero.ipynb
```

