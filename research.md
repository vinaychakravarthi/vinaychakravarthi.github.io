entia---
title: " "
layout:  page
---

Currently, we are working on the following topics of AI with applications in healthcare, IIoT, and fusion energy. 

![Research Focus](research.png)

### 1. **Responsible AI**
AI is rapidly transforming industries and daily life, but it also raises serious concerns regarding data privacy, security, fairness, ethics, and copyright compliance. Addressing these challenges will help to foster trust and acceptance of AI technologies across various fields. We are making following efforts towards Responsible AI.

**(Personalized) Federated Learning**: Federated learning (FL) is a distributed machine learning paradigm that allows a network of devices (e.g., hospitals, smartphones, media streamers, and Internet of things nodes) to collaboratively learn a global shared AI model without explicitly sharing their local raw data with the server or other devices (i.e., strictly adhering to data regulations like GDPR). Unlike traditional FL, which learns a single AI model, our focus is on developing personalized AI models tailored to specific subgroups of the population while maintaining GDPR compliance.

**Security and Privacy in Federated Learning**: Although FL claims to be privacy-preserving, it is still vulnerable to various attacks (e.g., model inversion attacks). An adversary can potentially infer sensitive training data from the model updates collected during the learning process, posing a risk to data privacy. Our goal is to mitigate these risks of data inference from trained AI models and ensuring that the learning process remains secure and fully compliant with data privacy regulations.

**Machine Unlearning**: To protect individual's privacy, authorities have enacted stringent regulations like the GDPR, which includes the right to be forgotten provision, and the AI Act that empower individuals to have control over their data. However, AI models' capacity to memorize training data poses significant challenges in complying with data regulations, as these models can inadvertently reveal details about the original data. Therefore, to protect individuals' privacy, we aim to delete the knowledge acquired by the AI model from those specific data samples (i.e., the data samples requested for deletion).

**Fairness-Concious AI**: Fairness in AI is crucial because AI systems are increasingly being used in decision-making processes that impact people's lives. However, traditional AI models often exhibit discriminatory decisions (i.e., decisions that disadvantage certain groups or individuals) due to biased data, fairness-agnostic algorithms, and a lack of diversity in training datasets. Therefore, our objective is to develop novel AI models that  promote fairness thereby benefitting all people without perpetuating existing social inequities.

### 2. **Next-Gen AI**
In the rapidly evolving field of AI, advanced techniques are essential for addressing complex, real-world challenges, such as handling dynamic and often limited data sources, adapting to new environments, and making intelligent decisions in complex systems. To address these, we are delving into the following advanced AI methodologies, pushing the boundaries of what AI can achieve across a range of applications.

**Self-Supervised Learning (SSL)**: In general, acquiring labeled data is expensive and time-consuming in almost every field, while unlabeled data is abundant. SSL leverages this vast pool of unlabeled data to train AI models, reducing the dependency on large labeled datasets. We are currently utilizing SSL in healthcare applications, where expert annotations are limited. 

**Life-long Learning**: In real-world applications, data arrives progressively, and the distribution of this data can change over time. Life-long learning allows AI models to adapt to these changes without forgetting previously learned information, ensuring robustness and flexibility. We are currently implementing life-long learning in healthcare systems, enabling our models to improve over time as they encounter new patient data and treatment outcomes.

**Graph Machine Learning (GML)**: Many real-world systems are best represented as graphs, capturing the underlying relationships and interactions among entities (e.g., social networks, molecular structures). GML leverages this underlying geometric structure to improve predictive accuracy and insights. We are utilizing GML in biological networks to uncover insights into disease mechanisms, helping to identify potential therapeutic targets and understand complex biological processes.

**Quantum Machine Learning**: Very recently, we are also embarking on Quantum AI. Our recent work explores Efficient Hybrid Quantum Vision Transformers (ViTs), combining classical and quantum components. These models are designed to work within the limitations of today’s noisy and small-scale quantum hardware, while still pushing the frontier toward practical quantum advantage. 

### 3. **Applied AI**
We are applying the innovations in Responsible AI and Next-Gen AI to real-world domains like healthcare and fusion energy—to improve patient management and enhance the efficiency and stability of fusion energy systems, driving transformative change and creating meaningful impact in these critical areas.

**Colorectal Cancer**: Colon capsule endoscopy is a non-invasive imaging technique that allows for comprehensive examination of the colon. By leveraging advanced AI models, we aim to enhance the accuracy of polyp detection and characterization within CCE images, facilitating early diagnosis and improving patient outcomes.

**Cardio Calcification**: Calcification in coronary arteries is a critical indicator of cardiovascular disease and can lead to severe health complications. Detecting and quantifying calcification through imaging techniques is essential for assessing patient risk and planning appropriate interventions. We are developing AI-based methods to automatically identify and measure cardio calcification from medical images, improving the accuracy and efficiency of diagnosis and enabling timely medical responses.

**Dementia**: Alzheimer's is a common type of Demnetia. Early and accurate diagnosis of Alzheimer's disease is crucial for effective management and treatment. AI models can assist in identifying early signs of Alzheimer's by analyzing complex medical data like brain imaging. Our research is focused on developing advanced AI models to detect and predict the progression of Alzheimer's disease, enabling timely interventions and improving patient care. 


