# WebGIS Potensi Likuifaksi

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Folium](https://img.shields.io/badge/Folium-WebGIS-green)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Spatial%20Analysis-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-black?logo=github)

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

## Lokasi Penelitian

Area penelitian berada pada wilayah investigasi geoteknik dengan beberapa titik borehole yang digunakan sebagai dasar analisis potensi likuifaksi dan pemetaan spasial nilai Factor of Safety (FS).

---

## Metode Analisis

Analisis likuifaksi dilakukan menggunakan pendekatan empiris Seed & Idriss dengan parameter utama:

- Cyclic Stress Ratio (CSR)
- Cyclic Resistance Ratio (CRR)
- Factor of Safety (FS)

Persamaan utama yang digunakan:

```text
FS = CRR / CSR
```

Interpretasi dilakukan berdasarkan hubungan antara beban siklik gempa dan kapasitas tahanan tanah terhadap likuifaksi.

---

## Klasifikasi Factor of Safety

| Nilai FS | Interpretasi |
|----------|---------------|
| FS < 1   | Rentan Likuifaksi |
| FS ≥ 1   | Aman |

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

[![Open WebGIS](https://img.shields.io/badge/Open-WebGIS-blue?style=for-the-badge&logo=github)](https://kiralrafa.github.io/likuifaksi-webgis-AhmadSamy-KiralRafa/)

---

## Dataset

[![Open Dataset](https://img.shields.io/badge/Open-Dataset-success?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1MykhOUAoMLhA9axRZvcafibx8tHebOw1?usp=sharing)

---

## Referensi

[![Open References](https://img.shields.io/badge/Open-References-orange?style=for-the-badge&logo=googledrive)](https://drive.google.com/drive/folders/1BotLMHBZZrhfzORJOqqovnUy4UY7X9CK?usp=sharing)

---

## Struktur Repository

```text
README.md
index.html
Project_Komputasi.ipynb
Data_hasil_likuifaksi.xlsx
```

---

## Future Development

- Integrasi interpolasi langsung pada WebGIS interaktif
- Penambahan layer geologi regional
- Export hasil analisis ke format GeoJSON dan Shapefile
- Pengembangan visualisasi 3D bawah permukaan
- Analisis multi-depth liquefaction mapping

---

## Author

- Kiral Rafa
- Ahmad Samy
