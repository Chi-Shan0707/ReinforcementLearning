# Chapter 1: Basic Concepts

## 1.2 state, state space, action

## 1.3 state transition
State transition can be determined or stochastic.

## 1.4 policy
Policy can be ditermined or stochastic.

## 1.5 reward
Reward can be ditermined or stochastic.

## 1.6 trajecotry, return, episode
Trajectory is a state-action-reward chain.<br>
Return is immediate reward plus future reward, namely total reward or cumulative reward.<br>
For discount rate $\gamma \in (0,1)$ , we have discounted return.<br>
When the agent reaches the terminal state, we get an episode.<br>
An episodic task can be converted into a continuing task if we make changes on the terminal state.<br>
- absorbing state: maintain the structure
- discounted return: view the terminal state as a normal one

## 1.7 Markov decision process
It is memoryless, so

$$
P\bigl(s_{t+1}=s' \mid s_t, a_t, s_{t-1}, a_{t-1},\dots,s_0\bigr)
= P\bigl(s_{t+1}=s' \mid s_t,a_t\bigr).
$$


$$
P\bigl(r_{t+1}=r' \mid s_t, a_t, s_{t-1}, a_{t-1}\dots,s_0,a_0\bigr)
= P\bigl(r_{t+1}=r' \mid s_t, a_t \bigr).
$$

