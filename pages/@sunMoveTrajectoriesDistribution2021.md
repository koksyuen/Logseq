tags:: [[ROBOTS]], [[open-source]], [[reading]], [[literature-review]]
date:: 2021
archive-location:: WOS:000684604200053
conference-name:: ROBOTICS: SCIENCE AND SYSTEM XVII
proceedings-title:: Northwestern University
isbn:: 2330-7668
doi:: 10.48550/arxiv.2106.13667
title:: @sunMoveTrajectoriesDistribution2021
item-type:: [[conferencePaper]]
original-title:: Move Beyond Trajectories: Distribution Space Coupling for Crowd Navigation
language:: English
authors:: [[MC Sun]], [[F Baldini]], [[P Trautman]], [[T Murphey]]
links:: [Local library](zotero://select/library/items/P7FPWVAY), [Web library](https://www.zotero.org/users/10791428/items/P7FPWVAY)

- [[Abstract]]
	- Cooperatively avoiding collision is a critical functionality for robots navigating in dense human crowds, failure of which could lead to either overaggressive or overcautious behavior. A necessary condition for cooperative collision avoidance is to couple the prediction of the agents' trajectories with the planning of the robot's trajectory. However, it is unclear that trajectory based cooperative collision avoidance captures the correct agent attributes. In this work we migrate from trajectory based coupling to a formalism that couples agent preference distributions. In particular, we show that preference distributions (probability density functions representing agents' intentions) can capture higher order statistics of agent behaviors, such as willingness to cooperate. Thus, coupling in distribution space exploits more information about inter-agent cooperation than coupling in trajectory space. We thus introduce a general objective for coupled prediction and planning in distribution space, and propose an iterative best response optimization method based on variational analysis with guaranteed sufficient decrease. Based on this analysis, we develop a sampling-based motion planning framework called DistNav that runs in real time on a laptop CPU. We evaluate our approach on challenging scenarios from both real world datasets and simulation environments, and benchmark against a wide variety of model based and machine learning based approaches. The safety and efficiency statistics of our approach outperform all other models. Finally, we find that DistNav is competitive with human safety and efficiency performance.
- [[Attachments]]
	- [Sun et al. - 2021 - Move Beyond Trajectories Distribution Space Coupl.pdf](https://arxiv.org/pdf/2106.13667.pdf) {{zotero-imported-file ANVQ29RG, "Sun et al. - 2021 - Move Beyond Trajectories Distribution Space Coupl.pdf"}}
- [[Literature notes]]
  tags:: model-based, crowd-navi