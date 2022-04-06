# Section 3: Q-Learning Intuition

## What is Reinforcement Learning

This is when we train an AI by using rewards and State based on the Actions the AI has take. If the AI does something correctly, we reward it with a point for example
Like training a dog

## The Bellman Equation

s = State, a = Action, R = Reward, y = Discount
When an AI moves accross a field (State), and it successfully reaches the end of the field, it will be rewarded with a point. It will then attribute a value to each step it took to generate the point.
V(s) = max_a(R(s,a) + yV(s'))
An AI uses this formula to calculate if the next step is a viable step or not. It's like a finance equation to calculate the value of a future step

A Markov Process is when your future state, not just your choice, but the environment as well. The Result of your Action is only dependent on the environment, not on how you got there
