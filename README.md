# PPO Gym-Platform

This repository implements the Proximal Policy Optimization (PPO) algorithm within a gym-platform environment using RLlib.

## Installation

You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Training

To find the optimal hyperparameters, we perform a grid search before initiating the training process. The objective is to achieve the highest possible reward within the specified environment.

## Interpretability

For model interpretability, we employ global surrogate models to gain insights into the trained model.

## Videos

Explore the [videos](videos) folder for recordings showcasing the trained policy's performance within the environment.
