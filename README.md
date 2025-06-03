# RecommendationSystem – Proyek Machine Learning Terapan

Proyek ini bertujuan untuk merancang dan mengembangkan model pembelajaran mesin yang dapat memberikan rekomendasi Anime kepada seseorang berdasarkan dataset yang diberikan.

## Struktur Proyek

- **RecommendationSystem.ipynb** → Notebook yang berisi eksplorasi data, persiapan dataset, serta eksperimen yang dilakukan dengan masing-masing model.
- **Laporan_Recommendation-System.md** → Laporan dokumentasi yang berisi analisis dan kesimpulan dan hasil dari proyek.
- **anime.csv**, **rating.csv** → Dataset yang digunakan dalam proyek ini
- **requirements.txt** → Daftar paket dan dependensi yang perlu diinstal untuk menjalankan proyek.
- **images/** → Folder yang menyimpan gambar-gambar yang digunakan dalam laporan untuk mendukung visualisasi analisis.

## Tujuan Proyek

- Menggunakan pendekatan **Collaborative Filtering** dengan membandingkan dua arsitektur model untuk memprediksi rating anime.
- Membangun model **Matrix Factorization** (`RecommenderNet`) sebagai _baseline_, yang menggunakan _dot product_ antara _embedding_ pengguna dan anime.
- Mengimplementasikan model **Neural Matrix Factorization (NeuMF)** yang menggabungkan jalur linear (GMF) dan non-linear (MLP) untuk menangkap pola preferensi yang lebih kompleks.
- Mengevaluasi kedua model menggunakan metrik **Root Mean Squared Error (RMSE)** dan **Mean Absolute Error (MAE)** untuk menentukan akurasi prediksi rating.
