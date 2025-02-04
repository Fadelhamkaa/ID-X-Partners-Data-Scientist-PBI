# ID-X-Partners-Data-Scientist-PBI

# Proyek Prediksi Risiko Kredit

## Deskripsi Proyek

Proyek ini merupakan tugas akhir dari program internship Data Scientist di ID/X Partners. Tujuannya adalah membangun model machine learning untuk memprediksi risiko kredit calon peminjam berdasarkan dataset pinjaman yang disediakan.  Proyek ini berfokus pada pengembangan solusi end-to-end, mulai dari pemahaman data, eksplorasi data, persiapan data, pemodelan, hingga evaluasi dan penyimpulan. Model yang dihasilkan diharapkan dapat membantu perusahaan pemberi pinjaman (multifinance) dalam membuat keputusan pemberian pinjaman yang lebih akurat dan mengurangi potensi kerugian akibat kredit macet.

## Metodologi

Proyek ini mengikuti metodologi Data Science yang umum, meliputi tahapan-tahapan berikut:

1. **Data Understanding:** Memahami karakteristik data, variabel-variabel yang terlibat, dan tujuan bisnis.  Tahap ini meliputi analisis deskriptif dan identifikasi potensi masalah dalam data.
2. **Exploratory Data Analysis (EDA):** Menjelajahi data lebih lanjut dengan visualisasi dan analisis statistik untuk mengidentifikasi pola, tren, dan hubungan antar variabel.  EDA membantu dalam memahami lebih dalam karakteristik data dan  menemukan insight yang berguna untuk pemodelan.
3. **Data Preparation:** Mempersiapkan data untuk pemodelan, termasuk penanganan missing values, outlier, encoding variabel kategorikal, dan scaling/normalisasi data numerik.  Data yang bersih dan terstruktur dengan baik sangat penting untuk performa model yang optimal.
4. **Data Modelling:**  Membangun model prediktif menggunakan algoritma machine learning.  Dalam proyek ini, digunakan algoritma Logistic Regression dan Random Forest. Pemilihan model didasarkan pada karakteristik data dan tujuan bisnis.  Proses ini juga meliputi tuning hyperparameter untuk mengoptimalkan performa model.
5. **Evaluation:** Mengevaluasi performa model menggunakan metrik yang relevan seperti akurasi, presisi, recall, F1-score, dan AUC.  Evaluasi dilakukan pada data testing yang terpisah untuk memastikan generalisasi model.
6. **Deployment & Monitoring (Opsional):**  Meskipun tidak diimplementasikan dalam proyek ini, idealnya model yang telah dievaluasi akan di-deploy dan di-monitoring performanya secara berkala untuk memastikan model tetap relevan dan akurat.


## Dataset

Dataset yang digunakan dalam proyek ini adalah "Loan Dataset" yang berisi informasi tentang pinjaman yang telah diberikan, termasuk data demografis peminjam, informasi pinjaman, dan status pinjaman (baik/macet).  Data dictionary yang menjelaskan setiap variabel dalam dataset juga disertakan.

## Tools dan Teknologi

- Bahasa Pemrograman: Python
- Library: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Environment: Jupyter Notebook / Google Colab


## File yang Diberikan

- `VIX IDX Partners ppt.pdf`:  Presentasi yang merangkum keseluruhan proyek, metodologi, hasil analisis, dan rekomendasi.
- `loan_data.ipynb`: Notebook Jupyter yang berisi kode Python untuk analisis data, pemodelan, dan evaluasi.



## Rekomendasi

Beberapa rekomendasi untuk pengembangan selanjutnya antara lain:

- Mencoba algoritma machine learning lain untuk membandingkan performa.
- Melakukan feature engineering untuk meningkatkan akurasi model.
- Mengumpulkan lebih banyak data untuk melatih model yang lebih robust.


## Kontributor

Muhammad Fadel Hamka

