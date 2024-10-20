# Mobile ALOHA

## Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation

![ubuntu](https://img.shields.io/badge/Device-Cobot%20Magic-blue.svg)  ![ubuntu](https://img.shields.io/badge/Device-Tracer-blue.svg)| ![CobotMagic](https://img.shields.io/badge/Embodied%20Intelligence-orange.svg) ![AToM](https://img.shields.io/badge/ACT-orange.svg)



[![arXiv](https://img.shields.io/badge/arXiv-181717?logo=arXiv&logoColor=white)](https://arxiv.org/abs/2401.02117) : https://arxiv.org/abs/2401.02117

[![Project Page](https://img.shields.io/badge/Project_Page-181717?logo=GitHub&logoColor=white)](https://affective-tom-bot.github.io/) : https://mobile-aloha.github.io/

[Zipeng Fu](https://zipengfu.github.io/)*  [Tony Z. Zhao](https://tonyzhaozh.github.io/)*  [Chelsea Finn](https://ai.stanford.edu/~cbfinn/)

![img](https://mobile-aloha.github.io/static/images/logo.jpg)

 [arXiv](http://arxiv.org/abs/2401.02117) |[Tutorial](https://docs.google.com/document/d/1_3yhWjodSNNYlpxkRCPIlvIAaQ76Nqk2wsqhnEVM6Dc) | [Datasets](https://drive.google.com/drive/folders/1FP5eakcxQrsHyiWBRDsMRvUfSxeykiDc) | [Hardware Code](https://github.com/MarkFzp/mobile-aloha) | [ML Code](https://github.com/MarkFzp/act-plus-plus) |[中文](https://mobile-aloha.github.io/cn.html)



<video download="" controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/mobile-aloha.mp4"style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 8.875px;"></video>

## Team

## Abstract

Imitation learning from human demonstrations has shown impressive performance in robotics. However, most results focus on table-top manipulation, lacking the mobility and dexterity necessary for generally useful tasks. In this work, we develop a system for imitating mobile manipulation tasks that are bimanual and require whole-body control. We first present Mobile ALOHA, a low-cost and whole-body teleoperation system for data collection. It augments the ALOHA system with a mobile base, and a whole-body teleoperation interface. Using data collected with Mobile ALOHA, we then perform supervised behavior cloning and find that co-training with existing static ALOHA datasets boosts performance on mobile manipulation tasks. With 50 demonstrations for each task, co-training can increase success rates by up to 90%, allowing Mobile ALOHA to autonomously complete complex mobile manipulation tasks such as sauteing and serving a piece of shrimp, opening a two-door wall cabinet to store heavy cooking pots, calling and entering an elevator, and lightly rinsing a used pan using a kitchen faucet.

## Autonomous Skills

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/cook_shrimp.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/wipe_wine.mp4"  style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/take_elevator.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/use_cabinets.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/wash_pan.mp4"  style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/push_chairs.mp4"  style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/high_five_third_person.mp4" pstyle="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/skills/high_five_moving_cam.mp4"style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

## Teleoperation

<iframe src="https://www.youtube.com/embed/mnLVbwxSdNM" title="Mobile ALOHA Robot - Cooking a 3-Course Cantonese Meal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" style="box-sizing: inherit; margin: 0px; padding: 0px; border: 0px; top: 0px; left: 0px; width: 753.75px; height: 422.3px;"></iframe>

<iframe src="https://www.youtube.com/embed/HaaZ8ss-HP4" title="Mobile ALOHA: Your Housekeeping Robot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" style="box-sizing: inherit; margin: 0px; padding: 0px; border: 0px; top: 0px; left: 0px; width: 753.75px; height: 422.3px;"></iframe>

## Robustness and Repeatability

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/wipe_wine_9_trials_8x_speed.mp4"  style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/take_elevator_5_trials_8x_speed.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/use_cabinets_3_pots_8x_speed.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/use_cabinets_distractors.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/push_chairs_morning_7_trials_8x_speed.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

<video controls="" autoplay="" loop="" muted="" playsinline="" src="./assets/resources/robustness/push_chairs_night_6_trials_8x_speed.mp4" style="box-sizing: inherit; height: auto; max-width: 100%; border: 1px solid rgb(187, 187, 187); border-radius: 10px; margin: 5.225px;"></video>

## Failures

We share some funny robot failures along our journey of hardware and software/AI co-development.

<iframe src="https://www.youtube.com/embed/xGNNW6smDPQ" title="Mobile ALOHA funny failures" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" style="box-sizing: inherit; margin: 0px; padding: 0px; border: 0px; top: 0px; left: 0px; width: 753.75px; height: 422.3px;"></iframe>

## Acknowledgements

We thank the Stanford Robotics Center and Steve Cousins for providing facility support for our experiments. We also thank members of Stanford IRIS Lab: Lucy X. Shi and Tian Gao, and members of Stanford REAL Lab: Cheng Chi, Zhenjia Xu, Yihuai Gao, Huy Ha, Zeyi Liu, Xiaomeng Xu, Chuer Pan and Shuran Song, for providing extensive helps for our experiments. We appreciate much photographing by Qingqing Zhao, and feedbacks from and helpful discussions with Karl Pertsch, Boyuan Chen, Ziwen Zhuang, Quan Vuong and Fei Xia. This project is supported by the Boston Dynamics AI Institute and ONR grant N00014-21-1-2685. Zipeng Fu is supported by Stanford Graduate Fellowship.

## BibTeX

```
@inproceedings{fu2024mobile,
  author    = {Fu, Zipeng and Zhao, Tony Z. and Finn, Chelsea},
  title     = {Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation},
  booktitle = {{Conference on Robot Learning (CoRL)}},
  year      = {2024},
}
```

Page template borrowed from [Nerfies](https://nerfies.github.io/) and [Robot-Parkour](https://robot-parkour.github.io/).
