# QLearning Python Project
This project contains two Jupyter notebooks that demonstrate how to implement Q-learning in different environments.

## Environment 1: Stick Game
The first environment is a simple stick game where a Q-learning agent plays against a human player. The players each take their turn, drawing between 1 and 3 sticks. The player who draws the last stick loses. The purpose of this environment is to introduce the basic concepts of Q-learning and show how it can be applied to a simple game.

The notebook "stick_game.ipynb" contains the code for this environment. It explains the rules of the game and how the Q-learning agent is implemented. It also shows how to play the game against the agent and how to train the agent to improve its performance.

## Environment 2: Grid World
The second environment is a grid world where the Q-learning agent must navigate to find the winning position and avoid the lost position. The agent can move up, right, left, or down to reach its goal. The purpose of this environment is to demonstrate how Q-learning can be used in a more complex environment.

The notebook "Q-learning.ipynb" contains the code for this environment. It explains how the grid world is set up and how the Q-learning agent is implemented. It also shows how to train the agent and how to evaluate its performance.

## Requirements
This project requires the following packages to be installed:

- numpy
- jupyterlab
- ipython
- nodejs-bin
- jupyter_contrib_nbextensions

## Installation
These packages can be installed by running the following command:
```
pipenv shell
pipenv install --requirements "requirements.txt"
```
to install ipython
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```


to fixed jupyter_nbextensions_configurator error
```
jupyter nbextensions_configurator enable --user
```

## Project Tree Structure
The project has the following tree structure:

- Pipfile
- Pipfile.lock
- Q-learning.ipynb
- README.md
- requirements.txt
- stick_game.ipynb

The `Pipfile` and `Pipfile.lock` files are used by pipenv to manage dependencies. The `Q-learning.ipynb` and `stick_game.ipynb` notebooks contain the code for the two environments. The `README.md` file is this file that you are currently reading. The `requirements.txt` file contains the list of packages required by the project.