# Markov Decision Process


Search Algorithms are the most common algorithms used practically in all computer applications like google search, google maps, database search, etc. The assumption with search algorithms assumption is that the decisions are always made under certainty; for example, in the figure below, the distance between the nodes is always constant, and the system can easily predict ADB as the shortest path between A to B without any uncertainty.

<div align = "center">


![image](https://user-images.githubusercontent.com/67491030/133155453-88b82959-5609-4a71-affe-5cf7b0a48bd9.png)


</div>

Markov Decision Processes help make such optimal decisions even when there are uncertainities, i.e., the outcome at a particular node is not always fixed and involves a probability factor. Unlike a search problem where everything is deterministic, Markov processes help deal with uncertainties involved at each point, where we take actions that might not end up in what we expected to and affect our decisions. For example, 80% of the time, the path DB is broken due to weather conditions! So, in that case, do we still consider path ADB is to the best possible route to take in all scenarios?

The solution to MDP is defined as a notion of policy (s), a mapping from each state s States to an action a Actions(s). A policy assigns an action to each state, i.e. the action will be chosen each time the system is at state s. The next step that follows is to evaluate these policies and see how good the policy is.

Once the action to be taken at each state is determined by the policy the next step is to evaluate how good the policy is. We can evaluate how well a certain policy does by computing the value function induced by that policy.

If you think about a policy, it will map a state to action and since the process is probabilistic this action can result in multiple random paths. The following exercise is to focuses on how to evaluate these random paths, and the &quot;_Utility_&quot; of a policy is the sum of the rewards through the path.
