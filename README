# ⚖️ PolicyPulse — GDPR RAG Assistant

PolicyPulse is a Retrieval-Augmented Generation (RAG) system designed to analyze GDPR documents using Large Language Models (LLMs).

The application allows users to:

- Upload GDPR PDF documents
- Retrieve semantically relevant content
- Generate context-aware answers
- Verify generated responses against retrieved evidence

---

# 🚀 Features

- 📄 Upload and process GDPR PDF files
- 🔍 Semantic retrieval using Cosine Similarity
- 🧠 Context-aware answer generation with RAG
- 🧩 Token-based document chunking
- 🚫 Duplicate chunk detection and filtering
- ✅ Built-in response verification system
- 🎨 Interactive Gradio interface
- 📚 Source chunk visualization
- 📊 Similarity score display

---

# 🏗️ System Architecture

```text
Upload PDF
     ↓
Extract Text
     ↓
Chunk Document
     ↓
Generate Embeddings
     ↓
Store in ChromaDB
     ↓
Semantic Retrieval
     ↓
Generate Answer using LLM
     ↓
Verify Response
     ↓
Display Results
```

---

# 🛠️ Technology Stack

| Category | Technology |
|---|---|
| Programming Language | Python |
| Framework | LangChain |
| Vector Database | ChromaDB |
| Embeddings | HuggingFace |
| LLM | Groq |
| UI | Gradio |

---

# 📦 Installation

Install all required dependencies:

```bash
pip install -qU \
langchain \
langchain-groq \
langchain-community \
langchain-text-splitters \
langchain-huggingface \
chromadb \
pypdf \
sentence-transformers \
gradio
```

---

# 🔐 Environment Variables

For security reasons, never hardcode API keys inside the source code.

## Linux / Mac

```bash
export GROQ_API_KEY="YOUR_API_KEY"
```

## Windows CMD

```cmd
set GROQ_API_KEY=YOUR_API_KEY
```

## Windows PowerShell

```powershell
$env:GROQ_API_KEY="YOUR_API_KEY"
```

---

# ▶️ Running the Application

```bash
python app.py
```

---

# 🧠 Retrieval Strategy

The retrieval pipeline combines multiple techniques to maximize relevance and reduce noise:

- Cosine Similarity Search
- Top-K Semantic Retrieval
- Similarity Threshold Filtering
- Duplicate Chunk Removal

---

# ✅ Response Verification System

PolicyPulse includes an automated verification pipeline to evaluate generated responses.

## VERIFIED

The response is fully supported by retrieved document chunks.

## WARNING

The response may contain unsupported or hallucinated information.

## NOT FOUND

No relevant GDPR content was retrieved.

---

# 📋 Output Information

For every user query, the system provides:

- Generated Answer
- Verification Status
- Retrieved Context Chunks
- Chunk Identifiers
- Source Page Numbers
- Cosine Similarity Scores

---

# 📂 Project Structure

```text
PolicyPulse/
│
├── app.py
├── requirements.txt
├── README.md
├── chroma_db/
│
└── assets/
```

---

# 🖼️ Example Workflow

```text
User uploads GDPR PDF
            ↓
System extracts text
            ↓
Chunks are generated
            ↓
Embeddings stored in ChromaDB
            ↓
Relevant chunks retrieved
            ↓
LLM generates answer
            ↓
Verification system checks response
            ↓
Results displayed to user
```

---

# 👥 Project Team

| Name | GitHub |
|---|---|
| Mahmoud Khamis | https://github.com/Mahmoud70-7 |
| Ahmed Amr Elmokadem | https://github.com/elmokademahmed35-netizen |
| Rahaf Ehab | https://github.com/RahafEA |
| Rana Yasser | https://github.com/ranayaser |
| Badr Ahmed | https://github.com/BadrWaqas |
| Hazem Mahmoud | https://github.com/Haz3m-m7hmoud |

---

# 🙏 Acknowledgment

We would like to express our sincere gratitude to our instructor for the continuous support, valuable guidance, and constructive feedback throughout the development of this project.

Their mentorship played a major role in the successful completion of PolicyPulse.

---

# ⭐ Future Improvements

- Multi-PDF support
- Conversation memory
- Hybrid retrieval (BM25 + Dense Retrieval)
- Advanced fact-checking pipeline
- GPU optimization
- Docker deployment
- Authentication system
- Citation highlighting

---

# 📜 License

This project is developed for educational and research purposes.
