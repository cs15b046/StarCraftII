This repository implements an A2C agent with a Fully Conv model baseline for the
[pysc2](https://github.com/deepmind/pysc2/)
environment as described in the DeepMind paper
[StarCraft II: A New Challenge for Reinforcement Learning](https://deepmind.com/documents/110/sc2le.pdf).
To run and train, use : python run.py experiment --map MoveToBeacon
To evalutate without training, add --eval flag and to visualize the agents, add --vis flag.
See `run.py` for all arguments.