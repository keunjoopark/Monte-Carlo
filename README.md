# Monte-Carlo

Dynamic Programming approaches assume perfect knowledge of the environment.

Monte Carlo methods learn directly from experience collected by interacting with the environment. An episode of experience is a series of (State, Action, Reward, Next State) tuples. MC methods work based on episodes. It is averaging complete returns.

Monte Carlo Policy Evaluation: To estimate the state-value function V(s) for a given policy, sample episodes of experience and estimate V(s) to be the reward received from that state onwards averaged across all of your experience. 
