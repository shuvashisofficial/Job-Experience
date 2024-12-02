### **README**

This repository contains the implementation and deliverables for **Assignment 1**, prepared as part of the AI/ML Engineer position assessment at **Nagorik Technologies Ltd.**. The tasks demonstrate proficiency in **NLP**, **computer vision**, and **machine learning workflows**, aligning with the recommended topics for preparation:

- **Basic SQL Queries**
- **Fundamental Coding Problems**: Arrays, graphs, and strings.
- **Object Detection and Classification**: Using computer vision models.
- **Large Language Models (LLMs)**: Foundations of AI and their practical applications.

---

### **Task 1: Build a Multilingual QA System**
- **Objective**: Build a Question-Answering (QA) system capable of handling both **Bengali** and **English**.
- **Model**: Fine-tuned **XLM-RoBERTa**, a multilingual transformer-based model, for the QA task.
- **Datasets**:
  - Bengali SQuAD: From `csebuetnlp/squad_bn`.
  - English SQuAD: From Hugging Face's `squad` dataset.
- **Key Features**:
  - Multilingual support for **Bengali** and **English** questions and contexts.
  - Fine-tuned on combined datasets using Hugging Face's Trainer API.
  - Evaluated through a pipeline-based QA system.
  - Tested via examples, providing accurate answers for multilingual input.

---

### **Task 2: Fine-Tune Stable Diffusion**
- **Objective**: Fine-tune a lightweight **Stable Diffusion model** for **image-to-image generation**.
- **Model**: `runwayml/stable-diffusion-v1-5`, optimized for image-to-image translation.
- **Dataset**: Kaggle's **Cats and Dogs Dataset**, processed for generating high-quality paired input-output data.
- **Key Features**:
  - Fine-tuned on GPUs for fast training and efficient image generation.
  - Generates new images based on input images and text prompts.
  - Includes a **Streamlit web app** for user-friendly testing of the image generation pipeline.

---

### **Task 3: Complete Colab Notebook**
- **Objective**: Complete the provided Colab notebook (`Assignment-1.ipynb`) with required functionalities.
- **Notebook Highlights**:
  - **Data Preprocessing**: Cleaned and transformed datasets for ML workflows.
  - **Visualization**: Presented insightful data visualizations for exploratory data analysis.
  - **Model Training**: Implemented machine learning models with proper evaluation and logical explanations.
- **Deliverable**:
  - A fully completed and well-documented notebook demonstrating essential ML/AI workflows.

---