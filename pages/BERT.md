alias:: bidirectional encoder representations from transformers

- Pretrain the [[transformer/encoder]]
	- [[BERT]] doesn't need manually label data
	  ![image.png](../assets/image_1696050664811_0.png){:height 138, :width 501}
	  ![image.png](../assets/image_1696050705043_0.png)
		- **Randomly mask a word**
		  ![image.png](../assets/image_1696049813876_0.png)
		  ![image.png](../assets/image_1696049833509_0.png)
		- **Predict the next sentence**
			- dataset
				- True sample
				  ![image.png](../assets/image_1696050243142_0.png)
				- False sample
				  ![image.png](../assets/image_1696050265182_0.png)
				  the next sentence is randomly sampled from the dataset
			- training
			  ![image.png](../assets/image_1696050204866_0.png)