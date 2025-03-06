# Book Recommendation System with Embeddings

This project implements a **book recommendation system** using different **text embeddings** (TF-IDF, Word2Vec, and BERT). The system takes book summaries and applies similarity measures to recommend similar books.

---

## Project Structure

📂 **Embedding/**  
- `01_book_crawling.ipynb` → Scrapes book data (titles, authors, summaries, and images) from Goodreads  
- `02_TF_IDF.ipynb` → Implements book embeddings using TF-IDF  
- `03_Word2Vec_Embedding.ipynb` → Implements Word2Vec embeddings  
- `04_BERT_Embedding.ipynb` → Uses BERT embeddings for semantic similarity  

📄 **Data Files**  
- `books.csv` → Contains book titles and author names  
- `books_summary.csv` → Includes book summaries for embedding-based recommendations  

📄 **Project Documentation**  
- `README.md` → Overview and instructions

---

## How to Run

### **Install Dependencies**
```bash
pip install -r requirements.txt