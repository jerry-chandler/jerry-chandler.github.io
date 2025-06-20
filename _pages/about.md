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

I'm a third year Ph.D candidate at [Zhejiang University (浙江大学)](https://www.zju.edu.cn/), Hangzhou, China, advised by Prof. [Xunzhao Yin](https://person.zju.edu.cn/en/xunzhaoyin). My research interests include compute-in-memory circuit/system design and software-hardware co-design for acceleration of content addressable memory (CAM), neural network (NN) and combinatorial optimization problems (COPs). 

I have published several [papers](https://scholar.google.com/citations?user=RoH8vVYAAAAJ) in top journals and conference proceedings including Nature Communications, IEEE Transactions on Circuits and Systems I: Regular Papers (TCAS-I), IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), IEEE Transactions on Very Large Scale Integration Systems (TVLSI), Design Automation Conference (DAC), Design Automation and Test in Europe (DATE),  Asia and South Pacific Design Automation Conference (ASP-DAC), etc. 

I anticipate being on the job market in 2027 and welcome contact and collaboration from both academia and industry. Please feel free to reach out!
  


<span class='anchor' id='-news'></span>

# 🔥 News
- *2025.02*, our paper is accepted by TCAS-I! Congratulations to all!
- *2025.02*, two papers are accepted by DAC 2025! Congratulations to all!
- *2024.10*, I am awarded the National Scholarship as a Ph.D student!
- *2024.05*, our paper is accepted by TVLSI! Congratulations to all!
- *2024.03*, our paper is published on Nature Communications! Congratulations to all! The paper is available at [https://www.nature.com/articles/s41467-024-46640-x](https://www.nature.com/articles/s41467-024-46640-x).
- *2024.02*, three papers are accepted by DAC 2024! Congratulations to all!

 
<span class='anchor' id='-publications'></span>

# 📝 Publications
## 📚 Journal Papers
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">TCAS-I 2025</span> **Yu Qian**, Ding Huang, Alptekin Vardar, Nellie Laleni, Min Zhou, Kai Ni, Thomas Kämpfe, Cheng zhuo and Xunzhao Yin, "Ferroelectric Compute-in-Memory Framework for Solving Pure and Mixed Strategy Nash Equilibrium". IEEE Transactions on Circuits and Systems I: Regular Papers. (IF = 5.2, SCI Section II)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">TVLSI 2024</span> **Yu Qian**\*, Liang Zhao\*, Fanzi Meng, Xiapeng Xu, Cheng zhuo and Xunzhao Yin, "Enhancing ConvNets with ConvFIFO: A Crossbar PIM Architecture Based on Kernel-Stationary First-In-First-Out Dataflow". IEEE Transactions on Very Large Scale Integration Systems, 2024 (01): 1-12. (IF = 2.8, SCI Section II)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">Nature Communications 2024</span> Xunzhao Yin\*, **Yu Qian**\*, Alptekin Vardar, Marcel Günther, Franz Müller, Nellie Laleni, Zijian Zhao, Zhouhang Jiang, Zhiguo Shi, Yiyu Shi, Xiao Gong, Cheng Zhuo, Thomas Kämpfe and Kai Ni, "Ferroelectric Compute-in-Memory Annealer for Combinatorial Optimization Problems". Nature Communications 15, 2419 (2024). (IF = 14.7, SCI Section I, <span style="color:red; font-weight:bold;">Editor’s Highlights</span>)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">TCAD 2022</span> Xunzhao Yin, **Yu Qian**, Mohsen Imani, Kai Ni, Chao Li, Grace Li Zhang, Bing Li, Ulf Schlichtmann and Cheng Zhuo, "Ferroelectric Ternary Content Addressable Memories for Energy-Efficient Associative Search", IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022, 42(4): 1099-1112. (IF = 2.7, CCF-A, SCI Section III)

## 📚 Conference Papers
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DAC 2025</span> **Yu Qian**, Xianmin Huang, Ranran Wang, Zeyu Yang, Min Zhou, Thomas Kämpfe, Cheng Zhuo and Xunzhao Yin, "Device-Algorithm Co-Design of Ferroelectric Compute-in-Memory In-Situ Annealer for Combinatorial Optimization Problems", ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 21-25, 2025. (CCF-A, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DAC 2025</span> Xuliang Yu, **Yu Qian**, Xunzhao Yin, Cheng Zhuo and Liang Zhao, "FeKAN: Efficient Kolmogorov-Arnold Networks Accelerator Using FeFET-based CAM and LUT", ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 21-25, 2025. (CCF-A, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">ISEDA 2025</span> Jiayi Wang, **Yu Qian**, Zeyu Yang, Zheyu Yan, Cheng Zhuo and Xunzhao Yin", ACM/IEEE International Symposium of EDA (ISEDA), Hong Kong Disneyland, China, May 9-12, 2025.
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DAC 2024</span> **Yu Qian**, Zeyu Yang, Kai Ni, Alptekin Vardar, Thomas Kämpfe and Xunzhao Yin, "HyCiM: A Hybrid Computing-in-Memory QUBO Solver for General Combinatorial Optimization Problems with Inequality Constraints", ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 23-27, 2024. 2024: 1-6. (CCF-A, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DAC 2024</span> **Yu Qian**, Kai Ni, Thomas Kämpfe, Cheng Zhuo and Xunzhao Yin, "C-Nash: A Novel Ferroelectric Computing-in-Memory Architecture for Solving Mixed Strategy Nash Equilibrium", ACM/IEEE Design Automation Conference(DAC), San Francisco, CA, Jun. 23-27, 2024. 2024: 1-6. (CCF-A, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DAC 2024</span> Zeyu Yang, Qingrong Huang, **Yu Qian**, Kai Ni, Thomas Kämpfe and Xunzhao Yin, "Energy Efficient Dual Designs of FeFET-Based Analog In-Memory Computing with Inherent Shift-Add Capability", ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, Jun. 23-27, 2024. 2024: 1-6. (CCF-A, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">ASP-DAC 2024</span> Liang Zhao\*, **Yu Qian**\*, Fanzi Meng, Xiapeng Xu, Xunzhao Yin and Cheng Zhuo, "ConvFIFO: A Crossbar Memory PIM Architecture for ConvNets Featuring First-In-First-Out Dataflow", IEEE/ACM Asian and South Pacific Design Automation Conference (ASPDAC),  Incheon Songdo Convensia, South Korea, Jan. 22-25, 2024. IEEE, 2024: 824-829. (CCF-C, EDA TOP 4 Conference)
- <span style="background-color:blue; color:white; font-family: 'Special Elite', cursive;">DATE 2021</span> **Yu Qian**, Zhenhao Fan, Haoran Wang, Chao Li, Mohsen Imani, Kai Ni, Grace Li Zhang, Bing Li, Ulf Schlichtmann, Cheng Zhuo and Xunzhao Yin, "Energy-Aware Designs of Ferroelectric Ternary Content Addressable Memory", IEEE/ACM Proceedings Design, Automation and Test in Europe (DATE), Virtual, Feb. 1-5, 2021. IEEE, 2021: 1090-1095. (CCF-B, EDA TOP 4 Conference)

<span class='anchor' id='-honors'></span>

# 🎖️ Selected Honors and Awards

- Outstanding Poster Award at the Post-Moore Academic Annual Conference, *2025*
- National Scholarship (Ph.D), *2024*
- Yuelun Alumni Scholarship (Two Times), *2023, 2021*
- Outstanding Graduates of Zhejiang Province, *2022*
- National Scholarship (Two Times, Undergraduate), *2020-2021*
- The First Class Scholarship (Three Times), *2019-2021*
- Bronze medal of Student Research Competition at ICCAD, *2021*
- Enterprise Special Award at Integrated Circuit EDA Design Elite Challenge (Team Leader), *2021* 
- Huawei Elite Scholarship, *2020*

<span class='anchor' id='-service'></span>

# ✍🏻 Academic Service
- Conference Reviewer: ISCAS *2025*
- Journal Reviewer: TCAD

<span class='anchor' id='-talk'></span>

# 🪑 Invited Talks
- "FeFET-based Compute-in-Memory Solver for Combinatorial Optimization Problems", FIT Forum of the Facalty of Information Technology, Zhejiang University, *2025*
- "A Compute-in-Memory Framework for Nach Equilibrium Problems", Academic Forum of the School of Integrated Circuits, Zhejiang University, *2025*

<span class='anchor' id='-athlete'></span>

# 🏆️ Athlete Performance

- 1st place (men's team) and 3rd place (mixed doubles) in the Zhejiang Province University Table Tennis Championship, *2024*
- 2nd place (men's team) and 3rd place (mixed doubles) in the Table Tennis Competition of the 16th University Games of Zhejiang Province, *2022*

<span class='anchor' id='-educations'></span>

# 🎓 Educations

- *2022.09 - Present*, Zhejiang University, Hangzhou, China, Ph.D., Electronic Science and Technology
- *2018.09 - 2022.06*, Zhejiang University, Hangzhou, China, B.Eng., Microelectronics Science and Engineering (GPA: 3.92/4, Rank: 4/77)

<span class='anchor' id='-hobby'></span>

# 🏃 Specialties and Hobbies

- 🏓 Table Tennis: Member of Zhejiang University team, *2018-Present*
- 🎤 Host: Host of the College New Year Party and Graduation Party, *2020-2022*


<a href="https://info.flagcounter.com/ang3"><img src="https://s11.flagcounter.com/count2/ang3/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
