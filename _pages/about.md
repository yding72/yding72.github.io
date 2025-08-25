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
<!-- , advised by [Prof. Luana Ruiz](https://luanaruiz9.github.io/).  -->
I am a M.S.E. Student in [Data Science of AMS](https://engineering.jhu.edu/ams/academics/graduate-studies/ms-in-data-science/) (Department of Applied Mathematics and Statistics) at the Whiting School of Engineering, Johns Hopkins University, advised by [Prof. Luana Ruiz](https://luanaruiz9.github.io/). . My primary interests lie in Graph Neural Networks (GNN) and Large Language Models (LLMs). I have hands-on experience with **Python, TensorFlow, and PyTorch**, and have worked on several projects involving **Time Series Analysis, LLMs and GNNs**.

# 📖 Education
- *Sep 2023 - May 2025 *, M.S.E. in Data Science, Johns Hopkins University, Baltimore, MD, U.S.A.
- *Sep 2018 - June 2023*, Bachelor in Data Science, Drexel University, Philadelphia, PA, U.S.A. \* 
- *Sep 2018 - June 2022*, Bachelor in Computer Science, Lanzhou University, Gansu, China \* 

\* I participated in a joint cooperative program and hold bachelor's degrees from both Lanzhou University and Drexel University

# 💻 Work Experience
<h2><strong>Health-Union, LLC</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>Philadelphia, PA</em></span></h2>
**Sep 2022 - Mar 2023** | *Data Co-op*
- Responsible for data management and data acquisition using Snowflake.
- Conducted data monitoring, identified the cause of abnormal data, and found corresponding solutions.
- Applied **Temporal Convolutional Network (TCN)** models to accurately predict the click-through rates on the Health-Union website, enhancing both model performance and predictive precision.

<h2><strong>AchievAI Technology Co., Ltd.</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>Guangdong, China</em></span></h2>
**Dec 2020 - Sep 2022** | *Python Programmer (90% remote)*
- Developed algorithms for image processing and machine learning, successfully extracting precise annual ring data from noisy wood texture images, enhancing accuracy and robustness.
- Conducted research on generating high-quality wood texture images with GANs.
- Developed a Python plugin on Linux for converting 3D wood models (.stl) to high-resolution .tiff images, significantly enhancing plugin functionality.

<h2><strong>Newland Digital Technology Co., Ltd.</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>Fujian, China</em></span></h2>
**Aug 2020 - Sep 2020** | *Python Programmer*
- Conducted market research on community security systems, integrating big data analysis to produce a comprehensive report.
- Developed Python web crawlers using Requests and Beautiful Soup, processing data from over 1,000 web pages for efficient data collection and storage.
- Implemented automated anti-scraping techniques, including user behavior simulation and dynamic IP proxy, improving data extraction accuracy and stability.


# 🎖 Technical Skills
- **Language**: Python, C, SQL, Matlab, R, JavaScript, PHP, Bash, Lisp
- **Frameworks**: PyTorch, Tensorflow, LangChain, Scikit-learn, OpenCV, NetworkX, Selenium
- **Deep Learning Models**: LLMs, GRNNs, Graph Transformer, GAN, ResNet, TCN, LSTM
- **Machine Learning**: upport Vector Machines, Naive Bayes, Decision trees, Logistic Regression

# 📝 Publications 
<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
-->
<!--- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->
- <u>Earthquake Magnitude Estimation Using Gated Graph Recurrent Neural Networks</u>, <em><strong>Yantian Ding</strong>, Luana Ruiz</em>, **ICASSP 2025** (Under Review)
- <u>HIV-AICare: A Domain Knowledge-guided Reinforcement Learning Approach for Optimizing Antiretroviral Therapy in People with HIV</u>, *Dapeng Yao, Wei Jin, Yao Zhao, Luis Parra-Rodriguez, Jane O'Halloran, Raha Dastgheyb, Zhengling Qi, <strong><em>Yantian Ding</em></strong>, David B. Hanna, Andrea Norcini-Pala, Amanda B. Spence*..., **Nature Medicine** (Under Review)
- <u>Phonocardiogram(PCG) Murmur Detection Based on the Mean Teacher Method</u>, *Yi Luo, Zuoming Fu, <strong><em>Yantian Ding</em></strong>, Xiaojian Chen, Vishal Patel, Kai Ding*, **Sensors** (accepted)
- <u>Ground Based-cloud Classification based on Comparing Different Classification Models</u>, *Tao Zhang, <strong><em>Yantian Ding</em></strong>, Wangjiang Gong, Zeyu Hou*, **CONF-CDS 2022**


# 🎙 Research Projects

<h2><u><strong>HIV-AICare Web Chatbot and Website Development</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**May 2024 – Current** | *Advised by [Prof. Yanxun Xu](https://engineering.jhu.edu/faculty/yanxun-xu/)*
- **Co-author** of the paper "*HIV-AICare: A Domain Knowledge-guided Reinforcement Learning Approach for Optimizing Antiretroviral Therapy in People with HIV*" (Under Review).
- Developed a chatbot for the HIV-AICare website based on **MedAlpaca and RAG** technologies, assisting users in interpreting web model calculation results and navigating the platform, significantly enhancing user engagement and system intelligence.
- Scripted in Python to efficiently gather and process necessary data for the project, leveraging Selenium to automate interactions with web pages.

<h2><u><strong>Earthquake Dataset for Graph Neural Network</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**Oct 2023 - Current** | *Advised by [Prof. Luana Ruiz](https://luanaruiz9.github.io/)*
- **First-author** of the parer "*Earthquake Magnitude Estimation Using Gated Graph Recurrent Neural Networks*" (Under Review).
- Built and optimized a seismic time series dataset (approximately 295GB) from New Zealand's GeoNet, and simultaneously designed and implemented preprocessing workflows, including data cleaning, graph structure construction, and data format conversion, ensuring compliance with the input requirements of GRNN models.
- **Refactored GRNN code** using PyTorch Geometric (PyG), significantly improving performance and efficiency, achieving a roughly 20\% increase in accuracy compared to traditional *Graph Transformer*.

<h2><strong>CALEX Extraction System</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>Graduation Design in Drexel University</em></span></h2>
**Sep 2022 - Jun 2023** | *Advised by [Prof. Hegler Tissot](https://drexel.edu/cci/about/directory/T/Tissot-Hegler/)*
- Managed the development and coding of the four-layer CALEX Extraction System, enhancing the processing of natural language texts for temporal data annotation.
- Assisted in dataset annotation, focusing on accuracy and efficiency to support applications in various domains.
- Utilized rule-based programming to standardize temporal expressions, improving the system’s scalability and reliability across its four layers.

<h2><strong>Traffic Accident Prediction based on Neural Network</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>Graduation Design in Lanzhou University</em></span></h2>
**Dec 2021 - Jun 2022** | *Advised by [Prof. Longjie Li](https://ljlilzu.github.io/)*
- Built a Graph Residual Neural Network incorporating an Attention Mechanisms model with a prediction accuracy of 92.42% on unseen data.
- Collected and collated accident data, speed data, and road data from NYC Open Data, NOAA, Uber Movement, and Open Street Map in Brooklyn.
- Developed a traffic accident severity forecasting model for the Brooklyn area with Python.

<h2><strong>Ground Based-cloud Classification based on Comparing Different Classification Models</strong></h2>
**May 2021 - Aug 2021** | *Advised by [Prof. David Woodruff](https://www.cs.cmu.edu/~dwoodruf/)*
- **Co-first-author** of the paper "*Ground Based-cloud Classification based on Comparing Different Classification Models*". Lecture Notes on *Data Engineering and Communications Technologies book series (CONF-CDS 2022)*. Accepted in March 2022.
- Preprocessed around 15,000 cloud images in 5 types in the same format and pixels using LBP.
- Implemented four classification models—KSVM, MLP, Custom Vision and ResNet to compare each classification’s accuracy.

<h2><strong>Raspberry Pi-Based Facial Recognition System</strong></h2>
**July 2020 - Apr 2021** | *Advised by [Prof. Qiming Liu](https://mat.lzu.edu.cn/shiziduiwu/jiaoshiduiwu/fujiaoshou/2021/0926/180670.html)*
- Designed a smaller facial recognition machine system, equipped with a trained face recognition algorithm.
- Developed a well-trained machine learning model with high accuracy and response speed.
- Built and debugged for the Raspberry Pi hardware system.

# 🏆 Honors and Awards
- A.J. Drexel Scholarship, Fall 2021
- Overseas Exchange Scholarship, Lanzhou University, 2021
- Overseas Exchange Scholarship, Lanzhou University, 2022



