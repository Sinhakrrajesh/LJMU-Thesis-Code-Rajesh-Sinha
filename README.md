# Thesis Experiments

## Overview

This repository contains the experimental code, evaluation results, and explainability analysis developed as part of my Master's dissertation titled:

**Evaluating Prompt Engineering Strategies for Generative AI in BFSI Applications: A Comparative Study of Risk Analysis, Customer Communication, and Decision Explanation with Explainable AI.**

The study investigates six prompt engineering strategies across multiple Large Language Models (LLMs) for Banking, Financial Services, and Insurance (BFSI) applications.

The research focuses on:
- Risk Analysis and Summarisation
- Customer Communication Drafting
- Decision Explanation and Justification

## Evaluated Prompt Engineering Strategies

- Zero-shot Prompting
- Few-shot Prompting
- Role-based Prompting
- Instruction-based Prompting
- Constraint-based Prompting
- Chain-of-Thought (CoT) Prompting

## Evaluated Large Language Models

- Llama-3.1-8B-Instant
- Llama-3.3-70B-Versatile
- GPT-OSS-20B
- GPT-OSS-120B

## Repository Structure

```text
LJMU-Thesis-Code-Rajesh-Sinha/
│
├── Task1_Risk_Analysis_and_Summarisation/
│   ├── Llama-3.1-8B-Instant/
│   ├── Llama-3.3-70B-Versatile/
│   ├── GPT-OSS-20B/
│   └── GPT-OSS-120B/
│
├── Task2_Customer_Communication_Drafting/
│   ├── Llama-3.1-8B-Instant/
│   ├── Llama-3.3-70B-Versatile/
│   ├── GPT-OSS-20B/
│   └── GPT-OSS-120B/
│
├── Task3_Decision_Explanation_and_Justification/
│   ├── Llama-3.1-8B-Instant/
│   ├── Llama-3.3-70B-Versatile/
│   ├── GPT-OSS-20B/
│   └── GPT-OSS-120B/
│
├── Outputs/
│   ├── Evaluation Results/
│   ├── Visualisations/
│   ├── Explainability Results/
│   └── Comparative Analysis/
│
├── Dataset/
├── README.md
└── requirements.txt
```



## Explainability Analysis

- LIME
- SHAP
- Integrated Gradients

## Key Contributions

- Controlled comparison of six prompt engineering strategies
- Evaluation across three BFSI tasks
- Comparative analysis of four LLMs
- Hallucination and compliance risk analysis
- Explainability analysis
- Identification of task-specific model-prompt combinations

## Disclaimer

This repository is intended for academic and research purposes only.

## Copyright

© 2026 Rajesh Sinha. All rights reserved.
