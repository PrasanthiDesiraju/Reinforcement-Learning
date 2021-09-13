**REINFORCEMENT LEARNING**

<div align = "center">
What is the point of intelligence? - To make decisions !

In real-world scenarios, these decisions are often tied to actions that influence the world around it, and that is the point of Data Science :)

Data Science is the discipline of making data useful - Cassie Kozyrkov
</div>

How to impart human intelligence to machines even in cases of uncertainty? This is what reinforcement learning ( RL ) is about, and it the art of learning to make good decisions in an uncertain situation.

RL involves

1. Optimization:  The goal is to get to a good decision and end up with an optimal solution to the problem.
2. Delayed Consequence:  As in the example of a chess game, the actions we make now cannot be identified as good or bad until later in the game. The reward is not always immediate, and can the impact might not be realized until later. This introduces two challenges.

  1. How to Plan your Actions - There has to be a balance between an immediate reward and potential future ramifications when planning out the actions.
  2. How to assign credit/reward -  Understand the causal relationship between the decisions we make in the past and the outcomes in the future.
1. Exploration: The agent learns only from what it tries to do; the decision will be made based only on the explored choices/ experience.
2.  Generalization:  Policy is mapping from an experience to action, and in RL, we try to generalize such a policy that yields a better result for an unknown/unexplored situation. This is a similar problem compared to any other ML algorithm, where the machine learns from the data directly and provides some kind of generalized representation of the task.

How is RL different from Other types of ML categories.


|                        |AI Planning     | Supervised Learning             | Unsupervised Learning | Imitation Learning      |
| -----------------------| ---------------|---------------------------------| --------------------- | ----------------------- |
| Optimization           | Yes            | Yes                             | Yes                   | Yes                     |
| Generalization         | Yes            | Yes                             | Yes                   | Yes                     |
| Exploration            | No             | No                              | No                    | No                      |
| Delayed Consequence    | Yes            | No                              | No                    | Yes                     |
|                        |Given the model of how decisions impact: AlphaGo|Needs Labels. Typically makes only one decision based on a given dataset/experience|There are no labels. Mostly used for clustering|Learn from the experience of others, assumes input of good policies|  


Examples of Reinforcement Learning :

1. Web Advertising
2. Robotic Design
