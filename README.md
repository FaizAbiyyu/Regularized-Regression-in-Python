# Regularized Regression in Python

## Deskripsi Proyek

Proyek ini menjelaskan implementasi *Regularized Regression* menggunakan Python. Teknik ini berguna untuk mencegah overfitting pada model regresi dengan menambahkan penalti pada parameter model. Dalam repositori ini, Anda akan mempelajari bagaimana menggunakan **Ridge Regression** dan **Lasso Regression** untuk mengelola kompleksitas model dan meningkatkan performa prediksi.

Regularized regression banyak digunakan dalam analisis data dan pembelajaran mesin untuk menangani dataset dengan jumlah fitur yang besar atau memiliki korelasi antar-fitur yang tinggi.

## Fitur

- **Implementasi Ridge Regression** menggunakan penalti L2.
- **Implementasi Lasso Regression** menggunakan penalti L1.
- Visualisasi koefisien regresi untuk membandingkan hasil dengan regresi linier biasa.
- Pengujian dan evaluasi performa model pada dataset simulasi.

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/FaizAbiyyu/Regularized-Regression-in-Python.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd Regularized-Regression-in-Python
   ```
3. Install dependensi menggunakan `pip`:
   ```bash
   pip install -r requirements.txt
   ```

## Penggunaan

1. Jalankan *notebook* Jupyter untuk mempelajari implementasi langkah demi langkah:
   ```bash
   jupyter notebook notebooks/regularized_regression.ipynb
   ```
2. Jika ingin menjalankan skrip secara langsung:
   ```bash
   python scripts/run_regression.py
   ```

## Hasil Visualisasi

Repositori ini menyertakan visualisasi seperti:

- Hubungan antara penalti regulasi dan koefisien model.
- Perbandingan performa model regulasi vs model regresi linier biasa.

## Teknologi yang Digunakan

- Python 3.8 atau lebih baru
- Library:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
