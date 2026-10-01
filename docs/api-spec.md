# API Specification EVChargeHub

## 1. Tujuan

Dokumentasi ini digunakan untuk menjelaskan API yang digunakan
dalam aplikasi EVChargeHub. Dokumentasi ini membantu tim dalam
memahami fungsi dan penggunaan endpoint yang tersedia.

## 2. Modul

API pada aplikasi EVChargeHub dapat digunakan untuk mendukung
beberapa modul, seperti:

- Autentikasi pengguna
- Pengelolaan pengemudi
- Pengelolaan kendaraan
- Pengelolaan stasiun charging
- Konfigurasi sistem
- Pengelolaan data pengguna

## 3. Dokumentasi Endpoint

### 3.1 Autentikasi

| Method | Endpoint | Fungsi |
|---|---|---|
| POST | `/login` | Digunakan untuk proses login pengguna |
| POST | `/logout` | Digunakan untuk keluar dari sistem |

### 3.2 Pengemudi

| Method | Endpoint | Fungsi |
|---|---|---|
| GET | `/pengemudi` | Menampilkan data pengemudi |
| POST | `/pengemudi` | Menambahkan data pengemudi |
| PUT | `/pengemudi/{id}` | Mengubah data pengemudi |
| DELETE | `/pengemudi/{id}` | Menghapus data pengemudi |

### 3.3 Kendaraan

| Method | Endpoint | Fungsi |
|---|---|---|
| GET | `/kendaraan` | Menampilkan data kendaraan |
| POST | `/kendaraan` | Menambahkan data kendaraan |
| PUT | `/kendaraan/{id}` | Mengubah data kendaraan |
| DELETE | `/kendaraan/{id}` | Menghapus data kendaraan |

### 3.4 Konfigurasi Sistem

| Method | Endpoint | Fungsi |
|---|---|---|
| GET | `/konfigurasi` | Menampilkan konfigurasi sistem |
| PUT | `/konfigurasi/{id}` | Mengubah konfigurasi sistem |

## 4. Catatan

Endpoint pada dokumentasi ini merupakan rancangan dokumentasi
awal dan dapat disesuaikan kembali dengan implementasi aplikasi
EVChargeHub yang dikembangkan oleh tim.