The Paper：[__Evolution Strategies as a Scalable Alternative to Reinforcement Learning__](https://arxiv.org/abs/1703.03864)

Openai post about evolution strategies - [blog post](https://blog.openai.com/evolution-strategies/)

The implemention is a single-machine version. And the paper provide a communication-less version for distribution, which depends on __the share
 random seed trick__. And it can be used in many evolution-based model, such as __Dueling Bandits__.
