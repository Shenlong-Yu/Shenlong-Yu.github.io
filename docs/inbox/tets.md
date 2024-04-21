---
tags:
  - Physics/Classical_Mechanics
dg-publish: true
share: true
---
# Hamilton's principle
The true evolution $\mathbf{q}(t)$ of a system described by $s$ generalized coordinates $\mathbf{q}=\left(q_1, q_2, \ldots, q_s\right)$ between two specified states $\mathbf{q}_1=\mathbf{q}\left(t_1\right)$ and $\mathbf{q}_2=\mathbf{q}\left(t_2\right)$ at two specified times $t_1$ and $t_2$ is a stationary point of the action $$S=\int_{t_1}^{t_2} L(q, \dot{q}, t) \mathrm{d} t$$, i.e., $\delta S=0$.
# Lagrange equation
- From Hamilton's principle, we can prove $$\frac{\mathrm{d}}{\mathrm{d} t} \frac{\partial L}{\partial \dot{q}_i}-\frac{\partial L}{\partial q_i}=0 \quad(i=1,2, \cdots, s)$$
	- $L$ is the Lagrangian. Lagrangian is a function which summarizes the dynamics of the entire system.
	- $q$ is the Generalized Coordinates. For systems of $s$ degrees of freedom, any variables $q_1,q_2,\cdots, q_s$ whose Position can be completely inscribed is called the generalized coordinates of this system, and its derivative $\dot{q}$ is called the generalized velocity.