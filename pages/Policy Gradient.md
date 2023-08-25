- Use neural network, $\theta$ to construct the policy, $\pi(a|s)$
  $\pi(a|s)$ outputs a distribution, which is a [[PDF]] of action, $a$ 
  ![image.png](../assets/image_1691832163926_0.png){:height 139, :width 532}
- **Main objective** of policy gradient: 
  maximise $E_s[V(s; \theta)]$ by learning $\theta$
  ![image.png](../assets/image_1691871679889_0.png)
- **Form 1**: only applicable for discrete action
  **Form 2**: applicable for discrete and continuous action
  ![image.png](../assets/image_1691872512065_0.png){:height 256, :width 780}
- **Form 1**: only applicable for discrete action
  ![image.png](../assets/image_1691872630490_0.png)
- **Form 2**: leverages monte carlo sampling method
  Since
  $$E_A[g(A, \theta)]=\frac{\partial V(s;\theta)}{\partial\theta}$$
  $g(\hat{a}, \theta)$ is an unbiased estimate of $\frac{\partial V(s;\theta)}{\partial\theta}$
  ![image.png](../assets/image_1691872753481_0.png)
- **Framework of Policy Gradient**
  [[stochastic policy gradient]] is used, since $a$ is randomly sampled  at every iteration.
  ![image.png](../assets/image_1691874271809_0.png)
  $q_t$ can be estimated by:
	- [[Monte Carlo]]
	  Disadvantage: need record of the whole trajectory
	  ![image.png](../assets/image_1691874785935_0.png)
	- [[Actor-Critic Methods]]