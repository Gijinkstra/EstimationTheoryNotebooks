## 2. Kalman filter

**Before you start:** Make sure you have understood [conditioning](../intro/3_conditioning.ipynb)

**About:** In this folder you will find 5+1 Python notebooks.
We start with the [Gauss-Makov model](./1_gauss_markov.ipynb), which, 
roughly speaking, is a discrete-time linear dynamical system 
with noise and some convenient assumptions (normality, independence).
This is a stochastic variant of your classical $x_{t+1}=Ax_t + Bu_t$.
Using this model and [conditioning](../intro/3_conditioning.ipynb)
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

**Next:** [sysid](../sysid/README.md)