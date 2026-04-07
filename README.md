# AI Ethics RAG System

This repository contains my **Retrieval-Augmented Generation (RAG) pipeline** built in **Flowise**, using the *Artificial Intelligence (AI) Ethics.pdf* document.  
The system demonstrates how embeddings, vector storage, and conversational retrieval can be combined to answer questions about AI ethics.

---

## 📂 Repository Structure

- `/chatflow/AI_Ethics_RAG_System.json`  
  → Exported Flowise Chatflow JSON (import this into Flowise to recreate the pipeline).  

- `/screenshots/`  
  → Images of the pipeline design and workflow.  

- `/document/Artificial_Intelligence_AI_Ethics.pdf`  
  → Source document used for embeddings.  

- `/report/AI_Ethics_RAG_Report.docx`  
  → Written report explaining the system.  

- `/presentation/AI_Ethics_Presentation.pptx`  
  → Slides prepared for the Internal Assessment.

---

## 🚀 How to Import the Chatflow JSON

1. Open **Flowise**.  
2. Click the **three dots (⋮)** menu in the top‑right corner.  
3. Select **Import**.  
4. Upload the file:
5. 5. The pipeline will load exactly as designed.

---

## ⚙️ Pipeline Overview

- **File Loader** → Loads the AI Ethics PDF.  
- **Text Splitter** → Breaks content into chunks.  
- **Google Gemini Embedding** → Converts text into embeddings.  
- **Vector Store** → Stores embeddings for retrieval.  
- **MistralAI** → Generates conversational answers.  
- **QA Chain** → Combines retriever + LLM + memory for final output.

---

## 🖼️ Pipeline Diagram

Here’s the visual workflow of the RAG system:

![Pipeline Diagram](Pipeline%20flowise.png)

---

## 📖 Project Goal

This project explores whether **RAG systems** can be a solution to **AI Ethics challenges**, by enabling transparent, document‑grounded answers instead of hallucinations.

---

## 📝 Author

Created by **Isha** for Internal Assessment on *AI Ethics and RAG Systems*.
