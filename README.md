# Project: Analisis Sentimen – Scraping Data & Pelatihan Model

Repository ini berisi dua proyek utama dalam rangkaian Big Fundamental Deep Learning (BFDL), yaitu:

- Web Scraping untuk Mengumpulkan Data Teks (Aplikasi Duolingo)

- Pelatihan Model Analisis Sentimen

Kedua proyek ini saling berhubungan: data hasil scraping digunakan untuk membangun model klasifikasi sentimen.

## 1. Scraping Data – Analisis Sentimen
Deskripsi

Project ini melakukan proses web scraping untuk mengumpulkan data teks (misalnya review, komentar, atau tweet) yang akan digunakan untuk analisis sentimen.

Langkah Utama

1. Menggunakan library seperti requests, BeautifulSoup, atau snscrape (sesuai isi notebook)

2. Mengambil data dari play store

3. Membersihkan hasil scraping dan menyimpannya dalam format CSV atau dataframe

Output

Dataset mentah yang siap diproses dan digunakan dalam pelatihan model analisis sentimen.

## 2. Pelatihan Model – Analisis Sentimen
Deskripsi

Notebook ini berfokus pada membangun model sentiment analysis menggunakan dataset hasil scraping.

Workflow

1. Text preprocessing:
  
  - Cleansing (menghapus URL, emoji, tanda baca, dll)

  - Case folding
    
  - Slang words
  
  - Tokenization
  
  - Stopword removal
  
  - Stemming (Sastrawi)

2. Feature engineering menggunakan:

- Lexicon
  
- TF-IDF

- Word Embedding

3. Modeling menggunakan algoritma Machine Learning seperti:

- Logistic Regression

- SVM
  
- Bidirectional LSTM

- CNN

Evaluasi model:

- Accuracy

- Classification Report

- Confusion Matrix

- Plot training vs validation accuracy dan validation loss

Hasil

- Model mampu mengklasifikasi sentimen (positif/negatif/netral) dengan akurasi yang baik

- Mengetahui fitur kata yang paling berpengaruh dalam menentukan sentimen

- Model dapat diimplementasikan untuk analisis opini publik atau review produk

Teknologi yang Digunakan

- Python

- BeautifulSoup / snscrape

- pandas, numpy

- scikit-learn

- Sastrawi (text preprocessing)

- Matplotlib / Seaborn

- Jupyter Notebook
