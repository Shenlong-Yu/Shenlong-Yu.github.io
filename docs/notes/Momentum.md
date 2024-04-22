---
share: true
tags:
  - Physics
---
Linear momentum is a conserved vector in an isolated system which comes from space homogeneity.
$$\boldsymbol{P}\equiv \sum_i \frac{\partial L}{\partial \boldsymbol{\dot q_i}}$$

> [!proof]-
> For a infinitesimal displacement $\boldsymbol{\epsilon}$, the radius vector $\textbf{r}$ becomes $\textbf{r} + \boldsymbol{\epsilon}$, thus the change of Lagrangian is
$$\delta L=\sum_i \frac{\partial L}{\partial \boldsymbol{r}_i} \cdot \delta \boldsymbol{r}_i=\boldsymbol{\varepsilon} \cdot \sum_i \frac{\partial L}{\partial \boldsymbol{r}_i}$$
Since $\boldsymbol{\epsilon}$ is arbitrary, the requirement of space homogeneity, i.e., $\delta L = 0$ is equivalent to
$$\sum_i \frac{\partial L}{\partial \boldsymbol{r}_i}=0$$
Plug in the Lagrange equation,
$$\frac{\mathrm{d}}{\mathrm{d} t} \sum_i \frac{\partial L}{\partial \boldsymbol{\dot q_i}}=0$$
From which we define the linear momentum
$$\boldsymbol{P}\equiv \sum_i \frac{\partial L}{\partial \boldsymbol{\dot q_i}}$$

> [!example]-
> For a particle system system whose Lagrangian is
$$L=\sum_a \frac{m_a v_a^2}{2}-U\left(\boldsymbol{r}_1, \boldsymbol{r}_2, \cdots\right)$$
we have the linear momentum 
$$\mathbf{P}=\sum_{\boldsymbol{a}} m_a \mathbf{v}_{\boldsymbol{a}}$$