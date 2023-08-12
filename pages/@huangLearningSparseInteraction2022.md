tags:: [[Computer Science - Computer Vision and Pattern Recognition]], [[Computer Science - Robotics]], [[literature-review]]
date:: 4/2022
issn:: "2377-3766, 2377-3774"
series-text:: 无
issue:: 2
series-title:: 无
doi:: 10.1109/LRA.2021.3138547
title:: @huangLearningSparseInteraction2022
pages:: 1198-1205
volume:: 7
item-type:: [[journalArticle]]
access-date:: 2023-06-13T07:26:53Z
original-title:: Learning Sparse Interaction Graphs of Partially Detected Pedestrians for Trajectory Prediction
url:: http://arxiv.org/abs/2107.07056
publication-title:: IEEE Robotics and Automation Letters
journal-abbreviation:: IEEE Robot Autom Lett
authors:: [[Zhe Huang]], [[Ruohua Li]], [[Kazuki Shin]], [[Katherine Driggs-Campbell]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/library/items/Q7TH3GGY), [Web library](https://www.zotero.org/users/10791428/items/Q7TH3GGY)

- [[Abstract]]
	- Multi-pedestrian trajectory prediction is an indispensable element of autonomous systems that safely interact with crowds in unstructured environments. Many recent efforts in trajectory prediction algorithms have focused on understanding social norms behind pedestrian motions. Yet we observe these works usually hold two assumptions, which prevent them from being smoothly applied to robot applications: (1) positions of all pedestrians are consistently tracked, and (2) the target agent pays attention to all pedestrians in the scene. The first assumption leads to biased interaction modeling with incomplete pedestrian data. The second assumption introduces aggregation of redundant surrounding information, and the target agent may be affected by unimportant neighbors or present overly conservative motion. Thus, we propose Gumbel Social Transformer, in which an Edge Gumbel Selector samples a sparse interaction graph of partially detected pedestrians at each time step. A Node Transformer Encoder and a Masked LSTM encode pedestrian features with sampled sparse graphs to predict trajectories. We demonstrate that our model overcomes potential problems caused by the aforementioned assumptions, and our approach outperforms related works in trajectory prediction benchmarks. Code is available at \url{https://github.com/tedhuang96/gst}.
- [[Attachments]]
	- [Huang et al_2022_Learning Sparse Interaction Graphs of Partially Detected Pedestrians for.pdf](https://ieeexplore.ieee.org/stampPDF/getPDF.jsp?tp=&arnumber=9664278&ref=) {{zotero-imported-file TMZPVZVS, "Huang et al_2022_Learning Sparse Interaction Graphs of Partially Detected Pedestrians for.pdf"}}
	- [arXiv.org Snapshot](https://arxiv.org/abs/2107.07056) {{zotero-imported-file HEBU94IZ, "2107.html"}}
- [[Literature notes]]
  tags:: GNN, transformer, traj_pred
	- [[Gumbel Social Transformer]]
	  ((6491380c-b8ec-41a6-995a-cc79b2e15d5c))
	  tags:: method, fig
		- [[Edge Gumbal Selector]]
			- [[multi head attention]]
			  ((64913974-25fe-4614-9032-e239becf8680))
			- [[Gumbel Softmax]]
			  ((64913a15-8b9f-426a-b7e4-d6d1ac654fc9))
		- Node Transformer Encoder [[TGConv]]
		- [[Masked LSTM]]
		  id:: 64913b0a-84b9-45d1-87bb-d599997308ba
		  {{embed ((64913a75-b0ff-4e9d-9c46-8b132c233e52))}}
	- ((64913ae4-5ff6-49da-8cc5-dce9a0b0fd06))
	  tags:: gap, txt
	  id:: 64913a75-b0ff-4e9d-9c46-8b132c233e52