# Analisis Pola Transaksi _E-Commerce_ dengan Apache Spark (PySpark)

Mata Kuliah **Infrastruktur dan Teknologi Big Data**  
Program Studi **S1 Sains Data**  
Fakultas Informatika – Universitas Telkom  
Tahun 2025

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data transaksi _e-commerce_ menggunakan pendekatan _Big_ Data _Analytics_ dengan memanfaatkan Apache Spark (PySpark).  
Analisis yang dilakukan mencakup:
- Tren transaksi dan _revenue_ dari waktu ke waktu
- Distribusi kategori produk, negara pelanggan, dan metode pembayaran
- Segmentasi pelanggan menggunakan algoritma K-Means _Clustering_

Proyek ini dirancang untuk mensimulasikan _pipeline_ Big Data mulai dari data _ingestion_, _preprocessing_, analisis, hingga visualisasi hasil.

## _Dataset_
_Dataset_ yang digunakan berasal dari Kaggle:

- **Jumlah Data**: ±50.000 transaksi  
- **Periode Data**: Maret 2023 – Maret 2025  
- **Format**: CSV  

Link dataset:  
https://www.kaggle.com/datasets/smayanj/e-commerce-transactions-dataset

### Fitur Utama
- Transaction_ID
- User_Name
- Age
- Country
- Product_Category
- Purchase_Amount
- Payment_Method
- Transaction_Date

## _Tools_ & Teknologi
- Apache Spark (PySpark)
- _Hadoop Distributed File System_ (HDFS)
- Spark MLlib
- Python
- Pandas & Matplotlib (visualisasi)
- Google Colab / Local Spark

## Alur _Pipeline_ Big Data
1. **Data _Ingestion_** -> Dataset CSV diunggah ke HDFS
3. **Data Preprocessing** -> Penyimpanan Data dalam format _Parquet_
4. **Analisis Data (PySpark)**
5. **Machine Learning** -> Menggunakan **K-Means Clustering**
7. **Visualisasi**

## Hasil Singkat
1. Terlihat tren peningkatan transaksi per tahun
2. Kontribusi _revenue_ antar kategori relatif merata
3. Pelanggan tersebar di berbagai negara
4. Segmentasi pelanggan berhasil membedakan perilaku belanja
