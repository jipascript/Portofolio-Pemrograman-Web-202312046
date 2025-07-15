# 🗃️ Portofolio Pemrograman Web – 202312046

[![GitHub Repo Size](https://img.shields.io/github/repo-size/jipascript/Portofolio-Pemrograman-Web-202312046?color=blue&label=Repo%20Size)](https://github.com/jipascript/Portofolio-Pemrograman-Web-202312046) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#-lisensi)

Repositori ini merupakan kumpulan hasil praktik mata kuliah **Pemrograman Web** semester 4 pada Program Studi **Teknik Informatika – STITEK Bontang**. Seluruh tugas dikembangkan secara terstruktur berdasarkan modul pembelajaran dan dikelola menggunakan sistem kontrol versi **Git** dan **GitHub**.

---

## 📌 Deskripsi

Tujuan dari repositori ini adalah:
- Mendokumentasikan proses belajar pengembangan web dari sisi frontend hingga backend
- Mengasah keterampilan penggunaan Git sebagai Version Control System
- Menerapkan alur kerja pengembangan proyek berbasis branch dan commit
- Membangun portofolio digital yang terstruktur, terbuka, dan mudah dipelajari

---

## 📂 Struktur Direktori

```
Portofolio-Pemrograman-Web-202312046/
├── Modul-1/
├── Modul-2/
├── Modul-3/
├── Modul-4/
├── Modul-5/
├── Modul-6/
└── README.md
```

---

## ⚙️ Prasyarat

Sebelum menjalankan atau memodifikasi proyek ini, pastikan telah menginstal dan menyiapkan:

| Teknologi | Keterangan |
|-----------|------------|
| **Git** | Version Control System |
| **GitHub** | Platform hosting repositori |
| **Visual Studio Code** | Editor teks dan terminal terintegrasi |
| **Laragon** | Web server lokal (Apache, MySQL, PHP) |
| **phpMyAdmin** | Manajemen database MySQL berbasis web |
| **HTML, CSS, JS** | Bahasa pemrograman frontend |
| **PHP** | Pemrosesan sisi server |
| **MySQL** | Sistem manajemen basis data relasional |

---

## ⚙️ Setup Proyek

### 1. Clone Repositori
```bash
git clone https://github.com/jipascript/Portofolio-Pemrograman-Web-202312046.git
cd Portofolio-Pemrograman-Web-202312046
```

### 2. Tambahkan Struktur Folder & Commit Awal
```bash
mkdir Modul-1 Modul-2 Modul-3
git checkout -b tugas/modul-1-3
git add .
git commit -m "Menambahkan tugas Modul 1 sampai 3"
git push -u origin tugas/modul-1-3
```

### 3. Lanjutkan Modul 4–6 dengan Branch Terpisah
```bash
git checkout main
git pull origin main
git checkout -b tugas/modul-4
mkdir Modul-4
# Tambahkan file tugas Modul 4
git add .
git commit -m "Menambahkan tugas Modul 4"
git push -u origin tugas/modul-4
```
_(Ulangi langkah serupa untuk Modul 5 dan 6.)_

---

## 🚀 Cara Menjalankan Proyek

### Untuk Modul 1–4 (Frontend)
- Cukup buka file `.html` langsung menggunakan browser
- Dapat juga menggunakan ekstensi **Live Server** di VS Code

### Untuk Modul 5–6 (Backend dengan PHP & MySQL)
1. **Pindahkan folder proyek** ke direktori `www` milik Laragon:
   ```
   C:\laragon\www\Portofolio-Pemrograman-Web-202312046
   ```
2. **Jalankan Laragon**, aktifkan Apache & MySQL.
3. **Akses di browser**:
   ```
   http://localhost/Portofolio-Pemrograman-Web-202312046/Modul-5/buku_tamu.php
   ```
4. **Buka phpMyAdmin**, buat database baru (misal: `praktikum_web`), lalu **import** file `Modul-6/database.sql`.

---

## 📬 Kontak

> **Nama** : Asma Nazhifah Lukman
> **NIM** : 202312046  
> **Program Studi** : Teknik Informatika  
> **GitHub** : [@jipascript](https://github.com/jipascript) 

---

## 🏁 Penutup

Repositori ini merupakan bagian dari hasil praktikum **Pemrograman Web**.  
Tidak hanya memuat kode sumber, tetapi juga menunjukkan alur kerja profesional seperti pemanfaatan **Git**, **branching**, dan dokumentasi proyek melalui **README** yang terstruktur.

Semoga dokumentasi ini bermanfaat dan dapat menjadi referensi pengembangan web secara sistematis. 🙌

---

## 📄 Lisensi

Repositori ini disusun sebagai bagian dari pemenuhan tugas akademik dalam mata kuliah Pemrograman Web di Sekolah Tinggi Teknologi Bontang (STITEK).
© 2025 Asma Nazhifah Lukman.  All rights reserved.
