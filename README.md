# WIDS_submission
A repo created to submit the solved WIDS assignments by me.

The first assignment given to us was about learning NumPy library of python, as it is useful in this project. it makes coding the algorithm simple and easy.
The second week was focused on understanding value function and policies, and implementing algorithms on the Multi-Armed Bandit Problem. Policy:- A policy π is a mapping from states to a probability distribution over actions. Value function:- The value function of a policy π is the expected return starting from state s and thereafter following π. The multi-armed bandit problem models an agent facing a set of k actions (arms), each producing stochastic rewards from a Normal distribution with unknown mean. At each time step, the agent chooses one arm and observes its reward, with the objective of maximizing cumulative reward over time. In our version, there are 10 arms.
The third assignment aimed at teaching us about Markov Decision Process (MDP), and then oding them, and also understand Bellman Optimality Equations. A Markov Decision Process (MDP) is a mathematical framework used to model sequential decision-making where outcomes are partly random and partly controlled by an agent. MDPs define an agent interacting with an environment over discrete time steps to maximize long-term rewards, adhering to the Markov property where future states depend only on the current state and action.
The final week was about implementation of our learnings about core reinforcement learning so far for a stock trading task. In this project, I implemented a complete RL pipeline for algorithmic trading. The main components included:
•	A custom trading environment that simulates market interaction using historical stock price data.
•	A tabular Q-learning agent that learns an optimal policy over discrete states and actions.
•	An evaluation framework to test the trained agent on unseen data.
•	A baseline comparison with a Buy-and-Hold strategy to contextualize the agent’s performance.
