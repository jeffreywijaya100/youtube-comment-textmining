# **YouTube Comment Text Mining — Public Sentiment Analysis Toward Machine Learning**

Dalam proyek ini, saya mengeksplorasi persepsi publik mengenai machine learning melalui analisis komentar berbahasa Indonesia dari video YouTube. Tujuan utama dari studi ini adalah memahami topik, opini, dan kata kunci yang paling sering dibahas oleh audiens untuk mendapatkan insight mengenai awareness, antusiasme, dan tantangan yang dirasakan masyarakat terkait machine learning.

## Tahapan Pengerjaan

### 1. Scraping Komentar YouTube

- Mengambil lebih dari 100 komentar dari ≥ 5 video YouTube yang berkaitan dengan topik machine learning dalam bahasa Indonesia.

- Proses scraping dilakukan menggunakan YouTube API / library scraping untuk mengumpulkan teks komentar secara realtime.

### 2. Data Pre-processing
   
Cleaning teks dilakukan agar model dapat membaca konten secara lebih akurat, meliputi:

- Case folding & cleansing (menghapus angka, URL, emoji, karakter spesial)

- Tokenization

- Stopword removal

- Lemmatization untuk mengubah kata ke bentuk dasar sesuai tata bahasa Indonesia

### 3. Exploratory Text Analysis

- Melakukan perhitungan frekuensi kata untuk mengetahui istilah yang paling sering dibahas audiens

- Visualisasi menggunakan Word Cloud untuk menonjolkan kata-kata yang paling sering muncul dalam komentar

### 4. Text Vectorization
   
Untuk mempersiapkan data ke tahap machine learning atau analisis lanjutan, digunakan 2 metode representasi teks:

- TF-IDF (Term Frequency — Inverse Document Frequency)

- Bag of Words (BoW)

Hasil menunjukkan variasi bobot kata dan hubungan antar komentar menjadi lebih mudah dianalisis setelah vectorization.

## Insight Utama

Berdasarkan chart yang telah di diproses, kita mendapati bahwa "nya" menjadi kata yang paling sering muncul dalam text/comment, disusul oleh kasih dan terima

Meskipun video yang diproses berkaitan dengan machine learning, akan tetapi 'nya' yang muncul pertama, meskipun bukan kata dasar dan merupakan akhiran tapi bisa paling banyak muncul

Selain itu, dapat dilihat behavior masyarakat indonesia ketika berkomentar mengenai video edukasi yang mayoritas mengucapkan terima kasih. Hal ini kembali lagi, tergantung dari text yang diambil, jumlah text yang dapat diambil, dan karena video tentang edukasi, berbeda video menghasilkan comment yang berbeda juga

## Impact / Business Value

Analisis text mining dari komentar YouTube ini dapat memberikan nilai nyata dalam konteks bisnis dan pengembangan produk edukasi berbasis AI, di antaranya:

✔ Brand & Content Strategy Improvement
Creator, penyedia kursus, dan institusi edukasi dapat mengetahui topik yang paling diminati untuk menentukan konten pembelajaran yang relevan dan tepat sasaran.

✔ Market Needs Identification
Insight dari komentar dapat membantu perusahaan ed-tech memahami kebutuhan audiens—misal: banyaknya komentar bertanya tentang materi untuk pemula dapat menjadi sinyal kebutuhan kelas beginner-friendly.

✔ Product Development untuk Platform Edukasi
Output text vectorization dapat dikembangkan lebih jauh ke sistem klasifikasi komentar, sentiment analysis, atau rekomendasi konten pembelajaran berbasis minat audiens.

✔ Customer Voice Understanding
Dapat dijadikan referensi untuk voice of customer (VoC) dalam pengembangan kurikulum dan strategi pemasaran teknologi.
