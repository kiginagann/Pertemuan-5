# Loan Approval Classifier
### Deskripsi
Proyek ini merupakan bagian dari tugas mata kuliah Machine Learning yang bertujuan untuk membangun model klasifikasi guna memprediksi persetujuan pinjaman berdasarkan berbagai faktor. Dataset yang digunakan dianalisis melalui tahapan eksplorasi, pemrosesan, pemilihan model, evaluasi, dan tuning hyperparameter.

### Struktur Proyek

1. Eksplorasi Data. Mencakup identifikasi missing values dalam dataset serta visualisasi data untuk memahami distribusi dan pola yang terdapat di dalamnya.

2. Pemrosesan Data. Data yang digunakan diproses melalui beberapa langkah, termasuk encoding fitur kategorikal, normalisasi fitur numerik, serta pembagian dataset menjadi training set dan testing set dengan proporsi 80:20.

3. Pemilihan dan Training Model. dipilih minimal dua algoritma Machine Learning yang berbeda (saya memilih Logistic Regression, Random Forest,  SVM,  XGBoost Classifier). Model kemudian dilatih menggunakan dataset yang telah diproses.

4. Evaluasi Model. Performa model dibandingkan menggunakan berbagai metrik evaluasi (akurasi, precision, recall, dan F1-score). Model dengan performa terbaik dipilih untuk tahap tuning.

5. Tuning Model dengan Grid Search untuk menemukan kombinasi hyperparameter terbaik. Kombinasi hyperparameter terbaik yang diperoleh kemudian disajikan dalam hasil akhir.

6. Perbandingan Performa Sebelum dan Sesudah Tuning. Hasil evaluasi model sebelum dan sesudah tuning dibandingkan untuk menilai efektivitas optimasi yang telah dilakukan dalam meningkatkan performa model.

### Hasil dan Evaluasi
- Model terbaik setelah tuning mencapai **59%** akurasi dengan peningkatan dari **53%** sebelum tuning.  
- Peningkatan recall kelas **1** dari **63%** menjadi **92%** menunjukkan bahwa model lebih baik dalam mendeteksi sampel positif setelah optimasi hyperparameter.
