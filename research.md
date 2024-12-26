---
title: " "
layout:  page
---

Currently, we are working on the following topics of AI with applications in healthcare, IIoT, and fusion energy. 

![Research Focus](research.png)

### 1. **Responsible AI**
AI is rapidly transforming industries and daily life, but it also raises serious concerns regarding data privacy, security, fairness, ethics, and copyright compliance. Addressing these challenges will help to foster trust and acceptance of AI technologies across various fields.

**(Personalized) Federated Learning**: Federated learning (FL) is a distributed machine learning paradigm that allows a network of devices (e.g., hospitals, smartphones, media streamers, and Internet of things nodes) to collaboratively learn a global shared AI model without explicitly sharing their local raw data with the server or other devices (i.e., strictly adhering to data regulations like GDPR). Unlike traditional FL, which learns a single AI model, our focus is on developing personalized AI models tailored to specific subgroups of the population while maintaining GDPR compliance.

**Security and Privacy in Federated Learning**: Although FL claims to be privacy-preserving, it is still vulnerable to various attacks (e.g., model inversion attacks). An adversary can potentially infer sensitive training data from the model updates collected during the learning process, posing a risk to data privacy. Our goal is to mitigate these risks of data inference from trained AI models and ensuring that the learning process remains secure and fully compliant with data privacy regulations.

**Machine Unlearning**: To protect individual's privacy, authorities have enacted stringent regulations like the GDPR, which includes the right to be forgotten provision, and the AI Act that empower individuals to have control over their data. However, AI models' capacity to memorize training data poses significant challenges in complying with data regulations, as these models can inadvertently reveal details about the original data. Therefore, to protect individuals' privacy, we aim to delete the knowledge acquired by the AI model from those specific data samples (i.e., the data samples requested for deletion).

**Fairness-Concious AI**: Fairness in AI is crucial because AI systems are increasingly being used in decision-making processes that impact people's lives. However, traditional AI models often exhibit discriminatory decisions (i.e., decisions that disadvantage certain groups or individuals) due to biased data, fairness-agnostic algorithms, and a lack of diversity in training datasets. Therefore, our objective is to develop novel AI models that  promote fairness thereby benefitting all people without perpetuating existing social inequities.

### 2. **Next-Gen AI**
**Self-Supervised Learning (SSL)**: In general, acquiring labeled data is expensive and time-consuming in almost every field, while unlabeled data is abundant. SSL leverages this vast pool of unlabeled data to train AI models, reducing the dependency on large labeled datasets. We are currently utilizing SSL in healthcare applications, where expert annotations are limited. 

- **Continual Learning**: Enabling AI models to adapt and learn continuously from new data.
- **Meta Learning**: Developing AI models that can adapt swiftly to new tasks.

### 3. **AI in Healthcare and Industrial Applications**
- **AI for Healthcare**: Applying advanced AI techniques to improve outcomes in healthcare, including diagnostics and personalized treatment.
- **AI for IIoT (Industrial Internet of Things)**: Enhancing automation and decision-making in industrial settings through AI models that process large-scale sensor data.

### 4. **Physics-Informed AI and Advanced Models**
- **Physics-Informed Neural Networks**: Integrating physical laws into neural networks for more accurate predictions in complex systems like energy or medical simulations.
- **AI for Fusion Energy**: Leveraging AI models, particularly, PINNs to forecast fuel-ion ratio. 
