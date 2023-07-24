---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)] | [[DBLP](https://dblp.org/pid/19/2969-1.html)] | [[View by topic](https://jd92.wang/research/)]

#### Preprints


- A Survey on Evaluation of Large Language Models. Yupeng Chang, Xu Wang, Jindong Wang, Yuan Wu, Kaijie Zhu, Hao Chen, Linyi Yang, Xiaoyuan Yi, Cunxiang Wang, Yidong Wang, Wei Ye, Yue Zhang, Yi Chang, Philip S. Yu, Qiang Yang, Xing Xie. [[arxiv](https://arxiv.org/abs/2307.03109)] [[code](https://github.com/MLGroupJLU/LLM-eval-survey)]
- PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts. Kaijie Zhu, Jindong Wang, Jiaheng Zhou, Zichen Wang, Hao Chen, Yidong Wang, Linyi Yang, Wei Ye, Neil Zhenqiang Gong, Yue Zhang, Xing Xie. [[arxiv](https://arxiv.org/abs/2306.04528)] [[code](https://github.com/microsoft/promptbench)]
- PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization. Yidong Wang, Zhuohao Yu, Zhengran Zeng, Linyi Yang, Cunxiang Wang, Hao Chen, Chaoya Jiang, Rui Xie, Jindong Wang, Xing Xie, Wei Ye, Shikun Zhang, Yue Zhang. [[arxiv](https://arxiv.org/abs/2306.05087)] [[code](https://github.com/WeOpenML/PandaLM)]
- Selective Mixup Helps with Distribution Shifts, But Not (Only) because of Mixup. Damien Teney, Jindong Wang, Ehsan Abbasnejad. [[arxiv](https://arxiv.org/abs/2305.16817)]
- Imprecise Label Learning: A Unified Framework for Learning with Various Imprecise Label Configurations. Hao Chen, Ankit Shah, Jindong Wang, Ran Tao, Yidong Wang, Xing Xie, Masashi Sugiyama, Rita Singh, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2305.12715)]
- Exploring Vision-Language Models for Imbalanced Learning. Yidong Wang, Zhuohao Yu, **Jindong Wang**, Qiang Heng, Hao Chen, Wei Ye, Rui Xie, Xing Xie, Shikun Zhang. [[arxiv](https://arxiv.org/abs/2304.01457)] [[code](https://github.com/Imbalance-VLM/Imbalance-VLM)]
- An Embarrassingly Simple Baseline for Imbalanced Semi-Supervised Learning. Hao Chen, Yue Fan, Yidong Wang, **Jindong Wang**, Bernt Schiele, Xing Xie, Marios Savvides, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2211.11086)] 
- FIXED: Frustratingly Easy Domain Generalization with Mixup. Wang Lu, **Jindong Wang**, Han Yu, Lei Huang, Xiang Zhang, Yiqiang Chen, Xing Xie. [[arxiv](https://arxiv.org/abs/2211.05228)]
- Conv-Adapter: Exploring Parameter Efficient Transfer Learning for ConvNets. Hao Chen, Ran Tao, Han Zhang, Yidong Wang, Wei Ye, Jindong Wang, Guosheng Hu, and Marios Savvides. [[arxiv](https://arxiv.org/abs/2208.07463)]
- Equivariant Disentangled Transformation for Domain Generalization under Combination Shift. Yivan Zhang, **Jindong Wang**, Xing Xie, and Masashi Sugiyama. [[arxiv](https://arxiv.org/abs/2208.02011)]
- Boosting Cross-Domain Speech Recognition with Self-Supervision. Han Zhu, Gaofeng Cheng, **Jindong Wang**, Wenxin Hou, Pengyuan Zhang, and Yonghong Yan. [[arxiv](https://arxiv.org/abs/2206.09783)]
- Learning Invariant Representations across Domains and Tasks. **Jindong Wang**, Wenjie Feng, Chang Liu, Chaohui Yu, Mingxuan Du, Renjun Xu, Tao Qin, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2103.05114)]
- Learning to match distributions for domain adaptation. Chaohui Yu, **Jindong Wang**, Chang Liu, Tao Qin, Renjun Xu, Wenjie Feng, Yiqiang Chen, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2007.10791)]

#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
