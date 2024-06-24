alias:: R square, R^2, R2

- Calculate how much **reduction in variation** after taking the parameters into account.
- denotes goodness of fit
	- thus greater is better
- Procedure:
	- Calculate variance with respect to mean
	  ![image.png](../assets/image_1710214683572_0.png)
	- Calculate variance with respect to fit
	  ![image.png](../assets/image_1710214828647_0.png)
	- ![image.png](../assets/image_1710214935268_0.png)
	- ![image.png](../assets/image_1710252013235_0.png)
	  Also can be 
	  $R^2=\frac{SS(mean)-SS(fit)}{SS(mean)}$
- $R^2$ must be scaled by number of parameters
	- because
		- ![image.png](../assets/image_1710252859404_0.png)
		- the more parameters we add to equation, the more opportunities we have for random events to reduce $SS(fit)$ and improve $R^2$