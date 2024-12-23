- ![T-test: Definition, Formula, Types, Applications](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsNUHzZk2cpqSUeN1bngv2oc9u3c7u9PBitw&s){:height 322, :width 600}
- [[t-distribution]]
	- {{video https://youtu.be/UetYS3PaHIo?si=VrveawAeFXmRA36e}}
- Implementation of [[t-test]] for [[GLM]] :
	- most understandable and formal mathematical method to apply t-test for [[GLM]]
	  collapsed:: true
		- [[linear transformation theorem]]
			- ![image.png](../assets/image_1720545737580_0.png)
			- ![image.png](../assets/image_1720546207361_0.png)
		- derivation
			- ![image.png](../assets/image_1720547295899_0.png)
			- ![image.png](../assets/image_1720547378216_0.png)
			- ![image.png](../assets/image_1720595783253_0.png)
		- {{video https://youtu.be/ZVXZS5yKtUs?si=-EL0TStCOx9WF4RW}}
	- uses [[Sum of Square Error]] as noise
	  collapsed:: true
		- ![image.png](../assets/image_1718083227527_0.png)
		- {{video https://youtu.be/BjDRsCC-8p8?si=IBfvLsAGu9ZVFfMo&t=119}}
	- isolate time series data into blocks, and perform [[GLM]] on every block. Finally perform t-test using mean and standard deviation of obtained betas.
	  collapsed:: true
		- ![image.png](../assets/image_1718083276275_0.png)
		- {{video https://youtu.be/9VGX1ui4nFk?si=357XRVJcKF3aEhEX&t=900}}
	- Uses [[covariance matrix]] to calculate noise
	  collapsed:: true
		- ![image.png](../assets/image_1718083300213_0.png)
			- {{video https://youtu.be/NRunOo7EKD8?si=Z2tXAwVXK2-HU5JU&t=169}}
		- ![image.png](../assets/image_1718083344656_0.png)
			- {{video https://youtu.be/qnjiJ41cryQ?si=tOekyqOUwu_15Wcx&t=309}}