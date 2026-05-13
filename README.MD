# WebGIS Potensi Likuifaksi

Project ini merupakan visualisasi spasial potensi likuifaksi berdasarkan data Standard Penetration Test (SPT) menggunakan Python dan GitHub Pages. Analisis dilakukan dengan menghitung parameter CSR (Cyclic Stress Ratio), CRR (Cyclic Resistance Ratio), dan Factor of Safety (FS) untuk mengidentifikasi zona tanah yang rentan terhadap likuifaksi akibat gempa bumi.

---

## Tujuan Project

- Mengolah data SPT menjadi parameter analisis likuifaksi
- Menghitung nilai FS pada setiap titik borehole
- Memvisualisasikan distribusi spasial nilai FS
- Membuat WebGIS interaktif berbasis Python

---

## Workflow Analisis

```text
Data SPT
↓
Perhitungan Tegangan Total & Efektif
↓
Perhitungan CSR
↓
Koreksi N-SPT menjadi (N1)60cs
↓
Perhitungan CRR
↓
Perhitungan Factor of Safety (FS)
↓
Plotting Spasial & Interpolasi
↓
Visualisasi WebGIS
```

---

## Hasil Interpolasi Spasial

Visualisasi distribusi spasial nilai Factor of Safety (FS) berdasarkan hasil interpolasi dari titik borehole.

![Interpolasi FS](interpolasi_fs.png)

---

## Fitur Utama

- Visualisasi titik borehole pada peta interaktif
- Popup informasi nilai FS tiap titik
- Klasifikasi zona aman dan rentan likuifaksi
- Interpolasi spasial nilai FS
- Grafik analisis CSR vs CRR
- Grafik profil FS terhadap kedalaman

---

## Teknologi yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Folium
- Scipy
- GeoPandas
- GitHub Pages

---

## Akses WebGIS

Klik link berikut untuk membuka WebGIS:

https://kiralrafa.github.io/likuifaksi-webgis-AhmadSamy-KiralRafa/

---

## Dataset

Data hasil pengolahan dan data pendukung dapat diakses melalui link berikut:

https://drive.google.com/drive/folders/1MykhOUAoMLhA9axRZvcafibx8tHebOw1?usp=sharing

---

## Referensi

Referensi jurnal, paper, dan sumber pendukung analisis dapat diakses melalui link berikut:

https://drive.google.com/drive/folders/1BotLMHBZZrhfzORJOqqovnUy4UY7X9CK?usp=sharing

---

## Struktur Project

```text
README.md
index.html
Project_Komputasi.ipynb
Data_hasil_likuifaksi.xlsx
interpolasi_fs.png
```

---

## Author

- Kiral Rafa
- Ahmad Samy
