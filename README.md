🛍️ Multimodal Product Recommendation System  
Image + Review → Recommendation Score**

A multimodal deep learning system that combines **computer vision** and **natural language processing** to classify fashion products and generate recommendation scores using **FastAPI** and **Streamlit**.

---

## 🚀 Features

- Image classification using a CNN backbone
- Review text analysis using a transformer-based NLP model
- Vision–language feature fusion
- Recommendation score generation (0–100)
- FastAPI backend (REST API)
- Streamlit frontend (interactive demo)
- Input validation (blank / invalid images blocked)

---

## 🧠 Model Overview

- **Vision model:** ResNet-50 (ImageNet pretrained)
- **Text model:** Transformer (BERT-based)
- **Fusion:** Concatenation of image + text embeddings
- **Head:** Fully connected classifier
- **Output:** Product category + confidence + recommendation score



