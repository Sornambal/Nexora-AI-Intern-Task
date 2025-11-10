# 🧠 Nexora AI Intern Task – Vibe Matcher Prototype

**Project Title:** Vibe Matcher – AI-Powered Fashion Recommendation Prototype  
**Organization:** Nexora.fashion  
**Submission Date:** November 11, 2025  

---

## 🚀 Overview
This project demonstrates a **vibe-driven fashion recommendation system** that connects user moods with matching fashion items.  
Given a natural language vibe query (e.g., _“energetic urban chic”_), the system embeds product descriptions using **OpenAI’s text-embedding-ada-002** model and retrieves the **top-3 similar products** via cosine similarity.

---

## 🧩 Features
- 🪄 AI-powered vibe matching using text embeddings  
- 🧥 Mock dataset of 6+ sample fashion products (Boho, Streetwear, Cozy, etc.)  
- 🔍 Top-3 product retrieval using cosine similarity (via scikit-learn)  
- ⚠️ Fallback logic for low-confidence matches  
- 📈 Evaluation metrics and latency plotting for performance tracking  
- 💡 Designed for Nexora.fashion’s vibe-based e-commerce experience  

---

## 🧠 Tech Stack
| Component | Technology |
|------------|-------------|
| Language | Python |
| Environment | Google Colab / Jupyter |
| Libraries | `openai`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `tqdm` |
| AI Model | `text-embedding-ada-002` (OpenAI Embeddings API) |

---

## 🧮 Steps Performed
1. **Data Preparation** – Created mock fashion dataset (5–10 items with vibes).  
2. **Embedding Generation** – Used OpenAI embeddings or deterministic mock embeddings.  
3. **Similarity Search** – Computed cosine similarity between query and product vectors.  
4. **Evaluation** – Tested 3 vibe queries, logged similarity metrics and latency.  
5. **Reflection** – Suggested improvements (Pinecone integration, hybrid ranking, etc.).

---

## 🧾 Example Queries
| Query | Example Output |
|--------|----------------|
| "Energetic urban chic" | Street Snap Hoodie, Minimalist Blazer, Sport Luxe Joggers |
| "Relaxed cozy weekend" | Cozy Knit Cardigan, Boho Dress, Elegant Silk Scarf |
| "Festival boho sunset" | Boho Dress, Elegant Silk Scarf, Cozy Knit Cardigan |

---

## 🕓 Future Improvements
- Integrate **Pinecone / Weaviate** for scalable vector search  
- Use hybrid ranking (BM25 + Embedding)  
- Add **image embeddings** for multi-modal matching  
- Cache embeddings to improve runtime performance  
- Personalize recommendations using user profiles  

---
