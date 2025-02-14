collapsed:: true

	- Notation
	  ![image.png](../assets/image_1691822540004_0.png)
	- [[Probability Distribution Function]] 
	  ![image.png](../assets/image_1691823781424_0.png)
	- [[Expectation]]
	  ![image.png](../assets/image_1691823893269_0.png)
- [[return]] : cummulative future reward
  ![image.png](../assets/image_1691825289676_0.png)
  [[discounted return]]: cummulative discounted future reward
  ![image.png](../assets/image_1691878299678_0.png)
	- [[return]] depends on 2 kind of randomness:
		- [[policy function]]
		  ![image.png](../assets/image_1691824420623_0.png)
		- [[state transition]]
		  ![image.png](../assets/image_1691824508353_0.png)
- [[random sampling]]
  **~** means **sampling from** a [[PDF]]
  **.** denotes variable that was sampled
  ![image.png](../assets/image_1691820728529_0.png){:height 76, :width 697}
- [[value function]], $V(s)$
	- [[action value function]], $Q_{\pi}(s_t, a_t)$
	  ![image.png](../assets/image_1691878745710_0.png)
	  ![image.png](../assets/image_1691878843984_0.png){:height 104, :width 743}
		- [[optimal action-value function]]
		  ![image.png](../assets/image_1691879680533_0.png)
	- [[state value function]], $V_{\pi} (s_t)$
	  ![image.png](../assets/image_1691878944537_0.png)$
	  E_A$: expectation w.r.t action $a_t \sim \pi(.|s_t)$
	  ![image.png](../assets/image_1691879061647_0.png)
		- assets:///home/koksyuen/Logseq/assets/image_1691878944537_0.png
- [[mdp]]
  ![image.png](../assets/image_1693860276323_0.png)
- [[pomdp]]
  ![image.png](../assets/image_1693860313799_0.png)