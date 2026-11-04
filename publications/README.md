# 📰 Academic Publications

This section features my research in blockchain technology and retrieval-augmented generation (RAG).  
The work includes both implementation and evaluation of AI and secure systems.

---

## ✅ Published Papers

### 🔗 A Web Application for Data Exchange Blockchain Platform  
*2023 BdKCSE Conference*  
[DOI: 10.1109/BdKCSE59280.2023.10339770](https://doi.org/10.1109/BdKCSE59280.2023.10339770)

<details>
<summary><strong>Abstract</strong></summary>

The paper presents a web application for smart crop production data exchange, integrating the Antelope blockchain and the Interplanetary File System (IPFS). Using smart contracts, the platform enables secure data storage, file sharing, and token transfers, ensuring transaction transparency and security. Designed with open-source solutions, it allows authentication via blockchain accounts or standard wallets like Anchor. Future development focuses on performance, scalability, and security testing to evolve the platform into a fully decentralized application (dApp).
</details>

---

### 🔗 Towards Blockchain Wallets Classification and Implementation  
*2023 ICAI Conference*  
[DOI: 10.1109/ICAI58806.2023.10339101](https://doi.org/10.1109/ICAI58806.2023.10339101)

<details>
<summary><strong>Abstract</strong></summary>

The paper explores the key components and classification of blockchain wallets, proposing an extended working definition to support custom wallet solutions. It presents the development of a non-custodial, software hot wallet for Antelope/IPFS-based data exchange, supporting ERC-20 and ERC-721 tokens/NFTs with biometric authentication. The study outlines the wallet’s functionalities for account management, token transfers, and file exchange authentication, extending the platform’s infrastructure. Future development aims to evolve the solution into a web-based dApp wallet.
</details>

---

### 🔗 Web Application for Retrieval-Augmented Generation: Implementation and Testing  
*Electronics (MDPI), 2024*  
[DOI: 10.3390/electronics13071361](https://doi.org/10.3390/electronics13071361)

<details>
<summary><strong>Abstract</strong></summary>

The paper explores the implementation of Retrieval-Augmented Generation (RAG) technology with open-source large language models (LLMs). A dedicated web-based application, PaSSER, was developed, integrating Mistral:7b, Llama2:7b, and Orca2:7b models. The study evaluates LLM performance using METEOR, ROUGE, BLEU, perplexity, cosine similarity, Pearson correlation, and F1 score, particularly within the smart agriculture domain. Additionally, it examines hardware considerations, revealing that GPUs are essential for fast text generation. The paper also discusses blockchain integration for storing and managing assessment results, with future development focused on fine-tuning LLMs and further blockchain integration.
</details>

---

### 🔗 Similarity Thresholds in Retrieval-Augmented Generation  
*IEEE IS 2024*  
[DOI: 10.1109/IS61756.2024.10705214](https://doi.org/10.1109/IS61756.2024.10705214)

<details>
<summary><strong>Abstract</strong></summary>

The study evaluates the performance of open-source Large Language Models (LLMs)—Mistral:7b, Llama2:7b, and Orca2:7b—in the context of Retrieval-Augmented Generation (RAG). The research identifies optimal similarity score thresholds for LLMs using NLP metrics and a custom-developed dataset in agriculture. Tests were conducted using the PaSSER web-based application, an extension of the Smart Crop Production Data Exchange (SCPDx) platform. The findings show that different LLMs perform best at varying similarity thresholds, with Mistral and Llama excelling at 0.55, and Orca achieving peak performance at 0.65. Future development aims to integrate larger LLMs (40B+), explore fine-tuning strategies, and further enhance PaSSER’s infrastructure.
</details>

---

### 🔗 Retrieval-Augmented Generation: Advancements and Challenges  
*PROBLEMS OF ENGINEERING CYBERNETICS AND ROBOTICS • 2025 • Vol. 83, pp. 32-57*  
ISSN (Print): 2738-7356 | ISSN (Online): 2738-7364
[DOI: 10.7546/PECR.83.25.03](https://doi.org/10.7546/PECR.83.25.03)

<details>
<summary><strong>Abstract</strong></summary>

The growing reliance on Large Language Models (LLMs) in knowledge-intensive tasks has led to the rapid adoption of Retrieval-Augmented Generation (RAG) as a strategy for improving factual grounding and domain adaptability. This review traces the evolution of RAG systems, from their roots in Information Retrieval (IR) and early Natural Language Processing (NLP) to current modular architectures that support dynamic reasoning and real-time knowledge integration. It categorizes key frameworks according to the specific challenges they target – such as retrieval precision, hallucination reduction, domain specialization, and interpretability – and analyzes how each addresses recurring failure modes in real-world applications. Through a comparative lens, the paper highlights both the fragmented nature of current solutions and the need for more unified, self-aware designs. Evaluation frameworks, including RAGAS, RGB, and PaSSER, are discussed in light of these gaps. Based on this analysis, the review outlines core directions for future research, emphasizing the importance of real-time retrieval validation, sentence-level attribution, failure correction mechanisms, and adaptable query rewriting. The findings suggest that RAG research is entering a phase of consolidation, where system reliability, transparency, and domain robustness will define progress more than generative fluency alone.
</details>

---

### 🔗 PaSSER: A Platform for Evaluating LLMs in RAG
*IEEE, 2025*

<details>
<summary><strong>Abstract</strong></summary>

This paper describes PaSSER, an open-source platform designed for the evaluation of RAG. Current evaluation tools operate with fixed configurations. This restricts researchers' ability to study the impact of retrieval settings on model performance. PaSSER addresses this issue by enabling the systematic variation of retrieval parameters while ensuring reproducible results. The platform integrates three key components. A web-based interface supports both normal and score retrieval modes with configurable similarity thresholds. A computational backend aggregates eleven evaluation metrics into a weighted composite performance score. Blockchain-based logging ensures that parameter settings and results are immutable and can be verified independently. A controlled evaluation using the Mistral 7B model demonstrates the platform's capability. Two similarity thresholds (0.85 vs. 0.55) were compared on a domain-specific dataset. The evaluation reveals measurable differences between lexical precision and semantic breadth approaches. The scope of this paper is limited to demonstrating the functionality of the platform. Blockchain integration provides tamper-proof experimental records. This addresses the challenge of reproducibility in RAG research, where parameter variations can significantly impact results, yet are often inadequately documented. Future development will focus on automated parameter exploration, expanded metric libraries, additional model integrations, and multi-domain dataset management to support larger-scale comparative studies.
</details>

---

### 🔗 Multi-Agent Coordination Strategies vs Retrieval-Augmented Generation in LLMs: A Comparative Evaluation  
*Electronics (MDPI), 2025*  
[DOI: 10.3390/electronics14244883](https://doi.org/10.3390/electronics14244883)

<details>
<summary><strong>Abstract</strong></summary>

This paper evaluates multi-agent coordination strategies against single-agent retrieval-augmented generation (RAG) for open-source language models. Four coordination strategies (collaborative, sequential, competitive, hierarchical) were tested across Mistral 7B, Llama 3.1 8B, and Granite 3.2 8B using 100 domain-specific question–answer pairs (3100 total evaluations). Performance was assessed using Composite Performance Score (CPS) and Threshold-aware CPS (T-CPS), aggregating nine metrics spanning lexical, semantic, and linguistic dimensions. Under the tested conditions, all 28 multi-agent configurations showed degradation relative to single-agent baselines, ranging from −4.4% to −35.3%. Coordination overhead was identified as a primary contributing factor. Llama 3.1 8B tolerated Sequential and Hierarchical coordination with minimal degradation (−4.9% to −5.3%). Mistral 7B with shared context retrieval achieved comparable results. Granite 3.2 8B showed degradation of 14–35% across all strategies. Collaborative coordination exhibited the largest degradation across all models. Study limitations include evaluation on a single domain (agriculture), use of 7–8B parameter models, and homogeneous agent architectures. These findings suggest that single-agent RAG may be preferable for factual question-answering tasks in local deployment scenarios with computational constraints. Future research should explore larger models, heterogeneous agent teams, role-specific prompting, and advanced consensus mechanisms.
</details>

---

## 🎓 Doctoral Dissertation

### 🔗 Evaluation Framework of Retrieval-Augmented Generation
*PhD dissertation, Institute of Information and Communication Technologies (IICT), Bulgarian Academy of Sciences, 2026*
Bulgarian title: *Рамка за оценка на съдържание, генерирано с разширено извличане*

- [Full text (PDF, English)](https://iict.bas.bg/konkursi/2026/MDimitrova/02-disertatsia-za-doktor-EN.pdf)
- [Defense notice, abstract and reviews (IICT-BAS)](https://iict.bas.bg/ZRASRB-n-stepeni.html)

---

## 📝 Upcoming

### 🔜 Model-Dependent Similarity Thresholds in Retrieval-Augmented Generation  
*SPRINGER, Book Chapter 12*  


<details>
<summary><strong>Abstract (preview)</strong></summary>

The study investigates the impact of similarity threshold tuning on Retrieval-Augmented Generation (RAG) system performance across four open-source language models. Mistral 7B, Llama 3.1 8B, Granite 3.2 8B, and DeepSeek 8B were evaluated using 369 question-answer pairs from the agricultural domain. Similarity thresholds from 0.50 to 0.95 were systematically tested to identify model-specific optimal configurations. An enhanced Composite Performance Score (CPS) was employed, integrating eleven evaluation metrics spanning lexical overlap (METEOR, ROUGE-2.f, ROUGE-L.f), semantic similarity (BERTScore.f1, B-RT.average), fluency and accuracy (F1 score, B-RT.fluency), and language modeling (Laplace Perplexity, Lidstone Perplexity) dimensions into a unified, weighted scoring system. The framework was extended with a Threshold-Aware Composite Performance Score (T-CPS) that penalizes output variability to identify stable, high-performing configurations. Results revealed distinct model sensitivity patterns. Mistral 7B achieved statistical significance at six thresholds with peak improvement of 4.58%. Granite 3.2 8B demonstrated consistent performance across seven consecutive thresholds. Llama 3.1 8B showed selective response at three high thresholds. DeepSeek 8B exhibited limited sensitivity with significance at only two thresholds. Model-specific threshold calibration yielded performance improvements ranging from 1.01% to 4.58% without requiring architectural modifications or additional computational resources. These findings demonstrate that model-specific threshold calibration represents a practical enhancement strategy that can deliver measurable performance improvements without requiring architectural modifications or additional computational resources.



