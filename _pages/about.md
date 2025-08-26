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
I recently graduated with an M.S.E. Student in [Data Science of AMS](https://engineering.jhu.edu/ams/academics/graduate-studies/ms-in-data-science/) from Johns Hopkins University in May 2025. My academic and professional background spans **Large Language Models (LLMs)**, **Graph Neural Networks (GNNs)**, and **Time Series Analysis**, with published and under-review research in top AI venues. I have hands-on experience with **Python, JavaScript, R, PyTorch, TensorFlow, LangChain, Flask, React, and MySQL**, and have applied these skills in projects ranging from **retrieval-augmented generation (LMAR), Kaplan-Meier survival curve reconstruction, and PCG murmur detection** to **full-stack AI-powered CRM automation**.

**I am now actively seeking full-time opportunities in LLMs, AI, Machine Learning, and Data Science**, where I can contribute to developing, deploying, and scaling intelligent systems for real-world applications. I am particularly interested in roles involving **LLMs, GNNs, multimodal AI, and applied machine learning for healthcare and finance**. Please feel free to connect with me via email for potential collaborations or job opportunities.
# 📖 Education
- *Sep 2023 - May 2025*, M.S.E. in Data Science, Johns Hopkins University, Baltimore, MD, U.S.A.
- *Sep 2018 - June 2023*, Bachelor in Data Science, Drexel University, Philadelphia, PA, U.S.A. \* 
- *Sep 2018 - June 2022*, Bachelor in Computer Science, Lanzhou University, Gansu, China \* 

\* I participated in a joint cooperative program and hold bachelor's degrees from both Lanzhou University and Drexel University

# 💻 Work Experience
<h2><strong>ComppInc.</strong> | <span style="font-weight: normal; font-size: 0.9em;"><em>San Francisco, CA</em></span></h2>
**Sep 2022 - Mar 2023** | *Full-Stack Developer*
- Built a full-stack web application that enables natural language control over Salesforce API operations, powered by **OpenAI Assistant API** and advanced tool calling logic.
- Developed the backend using Flask, integrated **LLM function calling**, streaming responses, and contextual memory; deployed on **GCP with Gunicorn + Nginx (HTTPS)**.
- Built a responsive **React** frontend supporting real-time chat and threaded memory; integrated MySQL for session history, tool records, and user management.
- Delivered a working Beta at [agent.compp.io](https://agent.compp.io), supporting CRM automation such as lead management, forecast queries, and opportunity updates.

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
- **Language**: Python, JavaScript, R, SQL, Matlab, PHP, Bash, C
- **Frameworks**: OpenAI Assistants and Function Calling, LangChain, PyTorch, Tensorflow, React, Scikit-learn, Tesseract OCR, Flask, Selenium
- **Deep Learning Models**: LLMs, GRNNs, Graph Transformer, GAN, ResNet, TCN, LSTM
- **Machine Learning**: Support Vector Machines, Naive Bayes, Decision trees, Logistic Regression

# 🎙 Research Projects
<h2><u><strong>LMAR</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**Sep 2024 – Current** | *Advised by [Prof. Yanxun Xu](https://engineering.jhu.edu/faculty/yanxun-xu/)*
- **Co-author** of the parer "*LMAR: Language Model Augmented Retriever for Domain-specific Knowledge Indexing*" [Under Review] AAAI Conference on Artificial Intelligence (AAAI), 2025.
- Developed LMAR, a model-agnostic retrieval framework that integrates LLM-guided contrastive training, semantic clustering, and synthetic QA supervision, significantly improving domain-specific information retrieval performance with low computational cost.- Scripted in Python to efficiently gather and process necessary data for the project, leveraging Selenium to automate interactions with web pages.
- Designed and implemented a two-stage pipeline that jointly refines embeddings and chunking using LLM-based triplet supervision and question-evidence pair generation, achieving state-of-the-art results on WikiQA, TechQA, and PubMedQA while remaining deployable on commodity GPUs

<h2><u><strong>KM-plot GPT</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**May 2025 – Current** | *Advised by [Prof. Yanxun Xu](https://engineering.jhu.edu/faculty/yanxun-xu/)*
- **Co-First-author** of the parer "*From Pixels to Patients: Automated IPD Reconstruction from Kaplan-Meier Figures Using Multi-Modal AI*".
- Developed an end-to-end pipeline to reconstruct Kaplan-Meier survival curves from image-only plots using LLM, Tesseract OCR, Python and R (via rpy2).
- Extracted axis values and risk tables from plot images using GPT-enhanced OCR; digitized survival curves using SurvdigitizeR, and reconstructed individual patient data (IPD) by aligning with clinical tables via *IPDfromKM*.
- Built a real-time Flask web service that integrates image super-resolution and denoising to enhance OCR accuracy, and implements optimal curve-to-table matching logic for survival curve reconstruction.

<h2><u><strong>HIV-AICare Web Chatbot and Website Development</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**May 2024 – Current** | *Advised by [Prof. Yanxun Xu](https://engineering.jhu.edu/faculty/yanxun-xu/)*
- **Co-author** of the paper "*HIV-AICare: A Domain Knowledge-guided Reinforcement Learning Approach for Optimizing Antiretroviral Therapy in People with HIV*".
- Developed an intelligent chatbot for the HIV-AICare platform using **Llama 3.1 8b** and **Multi-Agent** to enhance user comprehension and streamline platform navigation.
- Contributed to the development and implementation of the [HIV-AICare](https://hiv-aicare.wse.jhu.edu/) website, focusing on creating an intuitive user interface and ensuring seamless integration with backend systems to enhance platform usability and accessibility.

<h2><u><strong>Earthquake Dataset for Graph Neural Network</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**Oct 2023 - Current** | *Advised by [Prof. Luana Ruiz](https://luanaruiz9.github.io/)*
- **First-author** of the parer "*Earthquake Magnitude Estimation Using Gated Graph Recurrent Neural Networks*".
- Built and optimized a seismic time series dataset (approximately 295GB) from New Zealand's GeoNet, and simultaneously designed and implemented preprocessing workflows, including data cleaning, graph structure construction, and data format conversion, ensuring compliance with the input requirements of GRNN models.
- **Refactored GRNN code** using PyTorch Geometric (PyG), significantly improving performance and efficiency, achieving a roughly 20\% increase in accuracy compared to traditional *Graph Transformer*.

<h2><u><strong>PCGMurmurDetection via Mean Teacher Learning</strong></u> | <span style="font-weight: normal; font-size: 0.9em;"><em>Research in Johns Hopkins University</em></span></h2>
**Oct 2023 - Current** | *Advised by [Prof. Ding Kai](https://dinglab.jh.edu/)*
- **Co-author** of the parer "*Phonocardiogram (PCG) Murmur Detection Based on the Mean Teacher Method*".
- Developed a semi-supervised murmur detection system using the Mean Teacher framework on PC audio, integrating labeled (PhysioNet 2022) and unlabeled (PhysioNet 2016-e) datasets to improve generalization in low-resource clinical scenarios.
- Designed a lightweight CNN-based classifier combining Mel-spectrograms and demographic features; achieved state-of-the-art performance (Murmur Score 0.818, AUC 0.9004) with robust data augmentation and subject-wise cross-validation.

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

