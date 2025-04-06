# 🧠 Sentiment Analysis Ulasan Aplikasi Indodax di Google Play Store

Proyek ini bertujuan untuk melakukan **analisis sentimen** terhadap ulasan pengguna aplikasi **Indodax** yang diperoleh dari Google Play Store. Proyek ini menggunakan metode machine learning dan deep learning untuk mengklasifikasikan sentimen menjadi *positif*, *netral*, atau *negatif*.

---

## 📌 Tujuan Proyek

- Mengumpulkan ulasan pengguna aplikasi Indodax menggunakan scraping otomatis
- Melakukan pembersihan dan praproses teks berbahasa Indonesia
- Menormalisasi kata tidak baku menggunakan kamus slang
- Membangun dan membandingkan model Machine Learning dan Deep Learning
- Mengevaluasi performa model berdasarkan akurasi dan metrik evaluasi lainnya

---

## 📁 Struktur Direktori
- 📦 Sentiment-Analysis-Indodax
- 📂 Dataset/ 📄 indodax_reviews.csv <- Dataset hasil scraping ┃📄 slang.json <- Kamus slang untuk normalisasi
- 📄 Scraping_Indodax.ipynb <- Notebook scraping review dari Google Play
- 📄 Sentiment_indodax.ipynb <- Notebook utama analisis sentimen
- 📄 requirements.txt <- Daftar dependensi proyek
- 📄 README.md <- Dokumentasi proyek ini

---

## ⚙️ Teknologi yang Digunakan

- Bahasa: **Python**
- Visualisasi: `Matplotlib`, `Seaborn`, `WordCloud`
- Preprocessing: `nltk`, `Sastrawi`, `re`, `string`, `json`
- Scraping: `google_play_scraper`
- Machine Learning: `scikit-learn`
- Deep Learning: `TensorFlow (Keras)`
- Notebook: Google Colab / Jupyter Notebook

---

## 📦 Instalasi

### 🔧 Cara 1: Install via `requirements.txt`

```bash
pip install -r requirements.txt
```

### 🔧 Cara 2: Install satu per satu (jika mengalami kendala)
pip install nltk sastrawi google-play-scraper
pip install scikit-learn tensorflow
