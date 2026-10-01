Yeah, the previous one was way too much for a GitHub README. For the repo, I'd keep it **clean, technical, and brief** while still showing the evolution from your original project.

# Contracts Intelligence Platform

An AI-powered evolution of my original **[Contracts Tracker](https://github.com/Sydney-Nyanchoga/Contracts-Tracker)**.

The initial Contracts Tracker was built to manage contracts, clients, dates, statuses, and court cases. This version extends that foundation into a **document intelligence platform** capable of processing both digital and hard-copy contracts.

## What’s New

* 📄 Upload and process PDF/image contracts
* 🔍 OCR for scanned and physical contracts
* 🤖 AI-powered extraction of contract information
* 🧠 Semantic search using embeddings and `pgvector`
* 💬 RAG-based contract question answering
* 📅 Contract expiry and renewal tracking
* ⚖️ Contract and court-case management
* ✅ Human verification of AI-extracted information

### AI Workflow

```text
Contract / Scan
      ↓
OCR & Document Processing
      ↓
AI Information Extraction
      ↓
Human Verification
      ↓
PostgreSQL
      ↓
Embeddings + pgvector
      ↓
Semantic Search / RAG
```

The goal is to move from simply **tracking contracts** to enabling the system to **understand and work with the contracts themselves**.

## Tech Stack

| Area             | Technology                |
| ---------------- | ------------------------- |
| Frontend         | React + TypeScript + Vite |
| UI               | Tailwind CSS + shadcn/ui  |
| Backend          | Python + FastAPI          |
| Database         | PostgreSQL + pgvector     |
| ORM              | SQLAlchemy                |
| OCR              | OCRmyPDF + Tesseract      |
| PDF Processing   | pdfplumber                |
| Image Processing | OpenCV                    |
| Local AI         | Ollama                    |
| Embeddings       | Sentence Transformers     |
| Testing          | Pytest + Vitest           |
| Containers       | Docker / Podman           |
| CI/CD            | GitHub Actions            |

## Development Roadmap

* [x] Core contract management
* [ ] Document upload & storage
* [ ] OCR & text extraction
* [ ] AI contract information extraction
* [ ] Semantic search
* [ ] RAG / "Ask Your Contract"
* [ ] Contract comparison
* [ ] Automated expiry & renewal reminders

> **From tracking contracts → to understanding contracts.**

**Status:** 🚧 Active Development
