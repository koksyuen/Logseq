alias:: reinforce with baseline

- [[Policy Gradient]] with Baseline, $b$
  $b$ speed up the **convergence** of [[stochastic policy gradient]]
  ![image.png](../assets/image_1693841293401_0.png)
	- if $b = 0$, will be just standard [[Policy Gradient]]
	- if $b = V_{\pi}(s)$
	  ![image.png](../assets/image_1693841627763_0.png)
	  It is then called [[advantage function]]
	  ![image.png](../assets/image_1693852360663_0.png)
		- apply $b = V_{\pi}(s)$ to [[stochastic policy gradient]]
			- $Q_{\pi}(s_t, A_t)$ could be approximated from [[discounted return]] with aid of [[Monte Carlo]] 
			  id:: 64f60c4a-fd9a-4123-a838-7f2c2f114f66
			  ![image.png](../assets/image_1693846605463_0.png)
			- [[policy gradient ascent]] with [[baseline]]
			  ![image.png](../assets/image_1693846853752_0.png)
			- update [[value network]] with [[baseline]] in [[stochastic policy gradient]]
			  ![image.png](../assets/image_1693847019757_0.png)