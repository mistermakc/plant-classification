# Reinforcement Learning Model for Car Racing

This repository contains a reinforcement learning model trained to play the Car Racing game.

## Part I: Setting UP the Environment

In this section, we will define the environment that will be used - "CarRaving-v2" and create an instance of it.

**Insight:** The action space that we will be using is continuous and will have 3 different actions:
- **Steering -** Ranges from -1 for full left to +1 for full right.
- **Gas -** Ranges from 0 to 1 for full gas.
- **Brake -** Ranges from 0 to 1 for full brake.

The observation space will consist of 96x96 RGB (3-channel) pixel frames from the gameplay.

## Part II: Running a Baseline of Random Episodes

In this section, we will let the agent take random actions in the environment in order to provide a baseline of what to expect from an untrained agent. This step is not necessary but it's useful to see the difference in performance before and after training the agent.

## Part III: Setting up the Agent & Policy

In this part, we will set up the Agent & Policy using Stable Baselines3 - a high-level Python library for reinforcement learning exercises.

### Create an Environment Instance and Wrap it:

Creating another instance of the environment and wrapping it using DummyVecEnv to allow Stable Baselines to interact with it.

### Setup the Agent and Policy

Create a PPO agent and define the policy it will use.

## Part IV: Training the Agent

Train the agent using the PPO algorithm.

## Part V: Saving and Loading the Model

Learn how to save and load the trained model.

## Part VI: Evaluating the Trained Model

Evaluate the trained agent's performance and compare it to the baseline.

## Part VII: Rendering the Environment and Creating a GIF

Render the environment to see how the trained agent performs visually and create a GIF out of it.

# Requirements

- Python 3.x
- OpenAI Gym
- Stable Baselines3
- Numpy
- ImageIO

# Installation

To set up and run this project, first, clone the repository, and then install the required packages.

# Usage

Run the script to start the training process of the agent. After training, you can evaluate its performance and render the environment to visualize the results.

# License

This project is licensed under the MIT License.
