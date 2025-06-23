# 🤖📊 Clustering Mahasiswa Berdasarkan Pengetahuan Etika AI

## 📝 Ringkasan Proyek

Proyek ini bertujuan untuk mengelompokkan mahasiswa berdasarkan pola penggunaan teknologi AI, kesadaran etika, serta integrasi nilai-nilai Islam dalam praktik teknologi menggunakan pendekatan *unsupervised learning* dengan algoritma **K-Means Clustering**.

## 📂 Dataset

- **Jumlah entri**: 89 responden (data survei)
- **Jenis data**: Survei tentang pengetahuan, sikap, dan penggunaan AI serta etika AI

## 📌 Clustering

- **Algoritma**: K-Means
- **Jumlah cluster**: 2
- **Evaluasi**:
  - **Silhouette Score**: `0.13`
  - **Visualisasi**: PCA (Principal Component Analysis) digunakan untuk proyeksi data ke 2D
- **Feature Importance**: Diidentifikasi melalui distribusi fitur dominan per cluster

## 🧠 Interpretasi Cluster

### 🔹 Cluster 0: *Engaged AI Ethicists and Power Users*

- Mahasiswa dengan penggunaan AI yang tinggi dan kesadaran etika yang kuat
- Peduli terhadap keselarasan AI dengan nilai-nilai Islam
- Menjadi agen perubahan potensial untuk literasi AI dan etika di lingkungan kampus

### 🔸 Cluster 1: *Pragmatic AI Users*

- Mahasiswa yang menggunakan AI secara pragmatis untuk keperluan akademik
- Kesadaran terhadap isu etika dan nilai-nilai Islam relatif rendah
- Mampu mengenali perbedaan hasil AI dan manusia, tetapi kurang menekankan pentingnya regulasi
