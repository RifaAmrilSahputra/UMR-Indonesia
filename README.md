# UMR-Indonesia

**Analisis dan Prediksi Upah Minimum Regional (UMR) di Indonesia 1997–2032**  

Repository ini berisi analisis data UMR di seluruh provinsi Indonesia dari tahun 1997 hingga 2022, serta prediksi UMR 10 tahun ke depan menggunakan model Linear Regression. Visualisasi mencakup tren tahunan, pertumbuhan, perbandingan antar provinsi/pulau, dan provinsi dengan UMR tertinggi.

---

## 📂 Struktur Dataset

- **Dataset:** `Indonesian Salary by Region (1997-2022)`
- **Kolom utama:**
  - `REGION` : Nama provinsi
  - `YEAR` : Tahun data
  - `SALARY` : Upah Minimum Regional (IDR)

---

## 🔧 Teknologi dan Library

- **Bahasa pemrograman:** Python & R  
- **Python libraries:**
  - `pandas`, `numpy` → manipulasi data  
  - `matplotlib`, `seaborn`, `plotly` → visualisasi data  
  - `scikit-learn` → Linear Regression untuk prediksi  
  - `warnings` → menonaktifkan peringatan  
- **R libraries (opsional):**
  - `tidyverse`, `skimr` → eksplorasi data

---

## 📊 Analisis yang Dilakukan

1. Eksplorasi data UMR per provinsi dan per pulau  
2. Visualisasi rata-rata UMR, UMR tertinggi, dan pertumbuhan tahunan  
3. Prediksi UMR 10 tahun ke depan (2023–2032) menggunakan **Linear Regression** per provinsi  
4. Visualisasi tren prediksi dan pertumbuhan UMR di masa depan  

---

## 🔄 Cara Menjalankan

1. Clone repository:

```bash
git clone https://github.com/username/UMR-Indonesia.git
```

2. Install dependencies:

```bash 
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```


3. Jalankan notebook Python (.ipynb) untuk melihat analisis dan visualisasi:

```bash
jupyter notebook UMR_Indonesia.ipynb
```

4. Dataset harus disimpan di folder yang sesuai, misal:

```bash
UMR-Indonesia/data/Indonesian Salary by Region (1997-2022).csv
```

---
## 📈 Visualisasi dan Output

- **Tren rata-rata UMR tiap provinsi/pulau**

- **Pertumbuhan tahunan UMR nasional**

- **Provinsi dengan UMR tertinggi**

- **Prediksi 10 tahun ke depan dengan Linear Regression**

- **Animasi interaktif UMR tiap provinsi (Plotly)**

💡 Insight yang Bisa Didapat

- **Provinsi dengan pertumbuhan UMR tercepat**

- **Tren gap UMR antar provinsi/pulau**

- **Prediksi UMR masa depan untuk perencanaan ekonomi/regional**

📌 Catatan

- **Model prediksi sederhana menggunakan Linear Regression**

- **Data prediksi bersifat estimasi, bukan nilai resmi pemerintah**
