# 📚 Similar Amazon Book Reviews

### 🔍 Detecting duplicate and near-duplicate reviews in the Amazon Books dataset using MinHash and LSH

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
  https://colab.research.google.com/github/maedehrabiee/Algorithms-for-Massive-Data-DSE-/blob/main/Similar_Amazon_Book_Reviews_Maedeh_Rabiee.ipynb
)

---

## 📘 Project Description
A scalable end-to-end pipeline for detecting duplicate and near-duplicate book reviews in the Amazon Books dataset (~3 million records).  
The approach uses **3-word shingles**, **MinHash (128 permutations)**, and **Locality-Sensitive Hashing (LSH)** with a **Jaccard similarity threshold = 0.6**.  

When tested on a 1 % sample (≈ 29,900 reviews), the total number of possible pairs (~4.47 × 10⁸) was reduced to just **331 candidates**, all confirmed ≥ 0.6 Jaccard.  
Implemented in **Python** with the **Datasketch** library and runs smoothly on **Google Colab**.

---

## 🧰 Tools
- Python  
- Datasketch  
- NumPy, Pandas  
- Google Colab  

---

## 📁 Dataset
[Kaggle – Amazon Books Reviews Dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews)

---

## 👩‍💻 Author
**Maedeh Rabiee**  
MSc Data Science for Economics — University of Milan  
