# Eksplorasi Data: Konsumsi Energi Peralatan Rumah (IoT)

Analisis eksplorasi data (EDA) dataset **Appliances Energy Prediction** (UCI) menggunakan Python.

## Tujuan
Memahami pola konsumsi listrik peralatan rumah berdasarkan data sensor suhu, kelembapan, dan cuaca.

## Dataset
- Sumber: UCI Machine Learning Repository
- 19.735 baris x 29 kolom, interval 10 menit

## Temuan Utama
- Puncak konsumsi pukul 18.00 (~190 Wh), terendah dini hari (~48 Wh)
- Distribusi miring ke kanan dengan ~10,8% outlier
- Korelasi antar fitur lemah (maks ~0,22)

## Struktur Repo
- `eda.ipynb` : notebook analisis
- `energydata_complete.csv` : dataset
- `gambar/` : hasil visualisasi

## Cara Menjalankan
pip install pandas matplotlib seaborn
jupyter notebook eda.ipynb

## Teknologi
Python, pandas, matplotlib, seaborn

## Penulis
Edga - D3 Teknik Komputer, POLSRI
Artikel Medium: [tambahkan link]
