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

I am a PhD student in the School of Computing and Information Systems at the [University of Melbourne](https://www.unimelb.edu.au), specializing in **Clinical Data Science**. My research involves the application of **Artificial Intelligence(AI)** and **Process Mining** within clinical settings to improve patient care and outcomes. I’m really passionate about **Computer Science** and **Biomedical Informatics**, and I love using new technology to make healthcare better for everyone. Currently,I focus on designing scalable data pipelines to measure and visualize variability in healthcare processes. I am supervised by [A/Prof Daniel Capurro Nario](https://findanexpert.unimelb.edu.au/profile/852679-daniel-capurro-nario) from [Center for Digital Transformation of Health](https://mdhs.unimelb.edu.au/digitalhealth) and [Dr.Abel Armas Cervantes](https://findanexpert.unimelb.edu.au/profile/822941-abel-armas-cervantes) from the School of Computing and Information Systems at the University of Melbourne.




# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BIBM 2023</div><img src='images/parsing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Parsing Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model](https://pmc.ncbi.nlm.nih.gov/articles/PMC11251129/pdf/nihms-2007993.pdf)

- To enable electronic screening of eligible patients for clinical trials, free-text clinical trial eligibility criteria should be translated to a computable format. **Natural Language Processing (NLP)** techniques have the potential to automate this process. In this study, we explored a supervised multi-input multi-output (MIMO) sequence labelling model to parse eligibility criteria into combinations of fact and condition tuples. Our experiments on a small manually annotated training dataset showed that that the performance of the MIMO framework with a BERT-based encoder using all the input sequences achieved an overall lenient-level AUROC of 0.61.
- This study was funded in part by the National Institutes of Health (NIH) through awards: R21 AG068717 and R21 CA253394.

**Reference:** Tian, S., **Yin, P.**, Zhang, H., Erdengasileng, A., Bian, J., & He, Z. (BIBM 2023). Parsing Clinical Trial Eligibility Criteria for Cohort Query by a Multi-Input Multi-Output Sequence Labeling Model.2023 **IEEE International Conference on Bioinformatics and Biomedicine (BIBM)**, Istanbul, Turkiye, pp. 4426-4430 
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AMIA 2021</div><img src='images/socialdata.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Data and Model Biases in Social Media Analyses: A Case Study of COVID-19 Tweets](https://pmc.ncbi.nlm.nih.gov/articles/PMC8861742/pdf/3577200.pdf)

- During the coronavirus disease pandemic (COVID-19), social media platforms such as Twitter have become a venue for individuals, health professionals, and government agencies to share COVID-19 information. Twitter has been a popular source of data for researchers, especially for public health studies. However, the use of Twitter data for research also has drawbacks and barriers. Biases appear everywhere from data collection methods to modeling approaches, and those biases have not been systematically assessed. In this study, we examined six different data collection methods and three different **Machine Learning (ML)** models-commonly used in social media analysis-to assess data collection bias and measure ML models’ sensitivity to data collection bias. We showed that (1) publicly available Twitter data collection endpoints with appropriate strategies can collect data that is reasonably representative of the Twitter universe; and (2) careful examinations of ML models’ sensitivity to data collection bias are critical.
- This work was supported in part by NSF Award #1734134

**Reference:** Zhao, Y., **Yin, P.**, Li, Y., He, X., Du, J., Tao, C., Guo, Y., Prosperi, M., Veltri, P., Wu, Y., & Bian, J. (AMIA 2021). Data and Model Biases in Social Media Analyses: A Case Study of COVID-19 Tweets. **American Medical Informatics Association Annual Symposium - Computing Research and Education Association of Australasia (CORE) Ranking A**
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SEPDA 2021</div><img src='images/graphdatabase.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Formal Computable Representation of Clinical Trial Eligibility Criteria for Alzheimer's Disease ](https://www.medrxiv.org/content/10.1101/2022.03.21.22272707v1.full.pdf)

- Ambiguity and misunderstanding of free-text clinical trial eligibility can affect the accuracy of translating trial investigators’ mental model of the study population to the correct cohort identification queries. In this pilot study, to eliminate the ambiguity when parsing eligibility criteria, we built ontology-based representations to standardize clinical trial eligibility criteria. We analyzed 10 Alzheimer’s disease (AD) trials' eligibility criteria and categorized them into general query patterns using an annotation schema borrowed from the literature on constructing knowledge graphs. Then, for each pattern, we built the corresponding ontological representations, linked them to **real-word electronic health record (EHR) data**, and constructed cohort identification queries using the **Neo4j graph database**. Our evaluation results of these cohort queries verified the accuracy of our ontology representation; and interestingly, we found that graph-queries achieved better runtime performance for complex study traits. 
- This study is funded in part by the National Insulites of Health (NIH) through awards: R21 AG068717 and R21 CA253394.

**Reference:** **Yin, P.**, Zhang, H., He, X., Diller, M., Li, Q., Tian, S., Erdengasileng, A., He, Z., Tao, C., & Bian, J. (SEPDA 2021). Towards Formal Computable Representation of Clinical Trial Eligibility Criteria for Alzheimer’s Disease. The 6th International Workshop on Semantics-Powered Health Data Analytics. 
</div>
</div>

# 🎉 News
- *2023.04*: &nbsp; Invited to serve as a reviewer for the 2023 American Medical Informatics Association Annual Symposium(AMIA). 

# 📖 Educations
- *2024.03 - (now)*, Doctor of Philosophy in Engineering and IT , [University of Melbourne](https://www.unimelb.edu.au), Australia. 
- *2021.08 - 2023.05*, Master of Science in Biomedical Informatics , [University of Florida](https://www.ufl.edu)(GPA:3.8/4.0), United States.
- *2019.08 - 2021.05*, Master of Science in Electrical and Computer Engineering , [University of Florida](https://www.ufl.edu)(GPA:3.8/4.0), United States.

