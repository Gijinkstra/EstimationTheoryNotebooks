## 3. System identification

[*Home*](../README.md)

**Before you start:** Take a moment to revise basic calculus (e.g., derivatives and gradients)

**About:** So far we have assumed that the system dynamics is known, 
e.g., in $x_{t+1}=Ax_t + Bu_t$ we assume we know $A$ and $B$. 
In this section we will instead try to estimate the system matrices from 
data. We'll start with the system $x_{t+1} = Ax_t + w_t$ (no input) and 
we'll assume we have a dataset of values of $x_t$ for $t=0,\ldots, N$
and we will estimate $A$ using the least squares approach. 

If time permits we'll turn our attention to systems of the form 
$$\begin{aligned}x_{t+1} = Ax_t + Bu_t, \\ y_t = Cx_t + Du_t,\end{aligned}$$
where we want to estimate $A$, $B$, $C$ and $D$ from input-output data.
We do so using the Python library [`n4sid`](./2_n4sid.ipynb).


**Contents:**

1. [Basic system identification](./1_sysid_basic.ipynb)
2. [n4sid](./2_n4sid.ipynb)*
3. [Tutorial](./6_tutorial.ipynb)

**Next:** [Bayesian estimation](../bayesian/README.md)