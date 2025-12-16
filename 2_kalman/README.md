## 2. Kalman filter

[*Home*](../README.md)

**Before you start:** Make sure you have understood [conditioning](../1_intro/3_conditioning.ipynb).
You also need to watch the **first five videos** from [this playlist](https://www.youtube.com/playlist?list=PLXBJk7WTnAgWNib_2rO6EKZ0DiTRfbtSJ) on YouTube **as well as** videos [No 12](https://www.youtube.com/watch?v=vjYsR4hYoEU&list=PLXBJk7WTnAgWNib_2rO6EKZ0DiTRfbtSJ&index=12) and [No 13](https://www.youtube.com/watch?v=YFnLIwYFu2Q&list=PLXBJk7WTnAgWNib_2rO6EKZ0DiTRfbtSJ&index=13). 

**About:** In this folder you will find 5+1 Python notebooks.
We start with the [Gauss-Makov model](./1_gauss_markov.ipynb), which, 
roughly speaking, is a discrete-time linear dynamical system 
with noise and some convenient assumptions (normality, independence).
This is a stochastic variant of your classical $x_{t+1}=Ax_t + Bu_t$.
Using this model and [conditioning](../1_intro/3_conditioning.ipynb)
we will then derive the [Kalman filter](./2_kalman_basic.ipynb).
We will then apply the Kalman filter to a simple GPS-based localisation
problem. To fully appreciate the capabilities of the Kalman filter
we will then look at a few [applications](./4_kalman_variants.ipynb): 
e.g., we can apply the KF
to dynamical systems with an unknown drift ($x_{t+1}=Ax_t + Bu_t + c_t$),
or cases where the sensor is biased (which is typically the case in 
practice). Lastly, we will introduce the [extended KF](./5_ekf.ipynb),
which can be used when the dynamics or output equation are nonlinear;
it's not a great solution, but often it works.

**Contents:**

1. [Gauss-Makov model](./1_gauss_markov.ipynb)
2. [Kalman filter](./2_kalman_basic.ipynb): an introduction
3. [Application to positioning](./3_kf_positioning.ipynb)
4. [Variants of the KF](./4_kalman_variants.ipynb)
5. [Extended KF](./5_ekf.ipynb)
6. [Tutorial](./6_tutorial.ipynb)

**Next:** [sysid](../3_sysid/README.md)