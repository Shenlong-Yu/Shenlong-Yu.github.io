---
share: true
tags:
  - Math/Statistics
  - Physics/Statistical_Physics
  - Computer_Science/Machine_Learning
---
Rejection sampling is a basic [[sampling|sampling]] method used to generate observations from a distribution.
It can solve the integration difficult of the [[inverse transform sampling|inverse transform sampling]].
# Process
1. To make a sampling for our target distribution $f(x)$, we first set a proposal distribution $g(x)$ and then rescale it by $M$ to envelope $f(x)$. Obviously, $M$ should satisfy $Mg(x)\geq f(x)$. ![[Rejection sampling_image_1.png|300]]
2. For a certain sample $a$, generate a [[Uniform distribution|Uniform distribution]] sample b, if $f(a) > b$ we accept the sample, otherwise reject. ![[Rejection sampling_image_2.png|500]]
The distribution of b is $U(0,1)*Mg(x)$, thus we have the judgment condition
$$
\text{accecpt sample, if}[\frac{f(a)}{Mg(a)}>U(0,1)].
$$
4. We finally obtain samples that conform to the target function distribution. ![[Rejection sampling_image_3.png|300]]
# Limitation
As the proposal distribution should always envelope the desired distribution $Mg(x)\geq f(x)$, so that a large amount of samples are wasted when the desired distribution is sharpe. ![[Rejection sampling_image_4.png|300]]
This can be solved by [[Markov chain Monte Carlo|MCMC]].
