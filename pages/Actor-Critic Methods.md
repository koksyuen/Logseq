alias:: actor-critic

- ![image.png](../assets/image_1691958247493_0.png)
- **Framework**
  ![image.png](../assets/image_1691960401153_0.png)
	- To obtain better performance, step 9 could be changed to:
	  $$\mathbf{\theta}_{t+1} = \mathbf{\theta}_t + \beta\cdot \delta_t \cdot \mathbf{d}_{\theta, t} $$
	  this method is called [[reinforce with baseline]]
- **Main objective** is similar to [[Policy Gradient]]:
  maximise $E_s[V_\pi(s)]$  
  ![image.png](../assets/image_1691958505043_0.png) 
  [[state-value function]] can be approximated using neural network, $\theta$ and $\mathbf{w}$
	- [[policy network]] [[actor]]
	  ![image.png](../assets/image_1691958662070_0.png)
		- update [[policy network]], $\pi(a|s;\mathbf{\theta})$ to increase the [[state value function]], $V(s; \mathbf{\theta}, \mathbf{w})$:
		  ![image.png](../assets/image_1691959671612_0.png)
			- so that [[actor]] gradually performs better
			- supervision is purely from the [[value network]] ([[critic]])
			- update [[policy network]], $\pi$ using [[Policy Gradient]]
			  ![image.png](../assets/image_1691959331902_0.png)
			- update [[policy network]] , $\pi$ using [[stochastic policy gradient]]
			  ![image.png](../assets/image_1691959592208_0.png)
	- [[value network]] [[critic]]
	  ![image.png](../assets/image_1691958723787_0.png)
		- update value network, $q(s,a; \mathbf{w})$ to better estimate the [[return]] 
		  ![image.png](../assets/image_1691959773657_0.png)
			- so that [[critic]]'s judgement becomes more accurate
			- supervision is purely from the [[rewards]]
			- update [[value network]], $q$ using [[TD]]
			  ![image.png](../assets/image_1691958957304_0.png)