# Laporan Proyek Machine Learning Laptop Price Analysis
Disusun oleh : Batara Helda Firdauzy
## Domain Proyek
### Latar Belakang
Laptop merupakan kebutuhan sekunder yang dibutuhkan oleh banyak bidang pekerjaan pada saat ini. Laptop memiliki nilai yang bergantung pada spesifikasi dan fitur dari laptop itu sendiri. 

<div><img src="https://github.com/Batarahelda/Laptop_Price_Analysis/assets/125903321/7711d15d-88d7-4c40-999a-dee7ecf4e243" width="750"/></div>

[Referensi Gambar](https://www.pngegg.com/id/png-zgbuq/download) 

Dalam mencapai hal tersebut, maka dilakukan penelitian untuk memprediksi harga laptop menggunakan model machine learning. Diharapkan model ini mampu memprediksi harga laptop yang sesuai dengan harga pasar. Prediksi ini nantinya dijadikan acuan bagi perusahaan dalam pembelian laptop dengan harga yang dapat mendatangkan profit bagi perusahaan.

## Business Understanding

### Problem Statements

1. Spesifikasi apa saja yang mempengaruhi harga dari laptop?
2. Berapa harga laptop dengan spesifikasi tertentu?

### Goals

Menjelaskan tujuan dari pernyataan masalah:
1. Mengetahui spesifikasi-spesifikasi yang dapat mempengaruhi harga dari laptop
2. Membuat model machine learning yang dapat memprediksi harga laptop dengan spesifikasi tertentu

### Solution statements
1. Menganalisis data dengan melakukan univariate analysis dan multivariate analysis. Memahami data juga dapat dilakukan dengan visualisasi. Memahami data dapat membantu untuk mengetahui kolerasi antar fitur.
2. Melakukan hyperparameter tuning menggunakan grid search dan membangun model regresi yang dapat memprediksi bilangan kontinu. ALgoritma yang dipakai dalam proyek ini adalah K-Nearest Neighbour, Random Forest, dan AdaBoost.

## Data Understanding

Dataset yang digunakan dalam proyek ini merupakan data harga laptop dengan berbagai spesifikasi dan berbagai merek. Dataset ini dapat diunduh pada [Kaggle : Laptop Price Analysis](https://www.kaggle.com/datasets/aemyjutt/laptop-price-analysis/data)

Berikut informasi pada Dataset :
- Dataset memiliki format CSV (Comma-Seperated Values).
- Dataset memiliki 4746 sample dengan 13 fitur.
- Dataset memiliki 1 fitur bertipe float64 dan 12 fitur bertipe object.
- Tidak ada missing value dalam dataset

### Variabel-variabel pada Dataset
- Manufacturer : Merek laptop.
- Model Name : Tipe model laptop.
- Category : Kategori laptop.
- Screen Size : Ukuran layar laptop.
- Screen : Tipe layar pada laptop.
- CPU : Tipe prossesor yang digunakan pada laptop.
- RAM : RAM yang digunakan pada laptop.
- Storage : Penyimpanan pada laptop.
- GPU : Graphic Card yang digunakan pada laptop.
- Operating System : Operating System yang digunakan pada laptop.
- Operating Sytem Version : Versi Operating System pada laptop.
- Weight : Berat laptop.
- Price : Harga laptop.

### Unvariate Analysis

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. Anda perlu menjelaskan tahapan dan parameter yang digunakan pada proses pemodelan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan kelebihan dan kekurangan dari setiap algoritma yang digunakan.
- Jika menggunakan satu algoritma pada solution statement, lakukan proses improvement terhadap model dengan hyperparameter tuning. **Jelaskan proses improvement yang dilakukan**.
- Jika menggunakan dua atau lebih algoritma pada solution statement, maka pilih model terbaik sebagai solusi. **Jelaskan mengapa memilih model tersebut sebagai model terbaik**.

## Evaluation
Pada bagian ini anda perlu menyebutkan metrik evaluasi yang digunakan. Lalu anda perlu menjelaskan hasil proyek berdasarkan metrik evaluasi yang digunakan.

Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan
- Menjelaskan hasil proyek berdasarkan metrik evaluasi

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.

