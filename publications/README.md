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
[DOI: DOI: 10.7546/PECR.83.25.03](https://doi.org/10.7546/PECR.83.25.03)

<details>
<summary><strong>Abstract (preview)</strong></summary>

This paper reviews the evolution of Retrieval-Augmented Generation (RAG) systems, focusing on recent advancements that address the limitations of traditional language models. It explores modular RAG architectures, data-centric training strategies, and hybrid retrieval techniques that combine structured and unstructured knowledge. The study examines enhancements in factual grounding, domain specialization, and multimodal reasoning, while identifying key challenges such as retrieval precision, evidence alignment, and self-refinement. It also outlines emerging evaluation frameworks, including RAGAS, RGB, and PaSSER. The paper concludes with recommendations for future research, emphasizing the need for unified, trustworthy, and adaptable RAG systems.
</details>

---

### 🔗 Multi-Agent Coordination Strategies vs Retrieval-Augmented Generation in LLMs: A Comparative Evaluation  
*Electronics (MDPI), 2025*  
[DOI: 10.3390/electronics14244883](https://doi.org/10.3390/electronics14244883)

<details>
<summary><strong>Abstract</strong></summary>

This paper evaluates multi-agent coordination strategies against retrieval-augmented generation for 7-8B open-source models. Four coordination strategies (collaborative, sequential, competitive and hierarchical) were evaluated across three open-source models: Mistral 7B, Llama 3.1 8B and Granite 3.2 8B. The study determined whether multi-agent reasoning enhances retrieval-augmented generation performance. The evaluation employed 100 question-answer pairs. In total, 2,000 model-question evaluations were conducted. Performance was assessed using Composite Performance Score (CPS) and Threshold-aware Composite Performance Score (T-CPS), two metrics developed to aggregate nine dimensions spanning lexical overlap, semantic similarity, and linguistic quality. Results revealed that 87.5% of multi-agent configurations underperformed baseline systems, with coordination overhead identified as the primary limiting factor. Llama 3.1 8B tolerated Sequential and Hierarchical coordination with minimal degradation, while Granite 3.2 8B and Mistral 7B showed severe degradation across all strategies. Collaborative coordination failed universally despite highest output consistency. These findings suggest that single-agent baselines may be preferable for most deployment scenarios under similar conditions. Future research should explore following developments: evaluation of role-specific prompts, investigation of advanced consensus methods, exploration of adaptive systems for strategy selection, and joint tuning of retrieval thresholds and coordination strategies.
</details>

---

## 📝 Upcoming

### 🔜 Model-Dependent Similarity Thresholds in Retrieval-Augmented Generation  
*SPRINGER, Book Chapter 12*  


<details>
<summary><strong>Abstract (preview)</strong></summary>

The study investigates the impact of similarity threshold tuning on Retrieval-Augmented Generation (RAG) system performance across four open-source language models. Mistral 7B, Llama 3.1 8B, Granite 3.2 8B, and DeepSeek 8B were evaluated using 369 question-answer pairs from the agricultural domain. Similarity thresholds from 0.50 to 0.95 were systematically tested to identify model-specific optimal configurations. An enhanced Composite Performance Score (CPS) was employed, integrating eleven evaluation metrics spanning lexical overlap (METEOR, ROUGE-2.f, ROUGE-L.f), semantic similarity (BERTScore.f1, B-RT.average), fluency and accuracy (F1 score, B-RT.fluency), and language modeling (Laplace Perplexity, Lidstone Perplexity) dimensions into a unified, weighted scoring system. The framework was extended with a Threshold-Aware Composite Performance Score (T-CPS) that penalizes output variability to identify stable, high-performing configurations. Results revealed distinct model sensitivity patterns. Mistral 7B achieved statistical significance at six thresholds with peak improvement of 4.58%. Granite 3.2 8B demonstrated consistent performance across seven consecutive thresholds. Llama 3.1 8B showed selective response at three high thresholds. DeepSeek 8B exhibited limited sensitivity with significance at only two thresholds. Model-specific threshold calibration yielded performance improvements ranging from 1.01% to 4.58% without requiring architectural modifications or additional computational resources. These findings demonstrate that model-specific threshold calibration represents a practical enhancement strategy that can deliver measurable performance improvements without requiring architectural modifications or additional computational resources.



