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
📦 Sentiment-Analysis-Indodax ┣ 📂 Dataset/ ┃ ┣ 📄 indodax_reviews.csv <- Dataset hasil scraping ┃ ┗ 📄 slang.json <- Kamus slang untuk normalisasi ┣ 📄 Scraping_Indodax.ipynb <- Notebook scraping review dari Google Play ┣ 📄 Sentiment_indodax.ipynb <- Notebook utama analisis sentimen ┣ 📄 requirements.txt <- Daftar dependensi proyek ┗ 📄 README.md <- Dokumentasi proyek ini
