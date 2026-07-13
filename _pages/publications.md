---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{ author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!--
* Shengwei An*, __Lu Yan*__, Siyuan Cheng, Guangyu Shen, Kaiyuan Zhang, Qiuling Xu, Guanhong Tao, Xiangyu Zhang, 2024. Rethinking the Invisible Protection against Unauthorized Image Usage in Stable Diffusion. In Proceedings of the 33rd USENIX Security Symposium (USENIX Security 2024) 
* __Lu Yan__, Siyuan Cheng, Guangyu Shen, Guanhong Tao, Xuan Chen, Kaiyuan Zhang, Yunshu Mao, and Xiangyu Zhang, 2023. $D^3$: Detoxing Deep Learning Dataset. In Proceedings of 37th Conference on Neural Information Processing Systems (Backdoors in Deep Learning @ NeurIPS 2023)
* __Lu Yan__, Zhuo Zhang, Guanhong Tao, Kaiyuan Zhang, Xuan Chen, Guangyu Shen and Xiangyu Zhang, 2023. ParaFuzz: An Interpretability-Driven Technique for Detecting Poisoned Samples in NLP. In Proceedings of 37th Conference on Neural Information Processing Systems (NeurIPS 2023)
* Shin Hwei Tan, Ziqiang Li, and __Lu Yan__ (2023). CrossFix: Resolution of GitHub issues via similar bug recommendations. Journal of Software: Evolution and Process, e2554.
* Dongdong She, Rahul Krishna, __Lu Yan__, Suman Jana, and Bashakhi Ray (2020). MTFuzz: fuzzing with a multi-task neural network. In Proceedings of the 28th ACM joint meeting on European software engineering conference and symposium on the foundations of software engineering (ESEC/FSE).
* Jie Li, Lu Zhou, Huaxin Li, __Lu Yan__, and Haojin Zhu (2019, June). Dynamic traffic feature camouflaging via generative adversarial networks. In 2019 IEEE Conference on Communications and Network Security (CNS) (pp. 268-276). IEEE.
-->
