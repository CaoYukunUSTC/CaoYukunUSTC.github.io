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
# 👦 About me
<span class='anchor' id='about-me'></span>
Hi！I am a second-year Ph.D. student in [the School of Computer Science and Technology](https://cs.ustc.edu.cn/main.htm), [the University of Science and Technology of China (USTC,中国科大计算机学院)](https://www.ustc.edu.cn/); Data Darkness Lab (DDL Lab, led by [Prof. Xike Xie (谢希科)](http://staff.ustc.edu.cn/~xkxie/index.html)), Center for Medical Imaging, Robotics,
Analytic Computing & Learning ([MIRACLE Center](https://miracle.ustc.edu.cn/main.htm), led by [Prof. S. Kevin Zhou (周少华)](https://bme.ustc.edu.cn/2021/1115/c28129a532912/page.htm)), [Suzhou Institute for Advance Research](https://sz.ustc.edu.cn/index.html), [USTC](https://www.ustc.edu.cn/), supervised by [Prof. Xike Xie](http://staff.ustc.edu.cn/~xkxie/index.html) (since September 2020, postgraduate recommendation/推免入学). I received B.E. degree from [the College of Computer and Information Science and College of Software](http://cis.swu.edu.cn/), [Southwest University (SWU, 西南大学)](http://www.swu.edu.cn/) in 2020.

# 🔎 Research Interests
<span class='anchor' id='-research-interests'></span>

- **AI Field：** *Few-shot Learning*, *Meta-learning*, *Memory-augmented Network*, *Deep Generative Models*
- **LLMs Field：** *Graph/KG RAG*, *LLMs for Graph Understanding/Reasoning*, *Memory Module in LLMs Agent*
- **DB Field：** *Data/Graph Stream Processing*, *Data Exploration*, *Approximate Query Processing (AQP)*
- **Focus Applications:** *AI for DB (e.g., Neural Data Structures, Automated Data Exploration, Learning-augmented Algorithms, Deep Generative Models-based AQP)*, *Memory Architecture and Mechanisms in LLMs*
  



# 📝 Publications 
<span class='anchor' id='-publications'></span>
- <span style="color:gray;">**\[Arxiv\]**</span>  **Yukun Cao**, Zengyi Gao, Zhiyang Li, Xike Xie, S Kevin Zhou: "LEGO-GraphRAG: Modularizing Graph-based Retrieval-Augmented Generation for Design Space Exploration".  [Paper](https://arxiv.org/abs/2411.05844)
- <span style="color:gray;">**\[Arxiv\]**</span>  **Yukun Cao**, Shuo Han, Zengyi Gao, Zezhong Ding, Xike Xie, S Kevin Zhou: "GraphInsight: Unlocking Insights in Large Language Models for Graph Structure Understanding".  [Paper](https://arxiv.org/abs/2409.03258)
- <span style="color:gray;">**\[Arxiv\]**</span>   Zengyi Gao, **Yukun Cao <sup>Co-First</sup>**, Hairu Wang, Ao Ke, Yuan Feng, Xike Xie, S Kevin Zhou: "FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs".  [Paper](https://arxiv.org/pdf/2501.09957)
- <span style="color:gray;">**\[Arxiv\]**</span>  Yuan Feng, Junlin Lv, **Yukun Cao**, Xike Xie, S. Kevin Zhou: "Ada-kv: Optimizing kv cache eviction by adaptive budget allocation for efficient llm inference".  [Paper](https://arxiv.org/abs/2407.11550v3)
- <span style="color:gray;">**\[Arxiv\]**</span>  Yuan Feng, Junlin Lv, **Yukun Cao**, Xike Xie, S. Kevin Zhou: "Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective".  [Paper](https://arxiv.org/pdf/2502.03805)
- <span style="color:blue;">**\[IJCAI 25-Long Paper (CCF-A)\]**</span> Ao Ke, Wenlong Chen, Chuanwen Feng, **Yukun Cao**, Xike Xie, S.Kevin Zhou, Lei Feng: "Prototype-based Optimal Transport for Out-of-Distribution Detection": *The 34th International Joint Conference on Artificial Intelligence (IJCAI-25)*. [Paper](https://arxiv.org/abs/2410.07617)
- <span style="color:red;">**\[TPAMI 24-Regular Paper (CCF-A)\]**</span> **Yukun Cao**, Yuan Feng, Hairu Wang, Xike Xie, S. Kevin Zhou: "Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data": *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*. [Paper](https://ieeexplore.ieee.org/document/10499867)
- <span style="color:blue;">**\[ICLR 24-Spotlight Paper (Top AI conf.)\]**</span> Yuan Feng, **Yukun Cao <sup>Co-First</sup>**, Hairu Wang, Xike Xie, S. Kevin Zhou: "Mayfly: a Neural Data Structure for Graph Stream Summarization": *The Twelfth International Conference on Learning Representations (ICLR 2024), __Spotlight (Rate:5%)__*. [Paper](https://openreview.net/pdf?id=n7Sr8SW4bn)
- <span style="color:blue;">**\[ICDE 23-Regular Paper (CCF-A)\]**</span> **Yukun Cao**, Xike Xie, Kexing Huang: "Learn to Explore: on Bootstrapping Interactive Data Exploration with Meta-learning": *The 39th IEEE International Conference on Data Engineering (ICDE 2023)*. [Paper](https://ieeexplore.ieee.org/document/10184532)
- <span style="color:blue;">**\[AAAI 23-Oral Paper (CCF-A)\]**</span> **Yukun Cao**, Yuan Feng, Xike Xie: "Meta-sketch: A Neural Data Structure for Estimating Item Frequencies of Data Streams": *Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI 2023), __Oral (Rate:11%)__*. [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25846)
- <span style="color:green;">**\[GROUP 23-Demo Paper (CCF-B)\]**</span> Haoyun Li, **Yukun Cao**, Xike Xie: "VR-Explorer: A Demonstration of a Virtual Reality Interactive Data Exploration System": *The 2023 ACM International Conference on Supporting Group Work (GROUP 2023), Companion*. [Paper](https://dl.acm.org/doi/abs/10.1145/3565967.3570976), [Project Site](https://dataexplorevr.github.io/)
- <span style="color:green;">**\[KSEM 19-Long Paper (CCF-C)\]**</span> Jingyuan Wang, **Yukun Cao**, Ye Du, Li Li: "DST: A Deep Urban Traffic Flow Prediction Framework Based on Spatial-Temporal Features": *Knowledge Science, Engineering and Management-12th International Conference (KSEM 2019)*. 
- <span style="color:green;">**\[ICWE 19-Long Paper (CCF-C)\]**</span>  Xiaofei Xu, **Yukun Cao**, Li Li: "Exploring Semantic Change of Chinese Word Using Crawled Web Data": *Web Engineering-19th International Conference (ICWE 2019)*.
- <span style="color:green;">**\[KSEM 19-Long Paper (CCF-C)\]**</span>  Kexin Huang, **Yukun Cao**, Ye Du, Li Li: "Social-Aware and Sequential Embedding for Cold-Start Recommendation": *Knowledge Science, Engineering and Management-12th International Conference (KSEM 2019)*.




# 🎖 Honors and Awards
<span class='anchor' id='-honors-and-awards'></span>
- 2024 **Suzhou Industrial Park Scholarship (苏州工业园区奖学金)** at USTC.
- 2023 **Suzhou Industrial Park Scholarship (苏州工业园区奖学金)** at USTC.
- 2022 **Yuan-Qing Scholarship (元庆奖学金，选拔中国科大计算机学院2022级的4名博士生)** at USTC (Selecting 4 PhD students in the 2022 class of School of Computer Science).
- 2020 **Outstanding Graduates Award of Chongqing City (重庆市优秀毕业生)**.
- 2020 **Scholarship of Gratitude to Chinese Modern and Contemporary Scientists (感恩中国近现代科学家奖学金，面向中国西部的985/211高校评选，每所高校只评选10名)** (Targeting 985/211 project Universities in Western China, each university has only 10 students).
- 2020 **Pin-Sheng Scholarship (品胜奖学金)** at SWU (Rate: $\approx$ 1/480).
- 2019 **Yu-Hui Scholarship (玉辉奖学金)** at SWU (Rate: $\approx$ 1/480).
- 2017/2018/2019 three times **National Scholarship (三次获得 国家奖学金)** at SWU (Rate: $\approx$ 1/120).
- 2019 **Excellence in Learning Award (学习优胜奖)** at SWU.
- 2018 **Advanced Individual in Technological Innovation (科创先进个人称号)** at SWU.
- 2017/2018 twice **Outstanding Student Award（两次获得 三好学生称号）** at SWU.

# 📖 Educations
<span class='anchor' id='-educations'></span>

- **2022.09 - , PhD candidate in Computer Science.**

    *School of Computer Science and Technology, University of Science and Technology of China (CS, USTC), Hefei, Anhui.*

- **2020.09 - 2022.06, Master in Computer Science.**

    *School of Computer Science and Technology, University of Science and Technology of China (CS, USTC), Hefei, Anhui.*
 
- **2016.09 - 2020.06, Bachelor in Computer Science.**
 
    *College of Computer and Information Science and College of Software, Southwest University (CS, SWU), Beibei, Chongqing.* **Rank：1/126**
 






 
