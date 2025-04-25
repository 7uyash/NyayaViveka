# ⚖️ NyayaViveka – AI-Powered Legal Assistance Platform

NyayaViveka is a modern, AI-powered legal-tech platform designed to democratize access to legal information and support in India. It provides users with tools for analyzing legal documents, performing legal research, and receiving interactive guidance — all through a clean, intuitive, and responsive web interface.

> 🚀 Built with **Next.js**, Hugging Face APIs, and a strong focus on frontend AI integration.

---

## 👨‍💻 Team Details

We are a group of B.Tech (CSE) students from **K.R. Mangalam University**, working on this project as part of our academic initiative to leverage Artificial Intelligence for social good.

### 👥 Team Members:
- **Suyash Sahu** (Roll No: 23301010476) – Project Lead & Frontend Developer  
- **Prateek Pun** (Roll No: 2301010470) – Document Analysis & Integration  
- **Navneet Kumar** (Roll No: 2301010479) – Interactive AI Guidance & API integration  
- **Parth Pathak** (Roll No: 2301010433) – Legal Research & UI Design

---

## 🧠 Core Features

### 1. 📄 Document Analysis  
Upload legal PDFs and get key textual insights. Uses `pdf-lib` or `pdfjs-dist` to extract and simulate summary-style responses. *(In advanced versions, Hugging Face models like `law-ai/InLegalBERT` can be integrated for true legal summarization.)*

### 2. 🔍 Legal Research  
Search through simulated legal databases (IPC sections, case laws, articles). In future iterations, this will use embeddings from legal AI models to perform intelligent lookup and ranking.

### 3. 🤖 Interactive AI Guidance  
Ask legal questions and receive answers powered by Hugging Face’s QA model `deepset/roberta-base-squad2`. No `.env` file used — API key is included directly for ease of use.

---

## 🛠 Technologies Used

- **Next.js** – App framework
- **Tailwind CSS / ShadCN** – Styling & UI Components
- **Hugging Face Inference API** – AI-powered QnA and model interaction
- **React Router / Next Navigation** – Page transitions
- **pdf-lib / pdfjs-dist** – PDF Text Extraction
- **JavaScript & TypeScript** – Core development languages

---

## 📦 Project Structure

```bash
NyayaViveka/
├── pages/
│   ├── index.js                 # Landing page
│   ├── document-analysis.js     # Document Analysis module
│   ├── legal-research.js        # Legal Research module
│   └── interactive-guidance.js  # Interactive AI QnA
├── components/
│   ├── FeatureCard.jsx
│   ├── FileUpload.jsx
│   └── SearchResults.jsx
├── public/
├── styles/
├── README.md
└── ...
