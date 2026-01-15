# Sanskrit Document Retrieval-Augmented Generation (RAG) System

## 📌 Project Overview
This project implements a **Retrieval-Augmented Generation (RAG)** system for **Sanskrit documents**.
The system retrieves relevant Sanskrit text from documents and generates **accurate, context-grounded answers**
using a Large Language Model (LLM).

This approach reduces hallucinations by grounding answers strictly in retrieved document content.

---

## 🎯 Objectives
- Load Sanskrit documents (PDF/DOCX)
- Split documents into meaningful text chunks
- Generate vector embeddings
- Store embeddings in a vector database
- Retrieve relevant context for user queries
- Generate accurate answers using RAG

---

## 🗂️ Project Structure
```
.
├── data/
│   └── sanskrit_documents.pdf
├── report/
│   └── final_report.pdf
├── RAG_Sanskrit.ipynb
├── requirements.txt
└── README.md
```

---

## 🛠️ Tools & Technologies
- Python
- LangChain
- FAISS (Vector Database)
- HuggingFace / OpenAI Embeddings
- PyPDF2
- python-docx

---

## 🔄 Methodology (RAG Pipeline)
1. Document Loading
2. Text Splitting
3. Embedding Generation
4. Vector Storage (FAISS)
5. Context Retrieval
6. Answer Generation using LLM

---

## 🧪 Evaluation
- Questions created manually from Sanskrit documents
- Answers evaluated for correctness, relevance, and faithfulness

---

## ✅ Results
- Accurate Sanskrit passage retrieval
- Reduced hallucinations
- Improved answer reliability

---

## ⚠️ Limitations
- OCR quality affects accuracy
- Sanskrit language complexity
- Limited dataset size

---

## 🚀 Future Enhancements
- Sanskrit-specific embedding models
- Multilingual query support
- Web application deployment

---

## 👤 Author
**Anurag Thakre**  
B.Tech – Computer Science & Engineering (Data Science)

---

## 📜 License
Academic and educational use only.
