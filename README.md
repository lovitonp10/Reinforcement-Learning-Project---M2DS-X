# Reinforcement-Learning-Project-M2DS-X
Study and implementation of the paper [Deep Reinforcement Learning From Human Preferences.](https://arxiv.org/abs/1706.03741) This work was carried out as part of the RL course of the Intitut Polytechnique de Paris' master's degree in Data Science.

### Experiment

The implementation uses the CartPole environment from OpenAI Gym and TensorFlow. We opted to experiment with these techniques using the CartPole problem, a prevalent challenge in reinforcement learning. The objective of this game is to maintain the
balance of the pole for as long as feasible. To accomplish this, the system is managed by administering a force of either +1 or -1 to the cart. With every action performed, the environment provides multiple parameters for evaluation, including the cart’s position and velocity, the pole’s angle, and the pole’s velocity.

We made three different experiments:
1. With Human Preferences
2. Without Human Preferences
3. With Human Preferences and fitting the Reward function.
