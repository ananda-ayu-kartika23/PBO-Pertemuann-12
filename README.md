# 🧩 Tugas Pertemuan 13 – Aplikasi GUI Transaksi dengan Relasi Database

## 📘 Deskripsi Proyek
Repository ini berisi aplikasi GUI berbasis **Java** yang terhubung dengan **database relasional** menggunakan **Java Persistence API (JPA)**.  
Aplikasi ini menampilkan dan mengelola data dari beberapa tabel yang saling berelasi.  
Antarmuka dibuat menggunakan **Java Swing**, dengan pendekatan **tabbed panel** untuk memisahkan setiap modul CRUD.

---

## 🏗️ Fitur Utama
- **Relasi antar tabel:**  
  
- **GUI dengan Tabbed Interface:**  
  Menggunakan `JTabbedPane` untuk memisahkan fitur 

- **Operasi CRUD Lengkap:**  
  - Tambah, ubah, hapus, dan tampilkan data  
  - Sistem melakukan validasi sebelum menghapus data yang masih memiliki relasi

- **Validasi Relasi dan Integritas Data:**  
  - Menghindari *foreign key constraint error* dan menjaga konsistensi database
