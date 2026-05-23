---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm Chunyu Xue (薛春宇), a fourth-year PhD student in [Emerging Parallel Computing Center (EPCC)](http://epcc.sjtu.edu.cn) from [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn), advised by [Prof. Quan Chen](https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html). My research interests lie in building efficient and scalable systems for LLM and MultiModal pretraining, supervised fine-tuning, post-training, and cluster-level scheduling. 
Currently, I'm working as a research intern in [Moonshot AI (Kimi)](https://www.moonshot.ai) (RL Infrastructure). I had a wonderful experience when working as a research intern in [ByteDance Seed](https://seed.bytedance.com/en/) (Training Infrastructure). I worked as an engineering intern in [Microsoft Cloud+AI](https://www.microsoft.com/en-us/aprd/aboutus/team-cai). I received my B.S. in Computer Science and Technology from SJTU.
Feel free to reach out if you are interested in potential collaboration!

# 🔥 News

- *2026.05*, Glad to join Moonshot (Kimi) RL Infra team as a research intern 🥳, solving ambitious moonshot problems together that will lead humanity to AGI! Had a wonderful experience in Seed team~
- *2026.05*, Give a talk at NSDI'26, Renton, WA USA.
- *2026.04*, Give two talks at EuroSys'26, Edinburgh, Scoland UK.
- *2026.01*, Three papers ([Arena](https://dl.acm.org/doi/10.1145/3767295.3803571), [MegaScale-Omni](https://dl.acm.org/doi/10.1145/3767295.3803587), and [Suika](https://dl.acm.org/doi/10.1145/3767295.3803623)) are accepted by EuroSys'26!
- *2025.12*, [MuxTune](https://www.usenix.org/conference/nsdi26/presentation/xue-chunyu) is accepted by NSDI'26!
- *2025.10*, Serve as a reviewer for Concurrency and Computation: Practice and Experience.
- *2025.03*, Glad to join ByteDance Seed Training Infra team as a research intern 🥳, pushing the boundaries of AI together!

<span class='anchor' id='-education'></span>

# 🎓 Education

 - *2022.09 - Now*, Shanghai Jiao Tong University `Ph.D. in Computer Science`
 - *2018.09 - 2022.06*, Shanghai Jiao Tong University `B.S. in Computer Science (Zhiyuan Honors Program)`

<span class='anchor' id='-experiences'></span>

# 💼 Experiences

 - *2026.05 - Now*, Moonshot AI (Kimi) (RL Infrastructure) `Research Intern`
 - *2025.03 - 2026.05*, ByteDance Seed (Training Infrastructure) `Research Intern`
 - *2021.06 - 2021.09*, Microsoft (Cloud+AI) `Software Engineer Intern`

<span class='anchor' id='-publications'></span>

# 📖 Publications 

## Published

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">EuroSys 2026</span> **#Chunyu Xue**, Weihao Cui, Quan Chen, Chen Chen, Han Zhao, Shulai Zhang, Linmei Wang, Yan Li, Limin Xiao, Weifeng Zhang, Jing Yang, Bingsheng He, Minyi Guo. "Arena: Efficiently Training Large Models via Dynamic Scheduling and Adaptive Parallelism Co-Design". *21st ACM European Conference on Computer Systems*, Eurosys'26 (CCF-A). [[Paper]](https://dl.acm.org/doi/10.1145/3767295.3803571) [[Arxiv]](https://arxiv.org/abs/2403.16125) [[Code]](https://github.com/sjtu-epcc/arena)

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">EuroSys 2026</span> **#Chunyu Xue**, Yangrui Chen, Jianyu Jiang, Ningxin Zheng, Junda Feng, Jingji Chen, Shixiong Zhao, Shen Yan, Yi Lin, Lei Shi, Zanbo Wang, Lishu Luo, Faming Wu, Haibin Lin, Yanghua Peng, Xin Liu, Quan Chen. "MegaScale-Omni: A Hyper-Scale, Workload-Resilient System for MultiModal LLM Training in Production". *21st ACM European Conference on Computer Systems*, Eurosys'26 (CCF-A). [[Paper]](https://dl.acm.org/doi/10.1145/3767295.3803587)

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">NSDI 2026</span> **#Chunyu Xue**, Yi Pan, Weihao Cui, Quan Chen, Shulai Zhang, Bingsheng He, Minyi Guo. "MuxTune: Efficient Multi-Task LLM Fine-Tuning in Multi-Tenant Datacenters via Spatial-Temporal Backbone Multiplexing". *23rd USENIX Symposium on Networked Systems Design and Implementation*, NSDI'26 (CCF-A). [[Paper]](https://www.usenix.org/conference/nsdi26/presentation/xue-chunyu) [[Arxiv]](https://arxiv.org/abs/2603.02885) [[Code]](https://github.com/sjtu-epcc/muxtune)

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">EuroSys 2026</span> Yuxuan Wang, Yanbo Wang, Chen Chen, **#Chunyu Xue**, Qizhen Weng, Yin Chen, Zeren Li, Xuqi Zhu, Yongqiang Yang, Quan Chen, Minyi Guo. "Suika: Efficient and High-quality Re-scheduling of 3D-parallelized LLM Training Jobs in Shared Clusters". *21st ACM European Conference on Computer Systems*, Eurosys'26 (CCF-A). [[Paper]](https://dl.acm.org/doi/10.1145/3767295.3803623)

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">EuroSys 2025</span> Shulai Zhang, Quan Chen, Weihao Cui, Han Zhao, **#Chunyu Xue**, Zhen Zheng, Wei Lin, Minyi Guo. "Improving GPU Sharing Performance through Adaptive Bubbleless Spatial-Temporal Sharing". *20th ACM European Conference on Computer Systems*, Eurosys'25 (CCF-A). [[Paper]](https://dl.acm.org/doi/abs/10.1145/3689031.3696070)

 - <span style="background-color: #B16A6F; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">TACO 2025</span> Pengyu Yang, Weihao Cui, **#Chunyu Xue**, Han Zhao, Chen Chen, Quan Chen, Jing Yang, Minyi Guo. "Taming Flexible Job Packing in Deep Learning Training Clusters". *ACM Transactions on Architecture and Code Optimization*, TACO'25 (CCF-A). [[Paper]](https://dl.acm.org/doi/10.1145/3711927)

## Preprint

  - <span style="background-color: #A4D0C1; color: white; padding: 2px 6px; border-radius: 3px; font-weight: bold; font-size: 0.9em;">WIP</span> Yanbo Wang, Yuxuan Wang, Chen Chen, **#Chunyu Xue**, Yu Feng, Anbang Wu, Quan Chen, Yin Chen, Qizhen Weng. "Mosaic: Towards Efficient Training of Multimodal Models with Spatial Resource Multiplexing". *Work in progress*. [[Arxiv]](https://arxiv.org/abs/2605.18710v1)

<span class='anchor' id='-projects'></span>

# 🔨 Projects

 - *2026.03 - 2026.05*, ViT-USM Encoder Unified Load Balancing and Dynamic Sequence Parallelism in Multimodal Pretraining. ByteDance Seed.
 - *2025.12 - Now*, Eﬀicient Checkpoint-Restore Techniques for Large Model Elastic Training. Lenovo.
 - *2024.12 - 2025.12*, Eﬀicient and Elastic Training System for Large Models. Lenovo.



<span class='anchor' id='-awards'></span>

# 🎉 Awards

 - Outstanding Graduate of Shanghai Jiao Tong University, *2022.06* 
 - Zhiyuan Honors Degree, Shanghai Jiao Tong University, *2022.06* 
 - SJTU Undergraduate Excellence Scholarship, *2019-2022*
 - SJTU Zhiyuan Honors Scholarship, *2018-2022*
 - SJTU Xiaomi Scholarship, *2021.12*
