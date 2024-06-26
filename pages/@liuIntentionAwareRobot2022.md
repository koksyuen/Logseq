filters:: {"tue, 30.05.2023" true}
tags:: [[open-source]], [[read]], [[literature-review]]
date:: [[Mar 3rd, 2022]]
series-text:: 无
series-title:: 无
doi:: 10.48550/arXiv.2203.01821
title:: @liuIntentionAwareRobot2022
item-type:: [[journalArticle]]
access-date:: 2023-03-07T07:35:21Z
original-title:: Intention Aware Robot Crowd Navigation with Attention-Based Interaction Graph
language:: en
url:: https://arxiv.org/abs/2203.01821v2
authors:: [[Shuijing Liu]], [[Peixin Chang]], [[Zhe Huang]], [[Neeloy Chakraborty]], [[Kaiwen Hong]], [[Weihang Liang]], [[D. Livingston McPherson]], [[Junyi Geng]], [[Katherine Driggs-Campbell]]
library-catalog:: arxiv.org
links:: [Local library](zotero://select/library/items/DN3AZXJV), [Web library](https://www.zotero.org/users/10791428/items/DN3AZXJV)

- [[Abstract]]
  collapsed:: true
	- We study the problem of safe and intention-aware robot navigation in dense and interactive crowds. Most previous reinforcement learning (RL) based methods fail to consider different types of interactions among all agents or ignore the intentions of people, which results in performance degradation. In this paper, we propose a novel recurrent graph neural network with attention mechanisms to capture heterogeneous interactions among agents through space and time. To encourage longsighted robot behaviors, we infer the intentions of dynamic agents by predicting their future trajectories for several timesteps. The predictions are incorporated into a model-free RL framework to prevent the robot from intruding into the intended paths of other agents. We demonstrate that our method enables the robot to achieve good navigation performance and non-invasiveness in challenging crowd navigation scenarios. We successfully transfer the policy learned in simulation to a real-world TurtleBot 2i.
- [[Attachments]]
	- [Liu et al. - 2022 - Intention Aware Robot Crowd Navigation with Attent.pdf](https://arxiv.org/pdf/2203.01821) {{zotero-imported-file R45EZDNE, "Liu et al. - 2022 - Intention Aware Robot Crowd Navigation with Attent.pdf"}}
- [[Literature notes]]
  tags:: GNN, RL, crowd-navigation
	- ((64914887-9da9-4400-ba48-7aba00ee5f6f))
	  tags:: fig, method, main
		- Trajectory Predictor: [[GST]]
	- ((647672a0-1548-4c82-b74d-40b0b2e1d83a))
	  tags:: method, equa, reward
	- ((6477d698-2355-4661-98d4-dedce27954d2))
	  #+BEGIN_EXPORT latex
	  2(-d^t_{goal} + d^{t-1}_{goal})
	  #+END_EXPORT 
	  tags:: method, equa, reward