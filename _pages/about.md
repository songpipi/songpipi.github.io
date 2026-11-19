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

I am currently an Associate Researcher at the School of Information Science and Technology, University of Science and Technology of China (USTC).
I am a member of the [Future Media Computing Lab (未来媒体计算实验室)](https://ustc.fmclab.cn), led by Prof. [Xiaojun Chang (常晓军)](https://www.xiaojun.ai/) and Prof. [Xun Yang (杨勋)](https://faculty.ustc.edu.cn/yangxun/en/index.htm).

I completed my postdoctoral researcher job from July 2023 to June 2025 at the School of Information Science and Technology, University of Science and Technology of China, in Hefei, China, under the supervision of Prof. [Xun Yang (杨勋)](https://faculty.ustc.edu.cn/yangxun/en/index.htm). I obtained my bachelor's and doctoral degrees from the School of Computer Science and Information Engineering, Hefei University of Technology. During my doctoral studies, I was supervised by Prof. [Meng Wang (汪萌)](https://scholar.google.com/citations?user=rHagaaIAAAAJ). <!-- and Prof. [Dan Guo (郭丹)](https://scholar.google.com/citations?user=DsEONuMAAAAJ). -->

My research centers on multimodal intelligence, with a focus on perception, reasoning, and generation across vision, language, and audio modalities. I am particularly interested in how machines can perceive, interpret, and respond to human emotions in a multimodal context. My work spans topics such as cross-modal retrieval, visual captioning, and visual emotion reasoning, with the long-term goal of building empathetic and human-centric AI systems. If you are seeking any form of academic cooperation, please feel free to [contact me](mailto:beta.songpp@gmail.com).


# 🔥 News
- **2026.11**: 🏆 Our paper received the **ACM MM 2026 Outstanding Paper Award**! Congrats to **Pengyu**!
- **2026.07**: 🎉 Two papers are accepted to **ACM MM 2026**! Congrats to **Zhiyan** and **Pengyu**!
- **2026.06**: 🎉 Two papers are accepted to **ECCV 2026**! Congrats to **Wenlin** and **Zhiyan**!
- **2026.05**: 🏅 Honored to receive the **ICML 2026 Silver Reviewer Award**!
- **2026.05**: 🎉 One paper is accepted to **ICML 2026**! Congrats to **Zhiyuan**!
- **2026.01**: 🎉 One paper is accepted to **WWW 2026**! Congrats to **Yangyang**!


# 📝 Selected Publications

- **Layer Roles Matter: Mitigating Modality Imbalance in Multimodal Emotion Reasoning via Adaptive Layer Profiling**  
  Pengyu Huang, **Peipei Song**, Beier Zhu, Zhiyuan Han, Jinpeng Hu, Xun Yang  
  <span style="background-color:#E8F1FF;color:#2457A6;padding:3px 8px;border-radius:5px;font-weight:600;">ACM MM 2026</span> <span style="background-color:#FFF0DC;color:#A85A12;padding:3px 8px;border-radius:5px;font-weight:600;">Oral</span> <span style="background-color:#FFF1C2;color:#8C6100;padding:3px 8px;border-radius:5px;font-weight:700;">🏆 Outstanding Paper Award</span>   [[Paper]](https://arxiv.org/abs/2611.11907) · [[Project]](https://pengyuhuang1.github.io/LAMR/)

- **Benchmarking Dynamic Affective Reasoning: A Viewer-Centric Video Emotion Dataset**  
  Zhiyan Zhang, **Peipei Song**, Jinpeng Hu, Jingyang Jia, Xun Yang, Xiaojun Chang  
  <span style="background-color:#E8F1FF;color:#2457A6;padding:3px 8px;border-radius:5px;font-weight:600;">ECCV 2026</span>  [[Paper]](https://arxiv.org/abs/2607.10238) · [[Code]](https://github.com/Zhang-Zhiyan/DAR)

- **Bridging Subjectivity in Affective Explanation Captioning via Consensus-Prompted Emotion Reasoning**  
  **Peipei Song**, Zhiyan Zhang, Weidong Chen, Jinpeng Hu, Xun Yang, Xiaojun Chang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TIP 2026</span>  [[Paper]](https://doi.org/10.1109/TIP.2026.3703790) · [[Code]](https://github.com/songpipi/CPER)

- **Aleatoric-Epistemic Joint Uncertainty Modeling for Cross-Modal Retrieval**  
  Tianyu Chang, **Peipei Song**, Xun Yang, Dan Guo, Xiaojun Chang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TCYB 2026</span>  [[Paper]](https://doi.org/10.1109/TCYB.2026.3664380) · [[Code]](https://github.com/cty8998/AEUM)

- **Video Corpus Moment Retrieval With Query-Specific Context Learning and Progressive Localization**  
  Long Zhang, **Peipei Song**, Zhangling Duan, Shuo Wang, Xiaojun Chang, Xun Yang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TCSVT 2025</span>  [[Paper]](https://doi.org/10.1109/TCSVT.2025.3530570)

- **Towards Efficient Partially Relevant Video Retrieval With Active Moment Discovering**  
  **Peipei Song**, Long Zhang, Long Lan, Weidong Chen, Dan Guo, Xun Yang, Meng Wang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TMM 2025</span>  [[Paper]](https://doi.org/10.1109/TMM.2025.3590937) · [[Code]](https://github.com/songpipi/AMDNet)

- **Emotional Video Captioning With Vision-Based Emotion Interpretation Network**  
  **Peipei Song**, Dan Guo, Xun Yang, Shengeng Tang, Meng Wang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TIP 2024</span>  [[Paper]](https://doi.org/10.1109/TIP.2024.3359045)

- **Emotion-Prior Awareness Network for Emotional Video Captioning**  
  **Peipei Song**, Dan Guo, Xun Yang, Shengeng Tang, Erkun Yang, Meng Wang  
  <span style="background-color:#E8F1FF;color:#2457A6;padding:3px 8px;border-radius:5px;font-weight:600;">ACM MM 2023</span> <span style="background-color:#FFF0DC;color:#A85A12;padding:3px 8px;border-radius:5px;font-weight:600;">Oral</span>  [[Paper]](https://doi.org/10.1145/3581783.3611726) · [[Code]](https://github.com/songpipi/EPAN)

- **Contextual Attention Network for Emotional Video Captioning**  
  **Peipei Song**, Dan Guo, Jun Cheng, Meng Wang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TMM 2022</span>  [[Paper]](https://doi.org/10.1109/TMM.2022.3183402)

- **Memorial GAN With Joint Semantic Optimization for Unpaired Image Captioning**  
  **Peipei Song**, Dan Guo, Jinxing Zhou, Mingliang Xu, Meng Wang  
  <span style="background-color:#E6F5EB;color:#237346;padding:3px 8px;border-radius:5px;font-weight:600;">IEEE TCYB 2022</span>  [[Paper]](https://doi.org/10.1109/TCYB.2022.3175012)

<!-- 这是一行注释，不会显示在网页上 -->
<!-- 
# 🎖 Funds
- *2025.01--2027.12*, Young Scientists Fund (C Class), National Natural Science Foundation of China.
- *2025.01--2026.06*, General Program, China Postdoctoral Science Foundation.
-->

# 🏅 Honors & Awards
- *2026.11*, **Outstanding Paper Award**, ACM Multimedia (ACM MM 2026).
- *2026.05*, **Silver Reviewer Award**, International Conference on Machine Learning (ICML 2026).
- *2026.01*, **Second-Class Funding Award**, Mozi Outstanding Young Scholar Special Support Program, University of Science and Technology of China (USTC).
- *2025.08*, **First Place Award**, MiGA Challenge 2025, Track 2: Micro-gesture Online Recognition.

# 📖 Experience
- *2025.07--Now*, Associate Researcher, School of Information Science and Technology, University of Science and Technology of China, Hefei, China. 
- *2023.07--2025.06*, Postdoc, School of Information Science and Technology, University of Science and Technology of China, Hefei, China. 
- *2017.09--2023.06*, PhD, School of Computer Science and Information Engineering, Hefei University of Technology, Hefei, China. 
- *2013.09--2017.06*, Undergraduate, School of Computer Science and Information Engineering, Hefei University of Technology, Hefei, China.

# 💻 Services  
- **Conference Reviewer:** ICCV, CVPR, ACM MM, NeurIPS, ICLR, AAAI, WWW.
- **Journal Reviewer:** IEEE TMM, IEEE TNNLS, IEEE TCSVT, ACM TOMM, Pattern Recognition, Neurocomputing.


