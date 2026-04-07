# AI Ethics RAG System

This repository contains a Retrieval-Augmented Generation (RAG) pipeline built with **Flowise** to process and query documents on **Artificial Intelligence Ethics**.  
It integrates **Google Gemini embeddings** and **Mistral AI** for conversational retrieval.

---

## 📌 Features
- Loads and processes the *Artificial Intelligence (AI) Ethics.pdf* paper
- Splits text into chunks for efficient retrieval
- Embeds text using **Google Gemini**
- Stores embeddings in an **in-memory vector store**
- Uses **Mistral AI** for conversational Q&A
- Supports **ethical AI queries** with source citations

---

## 📂 Repository Structure
- `docs/` → Diagrams, screenshots, and explanations
- `src/` → Chatflow JSON and configuration files
- `data/` → AI Ethics PDF used for retrieval
- `README.md` → Documentation and usage guide

---

## 🖼 Workflow Diagram
![Workflow Diagram](docs/workflow-diagram.png)

---

## 🚀 Usage
1. Install [Flowise](https://flowiseai.com/)
2. Import the `src/chatflow.json` file into Flowise
3. Upload the `data/Artificial_Intelligence_AI_Ethics.pdf`
4. Run the pipeline and query:
5. Example output:
> Ethical AI prevents harm, addresses bias, and protects human rights.

---

## 📖 References
- Siau, K., & Wang, W. (2020). *Artificial Intelligence (AI) Ethics: Ethics of AI and Ethical AI*. Journal of Database Management, 31(2), 74–87.  
- Flowise Documentation: https://docs.flowiseai.com/

---

## 📜 License
MIT License
