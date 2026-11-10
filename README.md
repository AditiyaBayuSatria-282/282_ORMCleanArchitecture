# Praktikum 6 - ORM Clean Architecture

CRUD API Komik menggunakan Express.js, Sequelize, dan PostgreSQL.

## Cara Menjalankan
1. `npm install`
2. Salin `.env.example` jadi `.env`, lalu isi konfigurasi database
3. `npm start`

## Endpoint
| Method | URL | Keterangan |
|--------|-----|------------|
| GET | /api/Komik | Ambil semua komik |
| POST | /api/Komik | Tambah komik |
| PUT | /api/Komik/:id | Ubah komik |
| DELETE | /api/Komik/:id | Hapus komik |