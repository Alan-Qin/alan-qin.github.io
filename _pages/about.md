---
permalink: /
title: "Zeyu Qin (秦泽钰)"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<span class='anchor' id='about-me'></span>


# 🎓 About Me

I am Zeyu Qin (秦泽钰), a third-year Ph.D. student of [Computer Science & Engineering](https://cse.hkust.edu.hk/) at [Hong Kong University of Science and Technology](https://hkust.edu.hk/) (HKUST). My advisors are [Prof. Yi R. (May) Fung](https://mayrfung.github.io/) and [Prof. Minhao Cheng](https://cmhcbb.github.io/). Recently, I also collaborate with [Prof. Li Shen](https://sites.google.com/site/mathshenli/home), [Prof. Ruoyu Sun](https://ruoyus.github.io/), and [Dr. Yongqiang Chen](http://lfhase.win/). My research interest is broadly on _Scalable Oversight, and AI Safety_.  

Currently, I am focusing on:  
1) **Scaling Compute to Acticate Model Capacity**: Scaling Training-time and Testing-time Compute
2) **Agent Reasoning and Generalization**: Developing Robust Reasoning
3) **Training Reward Models and Critique Systems**: Providing Reliable Supervision Signals         


<!-- 
1) **Understanding of how data shapes models**: Helping Specify Better Learning Objective; Faithful Evaluation or Debugging Models    
2) **Reliable and Generalizable Reasoning**;    
3) **How to obtain "Better" and more Safe Supervision for oversighting LLMs**.   
-->


_I am very fortunate to have worked with lots of distinguished researchers: Dr. Liuyi Yao, Daoyuan Chen, Dr. Yaliang Li, Prof. Baoyuan Wu, Dr. Yanbo Fan, Prof. Hongyuan Zha, Dr. Jiancong Xiao, and Prof. Piji Li. I had an amazing four years at LGU with my good friends from Room 310 and Room 224. Miss you, guys!_


