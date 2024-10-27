# Mobile ALOHA

## Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation

![ubuntu](https://img.shields.io/badge/Device-Cobot%20Magic-blue.svg)  ![ubuntu](https://img.shields.io/badge/Device-Tracer-blue.svg)| ![CobotMagic](https://img.shields.io/badge/Embodied%20Intelligence-orange.svg) ![AToM](https://img.shields.io/badge/ACT-orange.svg)



[![arXiv](https://img.shields.io/badge/arXiv-181717?logo=arXiv&logoColor=white)](https://arxiv.org/abs/2401.02117) : https://arxiv.org/abs/2401.02117

[![Project Page](https://img.shields.io/badge/Project_Page-181717?logo=GitHub&logoColor=white)](https://affective-tom-bot.github.io/) : https://mobile-aloha.github.io/

[Zipeng Fu](https://zipengfu.github.io/)*  [Tony Z. Zhao](https://tonyzhaozh.github.io/)*  [Chelsea Finn](https://ai.stanford.edu/~cbfinn/)

![img](https://mobile-aloha.github.io/static/images/logo.jpg)

 [arXiv](http://arxiv.org/abs/2401.02117) |[Tutorial](https://docs.google.com/document/d/1_3yhWjodSNNYlpxkRCPIlvIAaQ76Nqk2wsqhnEVM6Dc) | [Datasets](https://drive.google.com/drive/folders/1FP5eakcxQrsHyiWBRDsMRvUfSxeykiDc) | [Hardware Code](https://github.com/MarkFzp/mobile-aloha) | [ML Code](https://github.com/MarkFzp/act-plus-plus) |[中文](https://mobile-aloha.github.io/cn.html)


## Abstract

Imitation learning from human demonstrations has shown impressive performance in robotics. However, most results focus on table-top manipulation, lacking the mobility and dexterity necessary for generally useful tasks. In this work, we develop a system for imitating mobile manipulation tasks that are bimanual and require whole-body control. We first present Mobile ALOHA, a low-cost and whole-body teleoperation system for data collection. It augments the ALOHA system with a mobile base, and a whole-body teleoperation interface. Using data collected with Mobile ALOHA, we then perform supervised behavior cloning and find that co-training with existing static ALOHA datasets boosts performance on mobile manipulation tasks. With 50 demonstrations for each task, co-training can increase success rates by up to 90%, allowing Mobile ALOHA to autonomously complete complex mobile manipulation tasks such as sauteing and serving a piece of shrimp, opening a two-door wall cabinet to store heavy cooking pots, calling and entering an elevator, and lightly rinsing a used pan using a kitchen faucet.



