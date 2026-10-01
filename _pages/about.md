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

# Welcome!

My research focuses on developing computational methods to transform health data into trustworthy and clinically meaningful evidence for clinical decision-making support. Currently, I work as a research engineer at the Royal Melbourne Hospital, dedicated to improving the quality of hospital care for patients with dementia. 

# 📝 Recent Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2026</div><img src='images/femr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[X-FEMR: A Token-level Explainable Approach for Electronic Health Records Foundation Models using Transformer-based Models](https://doi.org/10.48550/arXiv.2607.06163)

- Foundation Models for Electronic Health Records (FEMRs) are pretrained on large-scale structured patient data, enabling them to convert longitudinal patient trajectories into generalizable representations for diverse clinical prediction tasks. Despite their effectiveness, FEMRs remain black-box models, raising concerns about bias, interpretability, and clinical trust. To address this, we propose the first token-level explainability approach for FEMRs. We train a Transformer-based surrogate model on input-output pairs from the FEMR across two prediction tasks, approximating its behavior while preserving temporal dynamics. We identify the most influential tokens, providing insights into how FEMRs leverage different aspects of patient history for predictions. To evaluate clinical relevance, we introduce a novel clinical alignment metric that quantifies the correspondence between the surrogate model’s key tokens and clinically validated features. Our results demonstrate that the surrogate closely approximates FEMR predictions and that token-level explanations align well with clinical knowledge, offering a practical framework for interpretable and trustworthy clinical AI.

**Reference:** Huang, J.<sup>†</sup>, **Yin, P.<sup>†</sup>**, Xu, Z., Capurro, D., Conway, M., & Dang, T. (2026). X-FEMR: A Token-level Explainable Approach for Electronic Health Records Foundation Models using Transformer-based Models. arXiv preprint arXiv:2607.06163. <br><sup>†</sup> *These authors contributed equally.* Accepted by **In Proceedings of International Joint Conferences on Artificial Intelligence(IJCAI 2026)**(AI and Health Special Track, Accept Rate:18%)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JBI 2025</div><img src='images/measuring.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Measuring and Visualizing Healthcare Process Variability](https://pubmed.ncbi.nlm.nih.gov/40998279/)

- Understanding factors that contribute to clinical variability in patient care is critical, as unwarranted variability can lead to increased adverse events and prolonged hospital stays. Determining when this variability becomes excessive can be a step in optimizing patient outcomes and healthcare efficiency. In this study, we presents a standardized way to measure and visualize variability in clinical processes and measure its impact on patient-relevant outcomes.

**Reference:** **Yin, P.**, Cervantes, A. A., & Capurro, D. (2025). Measuring and visualizing healthcare process variability. **Journal of biomedical informatics**, 104918. Advance online publication. https://doi.org/10.1016/j.jbi.2025.104918 
</div>
</div>


# Journal Review
**[Nature Communications Health](https://www.nature.com/commshealth/)**<br>
Journal of Biomedical Informatics<br>
Discover Artificial Intelligence<br>
Frontiers in Cardiovascular Medicine<br>
BMC Medical Genomics<br>
and others<br>
     
# Conference Review
**NeurIPS** 2026 Workshop on Agents in the Wild<br>
**ICML** 2026 Workshop on Agents in the Wild<br>
**CVPR** 2026 Workshop Multi-Modal Reasoning for Agentic Intelligence(MMRAgI)<br>
**ICLR** 2026 Workshop AIWILD and ES-Reasoning<br>
American Medical Informatics Association Annual Symposium(AMIA) 2023<br> 
and others<br>

