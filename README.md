# Differential Privacy in Reinforcement Learning

Report and experiments done to study private RL algorithms for the course of Reinforcement Learning, Master MVA at ENS Paris-Saclay 2022-2023. In this paper, we provide differentially private deep RL algorithms and study the impact of privacy on the learning process.

## Contributions
Our contributions are two folds. (i) We propose central differentially private versions of REINFORCE and DQN algorithms using DP-SGD. (ii) We apply local differentially privacy to theses algorithms. With the increase in privacy, we observe that the learning process is slower and that the convergence is harder to achieve.

## Report
Report with our contributions to find [here](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/report.pdf).

## Code
Python implementation of our experiments to find below:
1. [Classic DQN](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_DQN.ipynb)
2. [Classic REINFORCE](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_REINFORCE.ipynb)
3. [DP-SGD DQN](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_DQN_DP.ipynb)
4. [DP-SGD REINFORCE](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_REINFORCE_DP.ipynb)
5. [LDP DQN](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_DQN_LDP.ipynb)
6. [LDP REINFORCE](https://github.com/AmbroiseOdonnat/RL-Differential-Privacy/blob/main/main_REINFORCE_LDP.ipynb)

