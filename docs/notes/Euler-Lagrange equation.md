---
share: true
tags:
  - Physics/Classical_Mechanics
---
From [[Hamilton's principle|Hamilton's principle]], we can get Lagrange equation:
$$
\frac{\mathrm{d}}{\mathrm{d} t} \frac{\partial L}{\partial \dot{q}_i}-\frac{\partial L}{\partial q_i}=0 \quad(i=1,2, \cdots, s)
$$
$L$ is the [[Lagrangian|Lagrangian]] and $q$ is the [[Generalised coordinates|Generalised coordinates]]. 
> [!proof]-
> From Hamilton's principle, we have:$$\begin{aligned}
& \delta S=\delta \int_{t_1}^{t_2} L(q, \dot{q}, t) \mathrm{d} t\\
&=\int_{t_1}^{t_2}\left(\frac{\partial L}{\partial q} \delta q+\frac{\partial L}{\partial \dot{q}} \delta \dot{q}\right) d t\\
&=\int_{t_1}^{t_2}\left(\frac{\partial L}{\partial q} \delta q+\frac{\partial L}{\partial \dot{q}} \frac{d}{d t} \delta q\right) d t \\
& =\int_{t_1}^{t_2}\left[\frac{\partial L}{\partial q} \delta q+\frac{d}{d t}\left(\frac{\partial L}{\partial \dot{q}} \delta q\right)-\frac{d}{d t} \frac{\partial L}{\partial \dot{q}} \delta q\right] d t \\
& =\int_{t_1}^{t_2}\left(\frac{\partial L}{\partial q}-\frac{d}{d t} \frac{\partial L}{\partial \dot{q}}\right) \delta q d t+\left.\frac{\partial L}{\partial \dot{q}} \delta q\right|_{t_1} ^{t_2}=0 \\
&\Rightarrow \frac{d}{d t} \frac{\partial L}{\partial \dot{q}}-\frac{\partial L}{\partial q}=0
\end{aligned}$$
where $\delta  q(t_1)=\delta q(t_2)=0$ to make $q(t_1)+\delta  q(t_1)=q(t_1), q(t_2)+\delta  q(t_2)=q(t_2)$.

> [!example]-
> For a particle system system whose Lagrangian is
$$L=\sum_a \frac{m_a v_a^2}{2}-U\left(\boldsymbol{r}_1, \boldsymbol{r}_2, \cdots\right)$$
plug into the Euler-Lagrange equation,
$$m_a \frac{\mathrm{d} \boldsymbol{v}_a}{\mathrm{~d} t}=-\frac{\partial U}{\partial \boldsymbol{r}_a}\equiv F_a$$
this is exactly the second law of [[Newtonian mechanics|Newtonian mechanics]] . From this we can say that the direction of [[Force|Force]] is the direction of the potential energy function $U$ to reduce the fastest.
