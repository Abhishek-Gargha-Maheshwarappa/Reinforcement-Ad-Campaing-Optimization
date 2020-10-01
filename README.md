# Reinforcement-Learning-Ad-Campaing-Optimization


Using Reinforcement Learning for Optimization of Ads

There kinds of methods have been implemented in the notebook along with random smapling to benchmark the performance each

## **1. Thompson sampling**

**Thompson sampling**, named after William R. Thompson, is a heuristic for choosing actions that address the exploration-exploitation dilemma in the multi-armed bandit problem. It consists of choosing the action that maximizes the expected reward with respect to a randomly drawn belief. The algorithm addresses a broad range of problems in a computationally efficient manner and is therefore enjoying wide use. 

## **2. Upper Confidence Bound (UCB)**

**The Upper Confidence Bound (UCB)** algorithm is often phrased as “optimism in the face of uncertainty.” That is, if a bandit has the potential to be the best we should try it. As one tries bandits more and more the uncertainty around the estimate of its payout shrinks. The algorithm allocates exploratory effort to actions that might be optimal and are in this sense "optimistic."

## **3. Epsilon-Greedy Action Selection**

**Epsilon-Greedy** is a simple method to balance exploration and exploitation by choosing between exploration and exploitation randomly.
The epsilon-greedy, where epsilon refers to the probability of choosing to explore, exploits most of the time with a small chance of exploring.
