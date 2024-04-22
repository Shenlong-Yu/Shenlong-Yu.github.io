---
share: true
tags:
  - Physics
---
Energy is a conserved quantity in an isolated system which comes from time homogeneity.
$$E\equiv \sum_i \dot{q}_i \frac{\partial L}{\partial \dot{q}_i} -L$$
> [!proof]-
> The total derivative of Lagrangian is
$$\frac{d L(q, \dot{q}, t)}{d t}=\sum_i \frac{\partial L}{\partial q_i} \dot{q}_i+\sum_i \frac{\partial L}{\partial \dot{q}_i} \ddot{q}_i$$
plug in the Lagrange's equation,
$$\frac{d L}{d t}=\sum_i \dot{q}_i \frac{d}{d t} \frac{\partial L}{\partial \dot{q}_i} +\sum_i \frac{\partial L}{\partial \dot{q}_i} \ddot{q}_i=\sum_i \frac{d}{d t}(\frac{\partial L}{\partial \dot{q}_i} \dot{q}_i)$$
Thus,
$$ \frac{d}{d t}(\sum_i \dot{q}_i \frac{\partial L}{\partial \dot{q}_i} -L)=0$$
From which we define the energy
$$E=\sum_i \dot{q}_i \frac{\partial L}{\partial \dot{q}_i} -L$$

> [!example]-
> For a particle system system whose Lagrangian is
$$L=\sum_a \frac{m_a v_a^2}{2}-U\left(\boldsymbol{r}_1, \boldsymbol{r}_2, \cdots\right)$$
the energy is
$$E=\sum_a \frac{m_a v_a^2}{2}+U\left(\boldsymbol{r}_1, \boldsymbol{r}_2, \cdots\right)$$
