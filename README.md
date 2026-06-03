AI-Powered Semantic Product Recommendation Engine using FAISS & Sentence Transformers

📌 Project Overview

This project is an AI-powered semantic search and recommendation engine that recommends products based on customer reviews and user intent queries.

Instead of traditional keyword search, this system uses:

- NLP Embeddings
- Sentence Transformers
- FAISS Vector Database
- Semantic Similarity Search

to understand the meaning and context behind customer queries.

Example queries:

- "Best phone for gaming"
- "Phone with strong battery life"
- "Travel-friendly lightweight phone"
- "Affordable phone with good value"

The system intelligently retrieves the most relevant products using vector similarity search.

---

🚀 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Sentence Transformers
- FAISS
- NLP
- Semantic Search
- Vector Embeddings

---

📂 Dataset Information

Dataset contains:

- review_id
- product_id
- review_text
- rating

Customer reviews are converted into embeddings and stored in a FAISS vector index for semantic retrieval.

---

🧠 Project Workflow

Customer Reviews CSV
        ↓
Text Preprocessing
        ↓
Sentence Transformer Embeddings
        ↓
Numerical Vector Conversion
        ↓
FAISS Vector Index
        ↓
User Query Embedding
        ↓
Similarity Search
        ↓
Product Recommendation

---

⚡ Features

✅ Semantic Product Search
✅ AI-Based Recommendation Engine
✅ Embedding Generation
✅ Fast Vector Similarity Search
✅ Customer Review Analysis
✅ NLP-Based Retrieval System
✅ Real-Time Query Recommendation

---

🔍 Example Queries

search_products("Best phone for gaming")

search_products("Phone with good battery")

search_products("Affordable phone")

search_products("Travel friendly lightweight phone")

---

📊 Sample Recommendations

User Query| Recommended Product
Best gaming phone| P103
Best battery phone| P101
Travel-friendly phone| P104
Budget phone| P105

---

## 📷 Project Output

![Output](screenshots/output.png)

📈 Key Insights

- Semantic search understands meaning instead of exact keywords.
- Embeddings capture contextual information from customer reviews.
- FAISS enables extremely fast vector similarity search.
- The recommendation system improves user experience and product discovery.

---

🎯 Real-World Applications

- E-commerce recommendation systems
- Amazon-style product search
- Netflix recommendation systems
- AI chatbots
- Semantic document retrieval
- Customer feedback analysis

---

📌 Future Improvements

- Deploy using Streamlit
- Add voice-based search
- Connect with real e-commerce datasets
- Use advanced LLM embeddings
- Build web application interface

---

👨‍💻 Author

Ghanghas Mahesh