# 📜 News
- *2025.07*：**Scaling Laws of Synthetic Data for Language Models** has been accepted to **COLM 2025**.
- *2025.05*: **Safety Reasoning paper has been accepted to ICML 2025**: we explore the **Safety Reasoning with Guidelines**. We introduce **SRG**, a scalable framework that synthesizes safety CoT supervision to encourage models to reason in alignment with diverse safety guidelines, each reflecting a different perspective on safety knowledge. Our SRG significantly improves OOD generalization of safety alignment. 
- *2025.03*: New work: we explore the **Scaling Laws of Synthetic Data for Language Models**. We introducing **SynthLLM**, a scalable framework that transforms pre-training corpora into diverse, high-quality synthetic datasets and find synthetic data that reliably adheres to the rectified scaling law across various model sizes.
- *2024.09*: **One <span style="color: red;">Spotlight</span> has been accepted to NeurIPS 2024**: Understanding **Superficial safety of Safety Tuning**--the Backdoor Purification Case. We demonstrated that safety fine-tuning cannot fully eliminate learned harmful features and provided a detailed analysis.
- *2023.09*: **Two papers (one <span style="color: red;">Spotlight</span>) have been accepted to NeurIPS 2023**: 1. Feature shift tuning which achieves SOTA purification performance against backdoor attacks; 2. Spotlight! Imitation learning from imperfect demonstrations (See [Ziniu Li](http://www.liziniu.org/)).
- *2023.05*: New work has been accepted to KDD 2023: The first study about **robustness from personalization in FL against backdoor attacks**.


<!-- 
- *2022.09*: The paper about **improving adversarial transferability by utilizing flatness of loss landscape (Reverse Adversarial Perturbation)** was accepted to NeurIPS 2022.
- *2021.09*: The paper about defense against query-based attacks **(Random Noise Defense)** was accepted to NeurIPS 2021.-->

# 📝 Publications 

**\* denoting equal contribution   $^{\dagger}$ denoting corresponding author**


## Scalable and Reliable Oversight

- **Scaling Laws of Synthetic Data for Language Models**   
**Zeyu Qin**, Qingxiu Dong, Xingxing Zhang $^{\dagger}$, Li Dong, Xiaolong Huang, Ziyi Yang, Mahmoud Khademi, Dongdong Zhang, Hany Hassan Awadalla, Yi R. Fung, Weizhu Chen, Minhao Cheng, Furu Wei $^{\dagger}$    
***COLM 2025*** [[arxiv](https://arxiv.org/abs/2503.19551)]

- **Safety Reasoning with Guidelines**   
Haoyu Wang\*, **Zeyu Qin\* $^{\dagger}$**, Li Shen, Xueqian Wang, Dacheng Tao, Minhao Cheng.  
***ICML 2025*** [[arxiv](https://arxiv.org/abs/2502.04040)]

- **Reinforcement Learning with Rubric Anchors**   
Zenan Huang\*, Yihong Zhuang\*, Guoshan Lu\*, **Zeyu Qin\***, Haokai Xu\*, Tianyu Zhao, Ru Peng, Jiaqi Hu, Zhanming Shen, Xiaomeng Hu, Xijun Gu, Peiyi Tu, Jiaxin Liu, Wenyu Chen, Yuzhuo Fu, Zhiting Fan, Yanmei Gu, Yuanyuan Wang, Zhengkai Yang, Jianguo Li, Junbo Zhao$^{\dagger}$  
Arxiv 2025 [[arxiv](https://arxiv.org/abs/2508.12790)]  

<!-- 
- **Uncovering, Explaining, and Mitigating the Superficial Safety of Backdoor Defense (<span style="color: red;">Spotlight!</span>)**    
Rui Min\*, **Zeyu Qin\* $^{\dagger}$**, Nevin Zhang, Li Shen, Minhao Cheng.   
***NeurIPS 2024*** [[arxiv](https://arxiv.org/abs/2410.09838)] [[code](https://github.com/AISafety-HKUST/Backdoor_Safety_Tuning)]
-->


## AI Safety

### Data Safety

- **Uncovering, Explaining, and Mitigating the Superficial Safety of Backdoor Defense (<span style="color: red;">Spotlight!</span>)**    
Rui Min\*, **Zeyu Qin\* $^{\dagger}$**, Nevin Zhang, Li Shen, Minhao Cheng.   
***NeurIPS 2024*** [[arxiv](https://arxiv.org/abs/2410.09838)] [[code](https://github.com/AISafety-HKUST/Backdoor_Safety_Tuning)]


- **Towards Stable Backdoor Purification through Feature Shift Tuning**    
Rui Min\*, **Zeyu Qin\* $^{\dagger}$**, Li Shen, Minhao Cheng.    
***NeurIPS 2023*** [[arxiv](https://arxiv.org/abs/2310.01875)] [[OpenReview](https://openreview.net/forum?id=8muKbaAgsh)] [[code](https://github.com/AISafety-HKUST/Backdoor_Safety_Tuning)]


- **Revisiting Personalized Federated Learning: Robustness Against Backdoor Attacks**   
**Zeyu Qin**, Liuyi Yao, Daoyuan Chen, Yaliang Li, Boling Ding, Minhao Cheng.   
***KDD 2023*** [[arxiv](https://arxiv.org/abs/2302.01677)] [[code](https://github.com/alibaba/FederatedScope/tree/backdoor-bench)]


### Adversarial Machine Learning

- **Boosting the Transferability of Adversarial Attacks with Reverse Adversarial Perturbation**    
**Zeyu Qin\***, Yanbo Fan\*, Yi Liu, Li Shen, Yong Zhang, Jue Wang, Baoyuan Wu.    
***NeurIPS 2022*** [[arxiv](https://arxiv.org/abs/2210.05968)] [[OpenReview](https://openreview.net/forum?id=k5uFiFLWv3X)] [[code](https://github.com/Alan-Qin/Transfer_attack_RAP)]

- **Random Noise Defense Against Query-Based Black-Box Attacks**    
**Zeyu Qin**, Yanbo Fan, Hongyuan Zha, Baoyuan Wu.    
***NeurIPS 2021*** [[arxiv](https://arxiv.org/abs/2104.11470)] [[OpenReview](https://openreview.net/forum?id=ZPSD4xZc6j8)] [[code](https://github.com/SCLBD/BlackboxBench)]

-------

## Collaboration with Excellent Researchers

- **Preserving Diversity in Supervised Fine-Tuning of Large Language Models**       
Ziniu Li, Congliang Chen, Tian Xu, **Zeyu Qin**, Jiancong Xiao, Ruoyu Sun, Zhi-Quan Luo.       
***ICLR 2025*** [[arxiv](https://arxiv.org/abs/2408.16673)]


- **Imitation Learning from Imperfection: Theoretical Justifications and Algorithms (<span style="color: red;">Spotlight!</span>)**    
Ziniu Li\*, Tian Xu\*, **Zeyu Qin**, Yang Yu, Zhiquan Luo.    
***NeurIPS 2023*** [[OpenReview](https://openreview.net/forum?id=vO04AzsB49)]  
(This is excellent work from Ziniu and Tian. I only conducted part of the experiments. I almost have no idea about Imitation Learning 😂.)


- **Beyond Factuality: A Comprehensive Evaluation of Large Language Models as Knowledge Generators**  
Liang Chen, Yang Deng, Yatao Bian, **Zeyu Qin**, Bingzhe Wu, Tat-Seng Chua, Kam-Fai Wong.   
***EMNLP 2023*** [[arxiv](https://arxiv.org/abs/2310.07289)] [[code](https://github.com/chanliang/conner)]

- **Adaptive Smoothness-weighted Adversarial Training for Multiple Perturbations with Its Stability Analysis.**  
Jiancong Xiao, **Zeyu Qin**, Yanbo Fan, Baoyuan Wu, Jue Wang, Zhi-Quan Luo.    
*ICML 2023 Workshop AdvML-Frontiers, 2023* [[arxiv](https://arxiv.org/abs/2210.00557)]


# 📝 Preprints
**\* denoting equal contribution  ^ denoting corresponding author**  

- **Quality-Diversity Red-Teaming: Automated Generation of High-Quality and Diverse Attackers for Large Language Models**     
Ren-Jian Wang, Ke Xue, **Zeyu Qin**, Ziniu Li, Sheng Tang, Hao-Tian Li, Shengcai Liu, Chao Qian.    
*Arxiv, 2025.* [[arxiv](https://arxiv.org/abs/2506.07121)]

- **Lifelong Safety Alignment for Language Models**     
Haoyu Wang, **Zeyu Qin**, Yifei Zhao, Chao Du, Min Lin, Xueqian Wang, Tianyu Pang.    
*Arxiv, 2025.* [[arxiv](https://arxiv.org/abs/2505.20259)]

- **Does Representation Intervention Really Identify Desired Concepts and Elicit Alignment?**     
Hongzheng Yang\*, Yongqiang Chen\*, **Zeyu Qin**, Tongliang Liu, Chaowei Xiao, Kun Zhang, Bo Han.    
*Arxiv, 2025.* [[arxiv](https://arxiv.org/abs/2505.18672)]


- **Step-On-Feet Tuning: Scaling Self-Alignment of LLMs via Bootstrapping**     
Haoyu Wang, Guozheng Ma, Ziqiao Meng, **Zeyu Qin**, Li Shen, Zhong Zhang, Bingzhe Wu, Liu Liu, Yatao Bian, Tingyang Xu, Xueqian Wang, Peilin Zhao.    
*Arxiv, 2024.* [[arxiv](https://arxiv.org/abs/2402.07610)]


# 🎖 Honors and Awards
- *2024.09*, NeurIPS 2024 Spotlight Paper
- *2023.09*, NeurIPS 2023 Spotlight Paper
- *2021.04*, Poster Runner-Up Reward of The First Doctoral and Postdoctoral Academic Forum of Shenzhen Research Institute of Big Data

<!-- 
# 📖 Educations
- *2022.08 - Now*, Ph.D. student in Computer Science & Engineering, The Hong Kong University of Science and Technology.
- *2018.08 - 2022.05 (Ph.D. -> M.Phil)*, M.Phil in Computer and Information Engineering, The Chinese University of Hong Kong, Shenzhen.
- *2014.09 - 2018.06*, B.Eng. in Information Engineering, Nanjing University of Aeronautics and Astronautics.
-->

# 💬 Invited Talks
- *2022.10*, Adversarial Transferability in AI Times Forum.

# 💻 Internships
- November 2024 -- July 2025: Research Intern, MSRA GenAI, Beijing, China
- June 2022 -- May 2023: Research Intern, Alibaba Damo Academy, Hangzhou, China
- July 2021 -- May 2022: Research Intern, Tencent AI Lab, Shenzhen, China
- January 2020 -- October 2020: Research Intern, Tencent AI Lab, Shenzhen, China

# 📧 Contact
zeyu.qin@connect.ust.hk ; zeyu6181136@gmail.com
