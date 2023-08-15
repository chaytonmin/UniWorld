# UniWorld: Autonomous Driving Pre-training via World Models 

> [Paper in arXiv](https://arxiv.org/abs/2308.07234) 

# Abstract
In this paper, we draw inspiration from Alberto Elfes' pioneering work in 1989, where he introduced the concept of the occupancy grid as World Models for robots~\cite{occupancy}. We imbue the robot with a spatial-temporal world model, termed UniWorld, to perceive its surroundings and predict the future behavior of other participants. UniWorld involves initially predicting 4D geometric occupancy as the World Models for foundational stage and subsequently fine-tuning on downstream tasks. UniWorld can estimate missing information concerning the world state and predict plausible future states of the world. Besides, UniWorld's pre-training process is label-free, enabling the utilization of massive amounts of image-LiDAR pairs to build a Foundational Model. 

# Bibtex
If this work is helpful for your research, please consider citing the following BibTeX entry.

```
@article{UniWorld,
  title={UniWorld: Autonomous Driving Pre-training via World Models },
  author={Chen Min, Dawei Zhao, Liang Xiao, Yiming Nie, and Bin Dai}
  journal={arXiv preprint},
  year={2023}
}
```
```
@article{occ-bev,
  title={Occ-BEV: Multi-Camera Unified Pre-training via 3D Scene Reconstruction},
  author={Chen Min, Dawei Zhao, Liang Xiao, Yiming Nie, and Bin Dai}
  journal={arXiv preprint},
  year={2023}
}
```
