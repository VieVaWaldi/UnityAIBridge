# UnityAIBridge

A custom RL pipeline for Unity MLAgents.

* Using mlagent_envs LLAPI, Rllib and gym
* Rllib for multi gpu and high batch size
* Gym for custom implementations eg. with stable baselines
* Single and MultiAgent
* Model transformation back to unity sentis

## Installation

I am using python 3.10.12, which is necessary for mlagent_envs.

> python3.10 -m venv venv

> source venv/bin/activate

> pip install -r requirements.txt