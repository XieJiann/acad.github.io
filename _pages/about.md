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
# JingWei Xu
<img src = "https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=15maGTwAAAAJ&citpid=3" align = "right" width = "200">
- Assistant Researcher
- Institute of Computer Software, Nanjing University
- Room 919, Computer Science and Technology Building
- jingweix (at) nju dot edu dot cn

My research interest includes DNN, DevOps for Intelligent Software


# News
- &nbsp;🎉🎉 Congratulations on Jian Xie's Neurips'22 paper "A Deep Learning Dataloader with Shared Data Preparation"!
- &nbsp;🎉🎉 Congratulations on Sen Wang and Zhuheng Sheng's ASE'22 tool-demo paper "ADEPT: A Testing Platform for Simulated Autonomous Driving"!
- &nbsp;🎉🎉 Congratulations on Zenan Li's ESEC/FSE'20 paper "Operational calibration: Debugging confidence errors for DNNs in the field"!
- &nbsp;🎉🎉 Congratulations on Yuehuan Wang's JCST journal paper "基于鲁棒性预测的深度神经网络质量保障"!
- &nbsp;🎉🎉 Congratulations on Huiyan Wang's ICSE'20 paper "DISSECTOR: Input Validation for Deep Learning Applications by Crossing-layer Dissection"!

# Publications 

- <img src = "data:image/png;base64,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" align = "right" width = "150"> Zenan Li, Xiaoxing Ma, Chang Xu, *JingWei Xu*, Chun Cao, and Jian Lü, “[Operational calibration: Debugging confidence errors for DNNs in the field](https://dl.acm.org/doi/pdf/10.1145/3368089.3409696)”, in Proceedings of the 28th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering , 901–913, 2020.
- YueHuan Wang, Zenan Li, *JingWei Xu*, Ping Yu, Taolue Chen, and Xiaoxing Ma, “基于鲁棒性预测的深度神经网络质量保障”, 计算机科学技术学报 , 35(5), 999–1015, 2020.
- Zenan Li, Xiaoxing Ma, Chang Xu, *JingWei Xu*, Chun Cao, and Jian Lu, “Operational Calibration: Debugging Confidence Errors for DNNs in the Field”, in Proceedings of The 28th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2020) , 2020.
- Huiyan Wang, *JingWei Xu*, Chang Xu, Xiaoxing Ma, and Jian Lu, “DISSECTOR: Input Validation for Deep Learning Applications by Crossing-layer Dissection”, in Proceedings of the 42nd ACM/IEEE International Conference on Software Engineering (ICSE) , 2020.
- Yuehuan Wang, Zenan Li, *JingWei Xu*, Ping Yu, and Xiaoxing Ma, “Fast Robustness Prediction for Deep Neural Network”, in Proceedings of the 11th Asia-Pacific Symposium on Internetware , 11:1--11:10, 2019. 
- Zenan Li, Xiaoxing Ma, Chang Xu, Chun Cao, *JingWei Xu*, and Jian Lu, “Boosting Operational DNN Testing Efficiency through Conditioning”, in Proceedings of The 27th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2019) , 2019. 
- *JingWei Xu*, Yuan Yao, Hanghang Tong, Xianping Tao, and Jian Lu, “HoORaYs: High-order Optimization of Rating Distance for Recommender Systems”, in Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining , 525–534, 2017.  
- *JingWei Xu*, Yuan Yao, Hanghang Tong, Xianping Tao, and Jian Lu, “RaPare: A Generic Strategy for Cold-Start Rating Prediction Problem”, IEEE Transactions on Knowledge and Data Engineering , 1–1, 2016. 
- *JingWei Xu*, Yuan Yao, Hanghang Tong, Xianping Tao, and Jian Lu, “Ice-Breaking: Mitigating Cold-Start Recommendation Problem by Rating Comparison”, in Proceedings of the Twenty-Fourth International Joint Conference on Artificial Intelligence, IJCAI 2015, Buenos Aires, Argentina, July 25-31, 2015 , 3981–3987, 2015. 
- Haibo Ye, Tao Gu, Xiaorui Zhu, *JingWei Xu*, Xianping Tao, Jian Lu, and Ning Jin, “FTrack: Infrastructure-free floor localization via mobile phone sensing”, in 2012 IEEE International Conference on Pervasive Computing and Communications, Lugano, Switzerland, March 19-23, 2012 , 2–10, 2012

# Honors and Awards
- KDD2017 Student Travel Awards


# Services
- PC Member for: WWW 2019-2022 ASONAM 2016-2021, CIKM 2017 (Short papers), AAAI 2018, 2022 PAKDD 2018, 2019, SIGIR 2021, KDD 2021-2022, Neurips 2022
  
# Teaching
- 2022 (Autumn) iOS Deveploment for Intelligent Applications
- 2022 (Spring) Introduction to Algorithm Design and Analysis Videos
- 2021 (Autumn) iOS Deveploment for Intelligent Applications
- 2021 (Spring) Introduction to Algorithm Design and Analysis
- 2020 (Spring) Introduction to Algorithm Design and Analysis
- 2019 (Spring) Introduction to Algorithm Design and Analysis
- 2018 (Spring) Introduction to Algorithm Design and Analysis 
  
# Projects
- [WSNs based Human Activity Recognition System]
  -A real-time AR system that built in Department of Computer Science & Technology, Nanjing University.

# Resources
- [The proof that the derivative of Eq. (12) is Lipschitz continuous in our TKDE submission](https://cs.nju.edu.cn/ics/people/jingweixu/static/proof.pdf)
- [Another implimentation for our KDD paper](https://github.com/ParagonLight/hoorays)