# Ctrl-Old-Delete

# 🧬 Agentic AI Against Aging: Comprehensive Aging Theories Identification

Welcome to the my **central repository** 🏛️ for our hackathon project:  
**Agentic AI Against Aging** — Task: *Identification of All Possible Aging Theories*.

_Aging is humanity’s most universal puzzle. Can modern AI identify **all** the theories trying to explain it?_

---
> **:sparkles: Project Final Results & Data**  
> :file_folder: [All results, datasets, and final outputs are available here!](https://drive.google.com/drive/folders/11SeqMT_Sjd2AOA2smFy-ixIONTtbRCDA?usp=sharing)
---

🌐 **Explore the Project Website:**  
[Agentic AI Against Aging — Interactive Web App](https://v0-agentic-workflow-website.vercel.app)


## 🚀 Project Overview

This page is your **main portal** to the code, ideas, and progress for the “Agentic AI Against Aging” hackathon submission focused on mapping the full landscape of scientific aging theories.

> ⚡ **Note:**  
> This is the central README — most of the *real code, AI pipelines, and data processing logic reside in separate, dedicated repositories* for each stage.  
> This document will guide you through the flow, logic, and module links.  
>
> _Aging is inevitable. But our inspiration is timeless!_ ⏳

---

## :world_map: Hackathon Workflow

Our system follows a structured, agentic multi-stage pipeline:

### **1️. Stage 1: Paper Mining**  
- **Goal:** Collect a broad set of DOIs with *high recall* for potential aging theory publications.  
  [🔗 Stage 1 Repository: download_agent](https://github.com/DianaZagirova/download_agent)

---

### **2️. Stage 2: Full-Text Extraction & Metadata**  
- **Goal:** Extract full texts and detailed metadata for the previously collected papers.  
  [🔗 Stage 2 Repository: scihub_api](https://github.com/DianaZagirova/scihub_api)

---

### **3️. Stage 3: LLM Judge — Filtering for Aging Theory**  
- **Goal:** Use a Language Model (LLM) Judge to filter for only those papers relevant to aging theory, applying a refined AI-based definition.  
  [🔗 Stage 3 Repository: judge_agent](https://github.com/DianaZagirova/judge_agent)

---

### **4️. Stage 4: Theory Extraction & QA (Part 1 & 2)**  
- **Goal:**  
    - Utilize LLMs to extract and normalize biological *aging theories* from selected papers.
    - Use LLMs for answering questions about papers containing valid aging theories.  
  [🔗 Stage 4 Repository: theories_extraction_agent](https://github.com/DianaZagirova/theories_extraction_agent)

---

### **5️. Stage 5: Embedding DB & RAG-based QA (Part 2)**  
- **Goal:**  
    - Create an embeddings database from extracted knowledge.
    - Employ Retrieval-Augmented Generation (RAG) for enhanced, accurate question answering about aging theories.  
  [🔗 Stage 5 Repository: RAG question answering agent](https://github.com/DianaZagirova/RAG_question_answering_agent)

### ️**6. Additional Stage: Analyze true and false positives**  
- **Goal:**  
    - Use GPT-5 to analyze true and false positives aging-theory-related articles to refine the definition of aging-theory-related articles.
    - Create a detailed queries for PubMed search (for Stage 1).
  [🔗 Additional Stage Repository: paper patterns agent](https://github.com/DianaZagirova/paper_patterns)
---

## 📝 Final Datasets, Results, and Pipelines

For simplicity and hackathon clarity, **final data, aggregated results, derived knowledge bases, and output files** are kept together:  
:star: [See the results on Google Drive](https://drive.google.com/drive/folders/11SeqMT_Sjd2AOA2smFy-ixIONTtbRCDA?usp=sharing)

---
## 📍 Start Exploring!

Please note that most of the modules produced very large files/databases that were not included into repositories. I tried to include as many files and examples as possible, but still the main collected data and the resulta are too large even for LFS.

Please explore repositories/examples files and demos. All other data could be provided by the request. Thank you! 



## :man_scientist: Team & Acknowledgments

This project is part of the “Agentic AI Against Aging” hackathon.
- Team lead: Diana Zagirova

---

> _Aging is certain. But the future of understanding it is now more ageless than ever, thanks to AI._  
```
---

