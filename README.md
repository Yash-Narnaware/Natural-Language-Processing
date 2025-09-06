# 🧠 Natural Language Processing – B.Tech Project

This repository contains my **B.Tech Project in Natural Language Processing (NLP)**.  
It features implementations of **two recommendation systems**, along with **experiment notebooks**, **project presentations**, and the **final BTP report**.

---

## 📌 Project Overview
The project explores **NLP techniques** and applies them to real-world applications.  
Key areas covered:
- Text preprocessing: tokenization, POS tagging, TF-IDF  
- Embeddings: Word2Vec, GloVe  
- Deep learning: RNNs, LSTMs  
- Transformer-based models: BERT  

---

## 🚀 Implemented Systems

### 📖 Bhagavad Gita Verse Recommender
- Web scraped and curated a dataset of **700+ verses** of the Bhagavad Gita.  
- Preprocessed the text (tokenization, stopword removal, lemmatization).  
- Implemented **TF-IDF** with **cosine similarity** to recommend semantically relevant verses.  
- Demonstrated practical usage of vector space models for scripture-based recommendations.  
- 📂 Dataset available on Kaggle: [Bhagavad Gita](https://www.kaggle.com/datasets/yashnarnaware/bhagavad-gita-versewise)  

### 🎬 Hybrid Movie Recommendation System
- Built using **MovieLens 32M dataset** and **TMDB 5000 Movies dataset**.  
- Combined:
  - **Collaborative Filtering (CF)** for user–item interactions  
  - **Content-Based Filtering (CBF)** for metadata-driven similarity  
- Designed **hybrid score fusion** with tunable weights to balance CF and CBF.  
- Analyzed **user-wise score distributions** to verify fairness and relevance.  

---

## 📊 Results
- **Verse Recommender** → Successfully retrieves semantically related verses with high relevance.  
- **Hybrid Movie Recommender** → Outperforms standalone CF/CBF, producing balanced, personalized recommendations.  
- **BERT-based QA** → Demonstrated transformer-based contextual understanding.  

---

## 🛠️ Tech Stack
- **Languages:** Python, Jupyter Notebooks  
- **Libraries:** scikit-learn, NumPy, Pandas, SciPy, Matplotlib  
- **NLP Frameworks:** NLTK, spaCy, HuggingFace Transformers  

---

## 📄 Deliverables
This repo includes:
- ✅ Source code for both recommenders and experiments  
- ✅ Datasets (or download instructions)  
- ✅ Final BTP Report (PDF)  
- ✅ All Presentation Slides (PPTs)  

---

## 🙌 Acknowledgements
Guided by **Dr. Saurabh Trivedi**.  
Special thanks to peers and collaborators for their contributions and feedback.  
