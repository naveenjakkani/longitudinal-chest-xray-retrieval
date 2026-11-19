# 🫁 Longitudinal Chest X-Ray Image Retrieval & Comparison System

An AI-powered medical imaging web application designed to retrieve prior patient chest radiographs and perform side-by-side longitudinal comparison to assist clinicians in tracking disease progression[cite: 1].

## 📌 Overview
Evaluating subtle clinical changes—such as effusion progression, infiltrates, or post-treatment recovery—requires comparing a patient's current chest X-ray against historical scans. This system leverages deep visual embeddings and similarity search to automatically retrieve relevant longitudinal studies and display them in an interactive comparison interface[cite: 1].

## ✨ Key Features
- **Content-Based Image Retrieval (CBIR):** Extracts dense feature embeddings from chest radiographs to retrieve visually and anatomically matched prior scans[cite: 1].
- **Longitudinal Side-by-Side Comparison:** Interactive TypeScript/React viewer for comparing baseline and follow-up radiographs across timestamps[cite: 1].
- **Visual Explainability & Attention Mapping:** Highlights key regions of interest and structural differences between sequential scans.
- **Fast Vector Similarity Search:** Low-latency retrieval across indexed medical imaging datasets.

## 🛠️ Tech Stack
- **Frontend:** TypeScript, React, Tailwind CSS *(adjust if using Next.js/Vite)*[cite: 1]
- **Deep Learning & Vision:** PyTorch / DenseNet / Vision Transformer (ViT) *(keep the backbone you used)*
- **Similarity Search:** FAISS / Cosine Similarity Vector Index
- **Backend / API:** FastAPI / Node.js *(keep the one you used)*

