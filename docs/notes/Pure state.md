---
tags:
  - Physics/Quantum_Computing
share: true
---
State
$$
|\psi\rangle=\cos \theta|0\rangle+e^{i \phi} \sin \theta|1\rangle=\left(\begin{array}{c}
\cos \theta \\
e^{i \phi} \sin \theta
\end{array}\right)
$$
Density matrix
$$\begin{aligned} \rho=|\psi\rangle\langle\psi| & =\frac{1}{2}\left(\begin{array}{cc}2 \cos ^2 \theta & e^{-i \phi} \sin 2 \theta \\ e^{i \phi} \sin 2 \theta & 2 \sin ^2 \theta\end{array}\right) \\ & =\frac{1}{2}\left(\begin{array}{cc}1+\cos 2 \theta & \sin 2 \theta \cos \phi-i \sin 2 \theta \sin \phi \\ \sin 2 \theta \cos \phi+i \sin 2 \theta \sin \phi & 1-\cos 2 \theta\end{array}\right) \\ & =\frac{1}{2}(I+\vec{n} \cdot \vec{\sigma})\end{aligned}$$
[[Born rule|Born rule]]
$$\begin{aligned} P\left(\left\langle\psi_n \mid \psi_m\right\rangle\right) & =\left|\left\langle\psi_n \mid \psi_m\right\rangle\right|^2 \\ & =\left(\left\langle\psi_n \mid \psi_m\right\rangle\left\langle\psi_m \mid \psi_n\right\rangle\right) \\ & =\operatorname{Tr}\left[\left|\psi_n\right\rangle\left\langle\psi_n \mid \psi_m\right\rangle\left\langle\psi_m\right|\right] \\ & =\operatorname{Tr}\left[\frac{1}{2}(I+\vec{n} \cdot \vec{\sigma}) \cdot \frac{1}{2}(I+\vec{m} \cdot \vec{\sigma})\right] \\ & =\frac{1}{4}(2+\operatorname{Tr}(\vec{n} \cdot \vec{\sigma} \cdot \vec{m} \cdot \vec{\sigma})) \\ & =\frac{1}{2}(1+\vec{n} \cdot \vec{m})\end{aligned}$$
Entanglement check
To composite system into two subspaces, we expand the state by the basis vectors of these two subspaces
$$\begin{equation*}
|\psi\rangle_{A B}=\sum_{a, b=1}^D \psi_{a b}|a\rangle_A|b\rangle_B
\end{equation*}$$
Schmidt decomposition prove that you can always have a simpler general form
$$\begin{equation*}
|\psi\rangle_{A B}=\sum_{c=1}^d \sqrt{\lambda_c}|c\rangle_A|c\rangle_B
\end{equation*}$$
The number $d$ is called the Schmidt number, $d \leq D$, if all $\lambda$ 's are non-zero, $d=D$ If $d=1$, the pure state is a product state.
If $d>1$, the pure state $|\psi\rangle_{A B}$ is entangled.