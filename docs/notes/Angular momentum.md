---
share: true
tags:
  - Physics
---
![[Angular momentum_image_1.png|150]]
Angular momentum is a conserved vector in an isolated system which comes from space isotropic.
$$\boldsymbol{M}\equiv \sum_a \boldsymbol{r_a} \times \boldsymbol{p_a}$$

> [!proof]-
> For an infinitesimal rotation, from Hamilton's principle we have 
$$\delta L=\sum_a\left(\frac{\partial L}{\partial \boldsymbol{r}_a} \cdot \delta \boldsymbol{r}_a+\frac{\partial L}{\partial \boldsymbol{v}_a} \cdot \delta \boldsymbol{v}_a\right)=0$$
for an infinitesimal rotation vector $\delta \boldsymbol{\varphi}$ , 
$$|\delta \boldsymbol{r}|=r \sin \theta \cdot \delta \varphi, \delta \boldsymbol{r}=\delta \boldsymbol{\varphi} \times \boldsymbol{r}, \delta \boldsymbol{v}=\delta \boldsymbol{\varphi} \times \boldsymbol{v}$$
from Momentum proof, 
$$\partial L / \partial \boldsymbol{v}_a=\boldsymbol{p}_a, \quad \partial L / \partial \boldsymbol{r}_a=\dot{\boldsymbol{p}}_a$$
plug into the equation
$$\sum_a\left[\dot{\boldsymbol{p}}_a \cdot\left(\delta \boldsymbol{\varphi} \times \boldsymbol{r}_a\right)+\boldsymbol{p}_a \cdot\left(\delta \boldsymbol{\varphi} \times \boldsymbol{v}_a\right)\right]=0$$
from the property of Cross product, we extract $\delta \boldsymbol{\phi}$
$$\delta \boldsymbol{\varphi} \cdot \sum_a\left(\boldsymbol{r}_a \times \dot{\boldsymbol{p}}_a+\boldsymbol{v}_a \times \boldsymbol{p}_a\right)=\delta \boldsymbol{\varphi} \cdot \frac{\mathrm{d}}{\mathrm{d} t} \sum_a \boldsymbol{r}_a \times \boldsymbol{p}_a=0$$
since $\delta \varphi$ is arbitrary, we define
$$\boldsymbol{M}\equiv \sum_a \boldsymbol{r_a} \times \boldsymbol{p_a}$$









