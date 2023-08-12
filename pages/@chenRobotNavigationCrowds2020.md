tags:: [[Autonomous vehicle navigation]], [[MODEL]], [[deep learning in robotics and automation]], [[social human-robot interaction]], [[literature-review]]
date:: 2020 APR
issn:: 2377-3766
archive-location:: 计算机科学2区
series-text:: 无
issue:: 2
series-title:: 无
series:: EI
extra:: Citation Key: chenRobotNavigationCrowds2020
doi:: 10.1109/LRA.2020.2972868
title:: @chenRobotNavigationCrowds2020
pages:: 2754-2761
volume:: 5
item-type:: [[journalArticle]]
call-number:: 4.32
rights:: 5.010
original-title:: Robot Navigation in Crowds by Graph Convolutional Networks With Attention Learned From Human Gaze
language:: English
publication-title:: IEEE ROBOTICS AND AUTOMATION LETTERS
archive:: Q2
authors:: [[YY Chen]], [[CC Liu]], [[BE Shi]], [[M Liu]]
library-catalog:: 工程技术3区
links:: [Local library](zotero://select/library/items/UUXLUQPR), [Web library](https://www.zotero.org/users/10791428/items/UUXLUQPR)

- [[Abstract]]
	- Safe and efficient crowd navigation for mobile robot is a crucial yet challenging task. Previous work has shown the power of deep reinforcement learning frameworks to train efficient policies. However, their performance deteriorates when the crowd size grows. We suggest that this can be addressed by enabling the network to identify and pay attention to the humans in the crowd that are most critical to navigation. We propose a novel network utilizing a graph representation to learn the policy. We first train a graph convolutional network based on human gaze data that accurately predicts human attention to different agents in the crowd as they perform a navigation task based on a top down view of the environment. We incorporate the learned attention into a graph-based reinforcement learning architecture. The proposed attention mechanism enables the assignment of meaningful weightings to the neighbors of the robot, and has the additional benefit of interpretability. Experiments on real-world dense pedestrian datasets with various crowd sizes demonstrate that our model outperforms state-of-art methods, increasing task completion rate by 18.4% and decreasing navigation time by 16.4%.
- [[Attachments]]
	- [Chen et al. - 2020 - Robot Navigation in Crowds by Graph Convolutional .pdf](https://arxiv.org/pdf/1909.10400) {{zotero-imported-file SXDPCYBK, "Chen et al. - 2020 - Robot Navigation in Crowds by Graph Convolutional .pdf"}}
- [[Literature notes]]
  tags:: GNN, RL, crowd-navi
	- ((64914adb-01fc-4cae-8fc9-f3617effe588))
	  tags:: method, fig, main
		- attention network
		  ((64914b2d-bbc0-4a14-ab01-5030788228e4))
			- supervise learning
				- ground truth: operator gaze
				- estimation/output: adjacency matrix (attention to pedestrians)
	- ((64914c1b-1184-40ca-968c-174c5a789753))
	  [[co-exist]], but the methodology didn't make use of this statement
	  tags:: question, txt
	- ((64914cf4-114d-4dab-b9fe-3fad3542aaa6))
	  tags:: txt, simulation, experiment