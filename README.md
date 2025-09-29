This project demonstrates how to achieve high-precision quantum metrology using digital twin algorithms. This encompasses training neural networks to predict quantum system evolution and employing reinforcement learning to learn adaptive optimal control strategies.

Virtual environment:

python3.8.19

torch2.4.0

qutip4.7.6

matplotlib3.7.2

Code file:

rnn: This folder contains the complete implementation process of the quantum system evolution predictor, including data collection, network construction, and its training and testing.

dqn_main.py: The main program for the reinforcement learning component—execute this code to initiate QDTS's training.

dqn_env.py: This file is used to simulate the reinforcement learning environment.

dqn_agent: This file defines the reinforcement learning network model and training method.

Hamiltonian.py: This file is used to simulate quantum systems and their evolution.

test.py: This file evaluates the performance of the trained QDTS model, ultimately displaying its CFI.
