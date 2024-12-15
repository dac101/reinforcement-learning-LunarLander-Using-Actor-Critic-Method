
This project implements the Actor-Critic reinforcement learning algorithm to solve the **LunarLander-v2** environment from OpenAI Gymnasium. The main steps include:

- **Environment Setup and Exploration:** Installing necessary libraries (`gymnasium`, `numpy`, `pytorch`) and understanding the state-action space and reward structure.
- **Design of Neural Networks:** Developing separate networks for:
  - **Actor (Policy Network):** Outputs a probability distribution over actions.
  - **Critic (Value Network):** Outputs a scalar value representing state value.
- **Training Loop:** Implementing the Actor-Critic algorithm using:
  - Advantage estimation from the critic's value function.
  - Policy gradient updates for the actor.
  - Mean squared error minimization for the critic.
- **Evaluation and Testing:** Evaluating the model's performance over multiple episodes, plotting learning curves, and comparing with a random baseline policy.

The final implementation includes detailed results, learning curves showcasing cumulative rewards over time, and a discussion of challenges faced and suggestions for improvement.
