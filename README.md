# agentic-document-ai
Agentic Document AI pipeline using PaddleOCR &amp; LangChain

# Agentic Document AI – From OCR to Autonomous Extraction

This repository contains my implementation and experiments based on the course
**“Document AI: From OCR to Agentic Doc Extraction”** by **DeepLearning.AI** in collaboration with **LandingAI**.

> ⚠️ **Credit Notice**
> The original course content, structure, and instructional notebooks belong to
> **DeepLearning.AI** and **LandingAI**.
>
> This repository is for **educational purposes only** and includes my **personal experiments, modifications, and extensions** built on top of the course material.

---

## 📌 Project Overview

This project implements an **end-to-end agentic document intelligence system** capable of:

* Extracting text from complex documents using **PaddleOCR**
* Understanding document layout & reading order
* Orchestrating **LangChain agents** for:

  * Tool selection
  * Multi-step reasoning
* Building **RAG pipelines** for document question answering
* Handling:

  * Tables
  * Charts
  * Difficult Documents like complex tables, certificates with stamps, low-quality scans
  * Financial & research documents

---

## 🧠 Architecture

```
Document → PaddleOCR → Layout Parsing →
Agent Orchestrator → Tools (RAG, VLM, QA) → Output
```

---

## 📂 Repository Structure

```
agentic-document-ai/
│
├── notebooks/
│   ├── Agentic_Doc_Understanding.ipynb
│   ├── ADE_Difficult_Docs.ipynb
│   ├── ADE_Extraction_for_RAG.ipynb
│   ├── Doc_Processing_Pipeline_Loan_Automation.ipynb
│   ├── Research_Paper_Chatbot_with_Strands_Agents.ipynb
│
├── assets/
│
├── README.md
└── requirements.txt
```

---

## 📘 Notebooks Description

| Notebook                      | Purpose                                  |
| ----------------------------- | ---------------------------------------- |
| **Agentic_Doc_Understanding** | Core agent system for tool orchestration |
| **ADE_Difficult_Docs**        | Handling  Difficult Documents like complex tables, certificates with stamps, low-quality scans  |
| **ADE_Extraction_for_RAG**    | Building RAG pipelines                   |
| **Loan Automation Pipeline**  | Fintech document processing              |
| **Research Paper Chatbot**    | Multi-agent academic QA system           |

---

## ⚙ Tech Stack

* PaddleOCR
* LangChain
* OpenAI / LLMs
* Vector Databases (FAISS)
* Python
* Flask
* OpenCV
* NumPy, Pandas

---

## 🚀 Use Cases

* Loan document automation
* Research paper chatbots
* Enterprise document QA
* Knowledge base creation
* Table & chart understanding

---

## 🎓 Course Credits

This work is based on the course:

**Document AI: From OCR to Agentic Doc Extraction**
Offered by **DeepLearning.AI** in collaboration with **LandingAI**

* Course Website: [https://www.deeplearning.ai](https://www.deeplearning.ai)
* LandingAI: [https://landing.ai](https://landing.ai)

All intellectual property of the original notebooks and teaching material belongs to **DeepLearning.AI & LandingAI**.

---

## 👤 Author

**Aryan Pawar**
IIT Bombay – BTech. in Mechanical Engineering + MTech. in AI & Data Science in 5 years (2022-2027)
LinkedIn: https://www.linkedin.com/in/pawararyan/

---

## 📜 License

This repository is for **educational and learning purposes only**.
Commercial usage of the original course material is prohibited.
