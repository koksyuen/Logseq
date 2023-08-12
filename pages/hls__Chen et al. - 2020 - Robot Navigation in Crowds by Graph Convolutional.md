file:: [Chen et al. - 2020 - Robot Navigation in Crowds by Graph Convolutional .pdf](file:///home/koksyuen/Zotero/storage/SXDPCYBK/Chen et al. - 2020 - Robot Navigation in Crowds by Graph Convolutional .pdf)
file-path:: file:///home/koksyuen/Zotero/storage/SXDPCYBK/Chen et al. - 2020 - Robot Navigation in Crowds by Graph Convolutional .pdf

- [:span]
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 64914adb-01fc-4cae-8fc9-f3617effe588
  hl-type:: area
  hl-stamp:: 1687243481117
- The attention network G was learned with supervision. The ground truth was generated from human gaze data. Gaze data collected while subjects attempted to navigate through the crowd to the goal using a joystick, while viewing the scene from overhead. We reproduced the scene in the real world crowd dataset [30]. For training, we used the stateattention weight pairs collected in Students001 environment. We collected gaze data for multiple starts with varying crowd sizes and densities, resulting in around 1700 state and attention pairs. To generate the ground truth attention weights, we first created a Gaussian mixture density over space by placing a Gaussian with standard deviation equals to two degree of visual angle at each gaze point in a temporal window from -0.1 to +0.1 seconds around the current time point. We assigned attention weights to each node by sampling from the density according to the node location, and normalized so that the attention weights summed to one. We used the L1 loss function and trained the network for 400 epochs until convergence.
  ls-type:: annotation
  hl-page:: 5
  hl-color:: yellow
  id:: 64914b2d-bbc0-4a14-ab01-5030788228e4
- key solution is to consider the impact of the motion of the robot on the crowds
  ls-type:: annotation
  hl-page:: 1
  hl-color:: red
  id:: 64914c1b-1184-40ca-968c-174c5a789753
- simulation environment from the augmented crowd dataset Students001
  ls-type:: annotation
  hl-page:: 4
  hl-color:: yellow
  id:: 64914cf4-114d-4dab-b9fe-3fad3542aaa6