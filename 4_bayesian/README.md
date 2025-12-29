## 4. Bayesian estimation

[*Home*](../README.md)

**Before you start:** You need to have watched the first three videos from [this playlist](https://www.youtube.com/playlist?list=PLXBJk7WTnAgWNib_2rO6EKZ0DiTRfbtSJ) on YouTube.

**About:** More often than not, before we collect data in order to estimate an unknown quantity, we know *something* about it. We may merely know that it is positive, or between 0 and 1. We may know that — roughly speaking — the parameter is *likely* to be *around* a certain value, and we may be more or less sure about this. This *prior* knowledge, or *prior belief* can be combined with the (noisy) observations to obtain a *posterior belief*. This is the essence of Bayesian estimation.

Here we will focus on using the Bayesian estimation framework and, in particular, the maximum a posteriori (MAP) estimation method to estimate system states. We'll discover that when the dynamics is linear and the assumption of the [Gauss-Markov model](../2_kalman/1_gauss_markov.ipynb) hold, MAP yields the Kalman filter equations. However, the MAP approach can be applied with the dynamics is nonlinear, and the noises are not normal, and in presence of state constraints. 

The MAP method boils down to solving optimisation problems (optimisation is the backbone of modern engineering and artificial intelligence). We'll start with a notebook on [optimisation in Python](./1_optimization.ipynb) before we move on to [Bayesian estimation](./2_bayesian_fie.ipynb).

**Contents:** 

1. [Introduction to optimisation in Python](./1_optimization.ipynb)
2. [Bayesian estimation](./2_bayesian_fie.ipynb)

**Next:** [Neural network methods](../5_neural/README.md)