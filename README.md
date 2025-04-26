
# 📋 Project Task Management System

## ✨ Deskripsi
Sistem ini dirancang untuk membantu admin dalam manajemen tugas dan karyawan dalam mengumpulkan tugas. Fitur mencakup autentikasi pengguna, pengelolaan tugas, pengumpulan tugas, hingga pembuatan laporan tugas dalam bentuk Excel dan PDF.

---

## 🚀 Fitur Utama

### 1. Autentikasi & Penggunaan
- **Registrasi & Login**
- **Verifikasi Email**
- **Verifikasi OTP**
- **Lupa Password**
- **Reset Password**

### 2. Manajemen Tugas (Admin)
- **Tambah Tugas**: Admin dapat membuat tugas baru.
- **Cari/Lihat Tugas**: Dilengkapi fitur **pagination**, **filter**, dan **sort**.
- **Edit Tugas**: Admin dapat mengubah **judul**, **deskripsi**, dan **deadline** dengan beberapa syarat validasi tertentu.
- **Hapus Tugas**: Admin dapat menghapus tugas.

### 3. Laporan Rekap Tugas
- **Export ke Excel**: Rekap tugas yang dapat diunduh dalam format Excel.
- **Export ke PDF**: Membuat laporan tugas dalam format PDF.

### 4. Pengumpulan Tugas (User/Karyawan)
- **Upload Tugas**: User/karyawan dapat mengunggah tugas dengan berbagai tipe file.
- **Ambil Tugas**: User dapat mengambil tugas yang sudah dikumpulkan sebelumnya.
- **Melihat Daftar Tugas**: User dapat melihat semua tugas yang dikaitkan dengan akun mereka.

---

## 🛠️ Teknologi yang Digunakan
- **Backend**: Spring Boot (Java)
- **Security**: Spring Security (JWT, OTP Verification, Email Verification)
- **Database**: MySQL / PostgreSQL
- **Export Laporan**: Apache POI (Excel), iText PDF (PDF)
- **Scheduler**: (Jika ada pengiriman otomatis reminder tugas)

---


