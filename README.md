# 📘 Data Science Summary - UTS Preparation

Ringkasan ini mencakup tahapan penting dalam proses analisis data dan klasifikasi menggunakan Python, Pandas, Matplotlib, serta algoritma Naive Bayes dan Decision Tree. Cocok untuk mahasiswa atau praktisi pemula yang ingin memahami dasar alur kerja data science.

---

## 🧰 1. Data Preparation dengan Pandas
- `pd.read_csv()`: Membaca dataset
- `df.info(), df.describe()`: Melihat ringkasan data
- `df.dropna()`: Menghapus nilai kosong
- `astype()`, `value_counts()`: Konversi dan eksplorasi label

---

## 📊 2. Visualisasi Data dengan Matplotlib & Seaborn
- `plt.plot(), sns.countplot()`: Visualisasi distribusi data
- `sns.heatmap()`: Menampilkan korelasi atau confusion matrix
- Membantu memahami struktur dan distribusi data sebelum modeling

---

## 🧠 3. Naive Bayes Classifier
- Algoritma berbasis probabilitas Bayes
- Asumsi: fitur saling independen
- Sangat cepat untuk prediksi awal
- Digunakan: `GaussianNB()` dari Scikit-learn

---

## 🌳 4. Decision Tree Classifier
- Algoritma klasifikasi berbasis pohon keputusan
- Menggunakan `DecisionTreeClassifier()`
- Bisa divisualisasikan dengan `plot_tree()`
- Kelebihan: mudah dipahami dan ditafsirkan

---

## 📈 5. Evaluasi Model
- **Confusion Matrix**: Menilai akurasi prediksi
- **Classification Report**: Precision, Recall, F1-score
- Membandingkan performa antara model Naive Bayes dan Decision Tree

---

## 📂 File Terkait
- `summary_uts_datascience.ipynb`: Notebook Jupyter berisi ringkasan & contoh kode
- Dataset dapat diunduh dari: [CIC Tabular IoT Attack 2024](https://www.yorku.ca/research/bccc/ucs-technical/cybersecurity-datasets-cds/)

---

## 🚀 Catatan
Proyek ini merupakan bagian dari latihan dan persiapan UTS mata kuliah Data Science. Dapat dijadikan portofolio awal untuk menunjukkan pemahaman dasar analisis data dan machine learning sederhana.

