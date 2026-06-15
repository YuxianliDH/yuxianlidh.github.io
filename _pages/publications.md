---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### Conference Papers
 * [ACISP'26] Pengfei Wu, **Yuxian Li**(co-first author), Lisha Yao, Xiaoguo Li, Guomin Yang, Tao Xiang, Robert H. Deng, "Understanding the Security of Cloud Storage Services: A Case Study and UC-Secure Design."
 * [ESORIC'25]Jianfei Sun, **Li Yuxian**(corresponding author), Xuehuan Yang, Guomin Yang, Robert Deng, "An efficient security-enhanced accountable access control fornamed data networkingnamed data networking."

 * [FC’25] Ming Li, **Li Yuxian**(corresponding author), Jian Weng, Yingjiu Li, Jiasi Weng, Junzuo Lai, RobertH Deng, “IvyAPC: Auditable Generalized Payment Chan‑
nels.”


### Journal Papers
* [TDSC'26] **Yuxian Li**, Xiaoguo Li, Guomin Yang, Haoxin Tu, Jianfei Sun, and Robert H. Deng, "MISC: Flexible Data Management for Private Smart Contract".
* [TIFS’25] **Li Yuxian**, Jian Weng, Junzuo Lai, Yingjiu Li, Jianfei Sun, Jiahe Wu, Ming Li, Pengfei Wu, Robert H Deng, “AuditPCH: Auditable
payment channel hub with privacy protection.''
* [JPDC 2023]  **Li Yuxian**, Weng Jian, Wu Wei, Li Ming, Li Yingjiu, Haoxin Tu, Wu Yongdong, and Robert. H. Deng, “PRI: PCH‑based privacy‑
preserving with reusability and interoperability for enhancing blockchain scalability”, in Journal of Parallel and Distributed Comput‑
ing. **Citation count**: 4.
* [JPDC 2022]  **Yuxian Li**, Weng Jian, Li Ming, Wu Wei, Weng Jiasi, Liu Jia‑nan, and Hu Shun, “ZeroCross: A sidechain‑based privacy‑
preserving cross‑chain solution for Monero”, in Journal of Parallel and Distributed Computing. **Citation count**: 42.

 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
