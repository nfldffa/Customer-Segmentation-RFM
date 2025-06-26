# Analisis Segmentasi Pelanggan dengan RFM & K-Means

![Gradio App Screenshot](![Image](https://github.com/user-attachments/assets/7bdefa36-7d85-4a7b-a128-b5ee14dc5c69))

Sebuah proyek data mining untuk mengelompokkan pelanggan berdasarkan perilaku pembelian mereka dan membuat demo interaktif menggunakan Gradio.

## Demo Langsung 🚀

Anda bisa mencoba aplikasi interaktifnya langsung di sini:
**[Link Demo Gradio di Hugging Face Spaces (akan diisi nanti)]**

---

## Latar Belakang

Dalam dunia bisnis, tidak semua pelanggan itu sama. Memahami perbedaan perilaku pelanggan adalah kunci untuk strategi pemasaran yang efektif. Proyek ini bertujuan untuk menyelesaikan masalah tersebut dengan melakukan segmentasi pelanggan menggunakan data transaksi historis.

## Alur Kerja Proyek
1.  **Pembersihan & Eksplorasi Data:** Memuat dataset transaksi, menangani nilai yang hilang dan duplikat, serta melakukan analisis data eksploratif (EDA).
2.  **Analisis RFM:** Menghitung skor **Recency**, **Frequency**, dan **Monetary** untuk setiap pelanggan.
3.  **Pra-pemrosesan & Clustering:** Melakukan transformasi log dan standardisasi pada data RFM, lalu menggunakan algoritma **K-Means** untuk mengelompokkan pelanggan ke dalam 4 segmen.
4.  **Interpretasi & Visualisasi:** Menganalisis karakteristik setiap segmen yang terbentuk dan memvisualisasikannya dalam scatter plot.
5.  **Pembuatan Aplikasi Demo:** Membangun antarmuka web yang sederhana dan interaktif menggunakan **Gradio** agar hasil model dapat diuji oleh siapa saja.

## Teknologi yang Digunakan
- **Analisis Data:** Python, Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Visualisasi:** Matplotlib, Seaborn
- **UI/Demo:** Gradio

## Hasil Visualisasi
Berikut adalah hasil pengelompokan pelanggan ke dalam 4 segmen:
![Customer Segmentation Plot](URL_SCREENSHOT_PLOT_ANDA)

---
