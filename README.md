Sistem Prediksi Kelulusan Mahasiswa

Deskripsi

Sistem Prediksi Kelulusan Mahasiswa merupakan aplikasi berbasis web sederhana yang dibuat menggunakan Python dan Streamlit. Aplikasi ini digunakan untuk memprediksi status kelulusan mahasiswa berdasarkan data IPK dan total SKS yang dimasukkan oleh pengguna.

Tujuan

Membangun aplikasi prediksi kelulusan mahasiswa dengan menerapkan arsitektur 4 layer, yaitu View Layer, Service Layer, Repository Layer, dan Model Layer.

Teknologi yang Digunakan

Python

Streamlit

SQLAlchemy

SQLite

Pandas

Python Dotenv

Struktur Proyek

Sistem-Prediksi-Kelulusan/
├── app.py
├── .env
├── .gitignore
├── requirements.txt
├── models/
│   └── model.py
├── repositories/
│   └── repository.py
└── services/
    └── service.py

Fitur Aplikasi

Input nama mahasiswa.

Input IPK.

Input total SKS.

Menampilkan hasil prediksi kelulusan.

Menyimpan data prediksi.

Menampilkan riwayat prediksi.

Cara Menjalankan Aplikasi

Clone repository:

git clone https://github.com/muhyi215809-creator/Sistem-Prediksi-Kelulusan.git

Masuk ke folder proyek:

cd Sistem-Prediksi-Kelulusan

Instal dependensi:

pip install -r requirements.txt

Jalankan aplikasi:

python -m streamlit run app.py

Database

Aplikasi menggunakan SQLite sebagai database dan SQLAlchemy untuk mengelola interaksi dengan database.
