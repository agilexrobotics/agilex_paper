# AToM-Bot: Embodied Fulfillment of Unspoken Human Needs with Affective Theory of Mind

![ubuntu](https://img.shields.io/badge/Device-Cobot%20S-blue.svg) | ![CobotMagic](https://img.shields.io/badge/Embodied%20Intelligence-orange.svg) ![AToM](https://img.shields.io/badge/VLM-orange.svg)![AToM](https://img.shields.io/badge/AToM-orange.svg)



[![arXiv](https://img.shields.io/badge/arXiv-181717?logo=arXiv&logoColor=white)](https://arxiv.org/abs/2406.08455) : https://arxiv.org/abs/2406.08455

[![Project Page](https://img.shields.io/badge/Project_Page-181717?logo=GitHub&logoColor=white)](https://affective-tom-bot.github.io/) : https://affective-tom-bot.github.io/


![](./assets/0.mp4)
<video>   
  <source src="assets\0.mp4" type="video/mp4">
</video>

## Abstract

We propose **AToM-Bot**, a novel task generation and execution framework for proactive robot-human interaction, which leverages the human mental and physical state inference capabilities of the Vision Language Model (VLM) prompted by the Affective Theory of Mind (AToM). Without requiring explicit commands by humans, AToM-Bot proactively generates and follows feasible tasks to improve general human well-being. When around humans, AToM-Bot first detects current human needs based on inferred human states and observations of the surrounding environment. It then generates tasks to fulfill these needs, taking into account its embodied constraints. We designed 16 daily life scenarios spanning 4 common scenes and tasked the same visual stimulus to 59 human subjects and our robot. We used the similarity between human open-ended answers and robot output, and the human satisfaction scores to metric robot performance. AToM-Bot received high human evaluations in need detection (6.42/7, 91.7%), embodied solution (6.15/7, 87.8%) and task execution (6.17/7, 88.1%). We show that AToM-Bot excels in generating and executing feasible plans to fulfill unspoken human needs.

## AToM-Bot

![](assets\fig2.png)

Overview of AToM-Bot, a robotic system for identifying and responding to human needs. It integrates human observations and environmental attributes to infer human needs. It then generates tasks for a robot by navigating to objects, manipulating them, and assisting human in daily setting. Due to the requirements of blind peer review, the individuals in the images were anonymized.

![](assets\fig1.png)

Website template borrowed from [NeRFies](https://github.com/nerfies/nerfies.github.io) and [VoxPoser](https://voxposer.github.io/).
