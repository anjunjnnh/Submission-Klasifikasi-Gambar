# Submission-Klasifikasi-Gambar

Ini adalah proyek submission untuk kelas **Belajar Pengembangan Machine Learning** dari Dicoding. Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan TensorFlow dan Keras.

## 📁 Dataset

Dataset yang digunakan adalah dataset gambar yang sudah dipisahkan ke dalam folder `train`, `validation`, dan `test`. Setiap folder berisi subfolder yang merepresentasikan kelas dari gambar.


## 🧠 Model

Model dikembangkan menggunakan arsitektur CNN sederhana yang dibangun dengan TensorFlow dan Keras. Arsitektur model terdiri dari:

- Beberapa lapisan `Conv2D` dan `MaxPooling2D`
- Lapisan `Flatten`
- Fully Connected layer (`Dense`)
- Lapisan output dengan aktivasi `softmax`

Selain itu, digunakan juga teknik augmentasi data dan callback seperti `EarlyStopping` 

## 🛠️ Tools dan Library

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## 📈 Hasil Evaluasi

Model berhasil mencapai akurasi:
- Akurasi pada data validation: **98%**
- Akurasi pada data test: **97%**

> *Catatan: Angka disesuaikan dengan hasil aktual dari model.*

## 📄 Lisensi

Proyek ini bebas digunakan untuk keperluan pembelajaran.
