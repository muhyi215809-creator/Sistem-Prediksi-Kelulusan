# Sistem Prediksi Kelulusan Mahasiswa

## Deskripsi

Sistem Prediksi Kelulusan Mahasiswa merupakan aplikasi berbasis web sederhana yang dibuat menggunakan Python dan Streamlit. Aplikasi ini digunakan untuk memprediksi status kelulusan mahasiswa berdasarkan data IPK dan total SKS yang dimasukkan oleh pengguna.

## Tujuan

Membangun aplikasi prediksi kelulusan mahasiswa dengan menerapkan arsitektur 4 layer, yaitu View Layer, Service Layer, Repository Layer, dan Model Layer.

## Teknologi yang Digunakan

- Python
- Streamlit
- SQLAlchemy
- SQLite
- Pandas
- Python Dotenv

## Struktur Proyek

```text
Sistem-Prediksi-Kelulusan/
├── app.py
├── .gitignore
├── requirements.txt
├── models/
│   └── model.py
├── repositories/
│   └── repository.py
└── services/
    └── service.py
```

## Fitur Aplikasi

- Input nama mahasiswa.
- Input IPK.
- Input total SKS.
- Menampilkan hasil prediksi kelulusan.
- Menyimpan data prediksi.
- Menampilkan riwayat prediksi.

## Cara Menjalankan Aplikasi

**1. Clone repository**

```bash
git clone https://github.com/muhyi215809-creator/Sistem-Prediksi-Kelulusan.git
```

**2. Masuk ke folder proyek**

```bash
cd Sistem-Prediksi-Kelulusan
```

**3. Instal dependensi**

```bash
pip install -r requirements.txt
```

**4. Jalankan aplikasi**

```bash
python -m streamlit run app.py
```

## Database

Aplikasi menggunakan SQLite sebagai database dan SQLAlchemy untuk mengelola interaksi dengan database.
