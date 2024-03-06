alias:: transformer

- [[attention]]
- [[self attention]]
- [[multi head attention]]
- https://machinelearningmastery.com/wp-content/uploads/2021/08/attention_research_1.png{:height 34, :width 713}
	- [[positional encoding]] is needed because [[Transformers]] doesn't capture positional relationship
	- [[transformer/encoder]]
		- One block of encoder
		  ![image.png](../assets/image_1696048773103_0.png)
		  Consist of one [[self attention]] layer and one dense layer
		  ![image.png](../assets/image_1696048796692_0.png)
	- [[transformer/decoder]]
		- One block of decoder
		  ![image.png](../assets/image_1696048622238_0.png)
		  Consists of one [[self attention]] layer, one [[attention]] layer, and one dense layer
		  ![image.png](../assets/image_1696048674865_0.png)
	- Overall
	  ![image.png](../assets/image_1696048855167_0.png)