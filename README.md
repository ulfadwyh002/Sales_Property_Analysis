# 🏠Analisis Pasar Properti Jabodetabek untuk Ekspansi Kantor Cabang RPPI
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jabodetabek](https://img.shields.io/badge/Jabodetabeks%20Property-3776AB?style=flat)
![Collaborative](https://img.shields.io/badge/Collaborative%20Project-3776AB?style=flat)
## 📌 Overview

Project ini merupakan analisis data properti di wilayah Jabodetabek yang dilakukan untuk memahami kondisi pasar properti, karakteristik harga antarwilayah, serta mengidentifikasi pertimbangan yang dapat digunakan dalam menentukan lokasi ekspansi kantor cabang. Analisis berfokus pada kualitas dan kesiapan data, perbedaan harga properti antarwilayah, serta karakteristik properti yang dapat mendukung proses pengambilan keputusan berbasis data.

## 🎯 Business Questions

1. Bagaimana kualitas dan karakteristik data properti yang tersedia?
2. Bagaimana perbedaan harga properti antarwilayah Jabodetabek?
3. Wilayah mana yang dapat menjadi alternatif pertimbangan untuk ekspansi kantor cabang berdasarkan kondisi pasar properti?

## 🔄 Metodologi

| Tahap                                  | Aktivitas                                                                                                                                                                                                                                                                                                                                                           |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Data Understanding**              | Memahami struktur dataset, variabel yang tersedia, serta kondisi awal dan karakteristik data.                                                                                                                                                                                                                                                                       |
| **2. Data Preprocessing**              | **Data Cleaning:** mengecek missing value, duplikasi, konsistensi format dan tipe data, serta kategori atau nilai yang tidak sesuai. <br><br> **Transformation:** menyeragamkan format dan satuan pada variabel yang diperlukan. <br><br> **Data Integration:** menggabungkan beberapa sumber data untuk memperoleh dataset yang lebih lengkap dan siap dianalisis. |
| **3. Exploratory Data Analysis (EDA)** | Menganalisis distribusi harga, karakteristik properti, serta perbedaan harga dan kondisi pasar antarwilayah Jabodetabek.                                                                                                                                                                                                                                            |
| **4. Dashboard**                       | Mengembangkan visualisasi interaktif untuk membantu menjawab Business Question 2 dan 3, terutama terkait perbandingan harga antarwilayah dan pertimbangan lokasi ekspansi.                                                                                                                                                                                          |

## 🔍 Key Findings

| Temuan                                                  | Insight                                                                                                                                                                                                           |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Kualitas data masih perlu ditingkatkan**              | Ditemukan proporsi *missing value* yang cukup tinggi pada beberapa kota, ketidakkonsistenan satuan pada variabel numerik, serta beberapa variabel yang belum memiliki definisi yang jelas, seperti luas bangunan. |
| **Jakarta memiliki harga properti tertinggi**           | Harga properti di Jakarta cenderung lebih tinggi dibandingkan Tangerang, Depok, dan Bekasi, menunjukkan adanya perbedaan karakteristik pasar antarwilayah.                                                        |
| **Depok menjadi salah satu alternatif lokasi ekspansi** | Depok memiliki posisi yang relatif strategis untuk menjangkau beberapa wilayah Jabodetabek, dengan harga properti yang cenderung lebih terjangkau dibandingkan Jakarta.                                           |

## 💡 Conclusion

Analisis menunjukkan bahwa **kualitas data merupakan salah satu aspek penting yang perlu diperhatikan sebelum digunakan sebagai dasar pengambilan keputusan**. Selain menemukan perbedaan harga yang cukup jelas antarwilayah, analisis juga menunjukkan bahwa wilayah dengan harga properti yang lebih terjangkau dapat menjadi alternatif yang perlu dipertimbangkan dalam strategi ekspansi.

Namun, keputusan ekspansi tidak sebaiknya hanya didasarkan pada harga properti. Faktor lain seperti aksesibilitas, target pasar, kepadatan penduduk, kompetitor, dan potensi pertumbuhan wilayah juga perlu dianalisis lebih lanjut.

## 🛠️ Tools

* **Python** — Data Cleaning & Exploratory Data Analysis
* **Pandas** — Data Manipulation
* **Matplotlib / Seaborn** — Data Visualization
* **Power BI / Tableau** — Interactive Dashboard
* **Excel** — Data Exploration & Validation


## 💡 Insight Utama

- **Kualitas data memengaruhi keandalan analisis.** Missing value yang tinggi, satuan yang tidak seragam, dan definisi variabel yang tidak jelas membatasi tingkat kepercayaan terhadap hasil analisis.
- **Terdapat perbedaan harga yang jelas antarwilayah.** Jakarta berada di segmen harga tertinggi, sedangkan Tangerang, Depok, dan Bekasi relatif lebih terjangkau.
- **Kombinasi lokasi strategis dan harga terjangkau menjadikan Depok kandidat yang menarik** untuk kantor cabang berikutnya.

