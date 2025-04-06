# README

This repository contains work related to the assignment given by SaiDL. The following topics are covered:

## 1. CoreML  
## 2. State Space Models (SSM)  

The repository includes Jupyter Notebook (`.ipynb`) files and LaTeX documentation for both topics. Below, I provide a brief overview of my observations for each project.

---

## **1. CoreML**

This project involved the implementation of APL frameworks to test robustness in the presence of noisy datasets.  

  I was aware of losses but unfamiliar with their classifications, such as active and passive loss. To address this, I familiarized myself with these loss types. After reviewing the referenced paper, I understood why this framework is being tested—it helps strike a balance between active and passive losses to avoid overshooting by relying solely on one type.

  I prepared datasets for both symmetrical and asymmetrical noise. Initially, I expected better performance on asymmetrical data since changes made for any class were fixed and deterministic. However, this expectation was not met.  
  - Symmetric noise is easier to handle due to its uniformity.
  - Asymmetric noise presents greater challenges because of structured bias and class imbalance.
  - While I understand this reasoning, I am still not entirely convinced why symmetric noise performs better.

---

## **2. State Space Models (SSM)**

Unlike CoreML, I had no prior knowledge of SSMs. To build my understanding, I followed these steps:

- **Learning Phase**:
  - Explored various blogs to grasp the concepts (the mathematics was daunting, so I focused on building intuition).
  - Studied an updated version of CS231n by the University of Michigan (taught by the same instructor) to understand the attention mechanism behind Transformers.
  - Referred to blogs by the author and The annotated S4 paper for a deeper understanding.

- **Training Phase**:
  - While training, I couldn’t replicate the results from the paper due to limitations in parameters such as the number of layers, epochs, etc.
  - Despite this, I trained the model multiple times with varying parameters to provide proof of work.

---

