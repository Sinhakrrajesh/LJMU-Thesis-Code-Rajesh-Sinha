# Evaluating Prompt Engineering Strategies for Generative AI in BFSI Applications: A Comparative Study of Risk Analysis, Customer Communication, and Decision Explanation with Explainable AI 

## Overview

This repository contains the experimental code, evaluation results, and explainability analysis developed as part of my Master's dissertation

- Student Name: Rajesh Kumar Sinha
- Programme: MSc Artificial Intelligence and Machine Learning, Liverpool John Moores University (LJMU)

The study investigates six prompt engineering strategies across multiple Large Language Models (LLMs) for Banking, Financial Services, and Insurance (BFSI) applications.

## The research focuses on:
- Risk Analysis and Summarisation
- Customer Communication Drafting
- Decision Explanation and Justification

# DataSet
- The study uses the Consumer Financial Protection Bureau complaint dataset.
- https://www.consumerfinance.gov/data-research/consumer-complaints/

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
├── Experiments/
│
├── Consolidated_Experiment_Result/
│   ├── Visualization_Outputs/
│   └── Experiment_Results.xlsx
│
├── Dataset/
│   └── common_bfsi_dataset.csv
│
├── Dataset_Preparation_Experiment/
│   └── 01_CFPB_Dataset_Cleaning_and_Preparation.ipynb
│
├── Task_1_Risk_Analysis_and_Summarisation_Experiments/
│   ├── Experiment_1_Llama_3_1_8b_instant/
│   ├── Experiment_2_Llama_3_3_70b_versatile/
│   ├── Experiment_3_04_Task1_GPTOSS_120B/
│   └── Experiment_4_05_Task1_GPTOSS_20B/
│
├── Task_2_Customer_Communication_Drafting_Experiments/
│   ├── Experiment_5_06_Task_2_Llama_3_1_8b_instant/
│   ├── Experiment_6_07_Task_2_Llama_3_3_70b_versatile/
│   ├── Experiment_7_08_Task_2_GPTOSS_120B/
│   └── Experiment_8_09_Task_2_GPTOSS_20B/
│
├── Task_3_Decision_Explanation_and_Justification_Experiments/
│   ├── Experiment_09_10_Task_3_Llama_3_1_8b_instant/
│   ├── Experiment_10_11_Task_3_Llama_3_3_70b_versatile/
│   ├── Experiment_11_12_Task_3_GPTOSS_120B/
│   └── Experiment_12_13_Task_3_GPTOSS_20B/
│
└── README.md
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
