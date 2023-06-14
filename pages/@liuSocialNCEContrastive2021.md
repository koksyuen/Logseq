tags:: [[open-source]], [[literature-review]]
date:: 2021
archive-location:: WOS:000798743205029
conference-name:: 2021 IEEE/CVF INTERNATIONAL CONFERENCE ON COMPUTER VISION (ICCV 2021)
proceedings-title:: Swiss Federal Institutes of Technology Domain
isbn:: 978-1-66542-812-5
doi:: 10.1109/ICCV48922.2021.01484
title:: @liuSocialNCEContrastive2021
pages:: 15098-15109
item-type:: [[conferencePaper]]
original-title:: Social NCE: Contrastive Learning of Socially-aware Motion Representations
language:: English
authors:: [[YJ Liu]], [[Q Yan]], [[A Alahi]], [[IEEE]]
links:: [Local library](zotero://select/library/items/37MHRC99), [Web library](https://www.zotero.org/users/10791428/items/37MHRC99)

- [[Abstract]]
	- Learning socially-aware motion representations is at the core of recent advances in multi-agent problems, such as human motion forecasting and robot navigation in crowds. Despite promising progress, existing representations learned with neural networks still struggle to generalize in closed-loop predictions (e.g., output colliding trajectories). This issue largely arises from the non-i.i.d. nature of sequential prediction in conjunction with ill-distributed training data. Intuitively, if the training data only comes from human behaviors in safe spaces, i.e., from "positive" examples, it is difficult for learning algorithms to capture the notion of "negative" examples like collisions. In this work, we aim to address this issue by explicitly modeling negative examples through self-supervision: (i) we introduce a social contrastive loss that regularizes the extracted motion representation by discerning the ground-truth positive events from synthetic negative ones; (ii) we construct informative negative samples based on our prior knowledge of rare but dangerous circumstances. Our method substantially reduces the collision rates of recent trajectory forecasting, behavioral cloning and reinforcement learning algorithms, outperforming state-of-the-art methods on several benchmarks. Our code is available at https: //github.com/vita-epfl/social- nce.
- [[Attachments]]
	- [Liu et al. - 2021 - Social NCE Contrastive Learning of Socially-aware.pdf](https://arxiv.org/pdf/2012.11717) {{zotero-imported-file 8PSID3US, "Liu et al. - 2021 - Social NCE Contrastive Learning of Socially-aware.pdf"}}