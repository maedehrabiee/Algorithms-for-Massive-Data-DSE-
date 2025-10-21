# 📚 Similar Amazon Book Reviews

### 🔍 Detecting duplicate and near-duplicate reviews in the Amazon Books dataset using MinHash and LSH

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
  https://colab.research.google.com/github/maedehrabiee/Algorithms-for-Massive-Data-DSE-/blob/main/Similar_Amazon_Book_Reviews_Maedeh_Rabiee.ipynb
)

---

## 📘 Project Description
This project builds a **scalable and efficient pipeline** to detect **duplicate and near-duplicate book reviews** from the **Amazon Books Reviews dataset**.  
The method combines three main steps:
- **Shingling:** splitting each review into sequences of 3 words  
- **MinHashing:** compressing text into compact signatures  
- **Locality-Sensitive Hashing (LSH):** quickly finding pairs of similar reviews based on Jaccard similarity  

The pipeline is implemented in **Python** using the **Datasketch** library and runs smoothly in **Google Colab**, making it suitable for large-scale text similarity detection tasks.

---

## 🧰 Tools and Technologies
- Python  
- Datasketch  
- NumPy & Pandas  
- Google Colab  

---

## 📁 Dataset
- **Source:** [Amazon Books Reviews Dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews)  
- **Main column used:** `review/text`

---

## 👩‍💻 Author
**Maedeh Rabiee**  
MSc Data Science for Economics — University of Milan  
