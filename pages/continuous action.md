- ![image.png](../assets/image_1693854589736_0.png)
- ![image.png](../assets/image_1693854519090_0.png)
	- Thus, use **neural networks** to approximate the functions
	  ![image.png](../assets/image_1693854644923_0.png)
	- Hence, action sampling can be done by
	  ![image.png](../assets/image_1693854754007_0.png)
- **Training**
	- to compute the derivative, [[auxiliary network]] is needed
	  ![image.png](../assets/image_1693855590062_0.png)
	  where $\mathbf{\theta} = (\mathbf{\theta}^{\mu}, \mathbf{\theta}^\rho)$
		- where [[auxiliary network]] is the natural log of policy network (needed for derivative / backpropagation)
		  ![image.png](../assets/image_1693855687350_0.png)
		- [[auxiliary network]] is **only** needed for training (computes derivative for backpropagation)
	- As the result, [[Policy Gradient]] for [[continuous action]]
		- would have only one difference from [[Policy Gradient]]
		  ![image.png](../assets/image_1693856403679_0.png)
		  since ![image.png](../assets/image_1693856453828_0.png)