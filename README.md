# Pacman AI — Reinforcement Learning (Value Iteration & Q-Learning)

This project explores the foundation of **Reinforcement Learning** through the UC Berkeley Pacman AI framework.  
I implemented agents that learn to act optimally in uncertain environments using **Markov Decision Processes (MDPs)** and **Temporal-Difference learning**.

The goal was to teach an autonomous agent how to make good decisions — not by giving it explicit rules, but by letting it **learn through experience**.

This project demonstrates:
- Use of Markov Decision Processes (MDPs) to model environments
- Implementation of Value Iteration using Bellman equations
- Implementation of Q-Learning for model-free learning
- Visualization of learned policies in Gridworld

---

## Concepts Implemented
- **Markov Decision Processes (MDPs):** Defined environments in terms of states, actions, rewards, and transitions.  
- **Value Iteration:** Used Bellman equations to iteratively compute the optimal value function and derive a policy.  
- **Q-Learning:** Implemented a model-free algorithm to learn action-value estimates from experience.  
- **Exploration vs. Exploitation:** Balanced random exploration (ε-greedy) with leveraging known good actions.  

---

## Workflow 

```
Environment (MDP)
      |
      v
+---------------------+
|  Value Iteration    |
|  Bellman Updates    |
+---------------------+
      |
      v
+---------------------+
|   Q-Learning Agent  |
|   Learn from Rewards |
+---------------------+
      |
      v
+---------------------+
|   Optimal Policy    |
|   (Best Actions)    |
+---------------------+
```



## What I Learned

Working on this project helped me connect theory to practice:

- I learned how **dynamic programming** (Value Iteration) and **reinforcement learning** (Q-Learning) are two sides of the same coin — one assumes full knowledge of the world, while the other learns directly from interaction.  
- I gained hands-on experience debugging stochastic environments and seeing how **hyperparameters like learning rate (α)** and **discount factor (γ)** affect convergence.  
- I improved my ability to **visualize agent behavior** by watching the learned policy evolve over time in Gridworld.  
- Most importantly, I developed a deeper intuition for **how agents learn from reward signals**, and how this connects to real-world AI systems like robotics, recommender systems, and autonomous driving.



## Tools Used

`Python 3.8+`, `NumPy`, `Tkinter`, `Terminal/Text Display`, `Gridworld Simulation`



## Outcome

This project demonstrates how reinforcement learning agents can discover optimal strategies through interaction with their environment.
It strengthened my understanding of value-based learning, policy derivation, and how algorithmic principles translate into real-world decision-making.


## Attribution

This project builds upon the UC Berkeley CS188 Pacman AI Projects.
