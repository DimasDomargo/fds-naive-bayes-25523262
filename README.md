# Praktikum Naïve Bayes Classifier (E1–E3)

Repositori ini berisi hasil pengerjaan tugas praktikum Fundamen Sains Data (16-Praktik Naïve Bayes) yang mencakup penerapan berbagai varian algoritma Naïve Bayes pada data tabular, data teks, dan data kesehatan yang tidak seimbang (imbalanced dataset).

Daftar Isi Notebook

E1 – Naïve Bayes untuk Data Tabular (GaussianNB)

Dataset: Palmer Penguins.

Fokus: Memprediksi spesies penguin berdasarkan pengukuran fisik (panjang paruh, kedalaman paruh, panjang sirip, dan berat tubuh).

Latihan: Membandingkan performa model empat fitur dengan model fitur tunggal (flipper_length_mm) serta memprediksi spesies data penguin baru beserta probabilitasnya.

E2 – Naïve Bayes untuk Data Teks (MultinomialNB & BernoulliNB)

Dataset: SMS Spam Collection (5.572 pesan teks).

Fokus: Mengklasifikasikan pesan SMS ke dalam kategori ham (normal) atau spam menggunakan teknik ekstraksi fitur Bag of Words (CountVectorizer).

Latihan: Membandingkan performa MultinomialNB (berbasis frekuensi kata) dengan BernoulliNB (berbasis kemunculan biner kata) serta menguji model pada pesan SMS buatan sendiri.

E3 – Naïve Bayes untuk Prediksi Diabetes (GaussianNB pada Imbalanced Data)

Dataset: Diabetes Prediction Dataset (100.000 catatan medis pasien).

Fokus: Mengevaluasi model pada dataset dengan kelas tidak seimbang (hanya ~8,5% kasus positif) dan memahami mengapa metrik Recall lebih krusial dibandingkan sekadar Accuracy dalam konteks skrining medis.

Latihan: Membandingkan efektivitas fitur tunggal HbA1c_level dan blood_glucose_level terhadap model enam fitur lengkap.

Teknologi & Pustaka yang Digunakan

Bahasa Pemrograman: Python 3

Lingkungan Kerja: Google Colaboratory

Pustaka Utama:

scikit-learn (GaussianNB, MultinomialNB, BernoulliNB, CountVectorizer, train_test_split, classification_report, ConfusionMatrixDisplay)

pandas (Manipulasi dan pemuatan data tabular)

matplotlib (Visualisasi distribusi data dan confusion matrix)
