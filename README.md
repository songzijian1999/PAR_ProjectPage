<!-- [![Website Badge](https://raw.githubusercontent.com/referit3d/referit3d/eccv/images/project_website_badge.svg)]() -->
[![arXiv](https://img.shields.io/badge/arXiv-2508.09822-b31b1b.svg?style=plastic)]()
# Physical Autoregressive Model for Robotic Manipulation without Action Pretraining
This is the official PyTorch implementation of **Physical Autoregressive Model for Robotic Manipulation without Action Pretraining**


[📘paper](https://arxiv.org/abs/2508.09822) |


## Abstract
The scarcity of manipulation data has motivated the use of pretrained large models from other modalities in robotics. In this work, we build upon autoregressive video generation models to propose a Physical Autoregressive Model (PAR), where physical tokens combine frames and actions to represent the joint evolution of the robot and its environment. PAR leverages the world knowledge embedded in video pretraining to understand physical dynamics without requiring action pretraining, enabling accurate video prediction and consistent action trajectories. It also adopts a DiT-based de-tokenizer to model frames and actions as continuous tokens, mitigating quantization errors and facilitating mutual enhancement. Furthermore, we incorporate a causal mask with inverse kinematics, parallel training, and the KV-cache mechanism to further improve performance and efficiency. Experiments on the ManiSkill benchmark show that PAR achieves a 100% success rate on the PushCube task, matches the performance of action-pretrained baselines on other tasks, and accurately predicts future videos with tightly aligned action trajectories. These findings underscore a promising direction for robotic manipulation by transferring world knowledge from autoregressive video pretraining.

---

<p align="center">
  <img src="static/images/phytransformers.svg" alt="示例图片（请替换为你的图片链接）" width="800">
</p>

<p align="center">
  <em>Fig 1: The illustration of Physical Autoregressive Model.</em>
</p>



## Detailed code coming soon