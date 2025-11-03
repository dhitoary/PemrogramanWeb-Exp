# Dhito Aryo Trengginas — Portofolio Praktikum Pemrograman Web

[![HTML](https://img.shields.io/badge/HTML-%3E%3D5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS](https://img.shields.io/badge/CSS-%3E%3D3.0-green.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![Live Demo](https://img.shields.io/badge/Live%20Demo-Open-green.svg)](https://raw.githack.com/dhitoary/PortofolioDhito_Prak.PW/main/DhitoAryoT_Portofolio.html)

Selamat datang! Ini adalah portofolio Pemrograman Web saya — dibuat hanya dengan HTML dan CSS.

---

## Tentang singkat
Saya Dhito Aryo Trengginas — Mahasiswa Teknik Informatika (NPM 2315061015). Tugas praktikum ini menuntut pembuatan portofolio statis menggunakan HTML & CSS. Fokus: desain yang aesthetic, responsif, dan mudah dikustomisasi.

- Bahasa: HTML & CSS (tanpa JavaScript)
- Fitur utama: About, Experience (timeline), Education, Skills, Contact
- Tema: Collage hijau (army/olive) 

---
## Instalasi dan Penggunaan

Karena ini adalah website statis, tidak diperlukan proses instalasi yang kompleks.

1.  *Clone repository ini:*
    bash
    git clone https://github.com/dhitoary/PemrogramanWeb-Exp.git
    
2.  *Masuk ke direktori proyek:*
    bash
    cd PemrogramanWeb-Exp
    
3.  **Buka file DhitoAryoT_Portofolio.html:**
    Buka file DhitoAryoT_Portofolio.html di browser pilihan kamu (misalnya Google Chrome, Firefox, atau Edge) untuk melihat website secara lokal.

---

## Workflow Git yang Diterapkan

Proyek ini dikerjakan dengan mengikuti alur kerja (workflow) Git yang terstruktur untuk mengelola riwayat perubahan secara efektif:

1.  *Inisialisasi Git:*
    * Proyek diinisialisasi sebagai repositori Git baru di direktori lokal menggunakan perintah git init.

2.  *Commit Bertahap (Atomic Commits):*
    * Setiap section utama dari website (seperti Home, About, Education, Skill, Portfolio, Contact) dibuat dan di-commit secara terpisah.
    * Tujuannya adalah agar setiap commit fokus pada satu penambahan fitur spesifik, sehingga riwayatnya mudah dilacak (contoh: git commit -m "add: create experience of porto", git commit -m "add: create eduskil").

3.  *Penggunaan Branch (Branching):*
    * Sebuah branch baru bernama exp dan eduskil dibuat untuk melakukan tampilan isi dari experience lalu education, dan skill untuk portofolio saya.
    * Perintah yang digunakan:
        bash
        git branch exp
        git branch eduskil
        git checkout exp
        git checkout eduskil
        
    * Pekerjaan styling baru dilakukan di dalam branch ini agar tidak mengganggu kode utama yang stabil di branch main.

4.  *Merge Branch:*
    * Setelah proses styling di branch exp dan eduskil selesai dan dipastikan berfungsi dengan baik, perubahan tersebut digabungkan kembali ke branch main.
    * Perintah yang digunakan:
        bash
        git checkout main
        git merge exp
        git merge eduskil
        

5.  *Push ke GitHub:*
    * Setelah semua fitur dan styling dianggap stabil di branch main, keseluruhan proyek di-push ke repositori remote di GitHub untuk disimpan dan dibagikan.
    * Perintah yang digunakan: git push origin main.

6.  *Pembuatan README.md:*
    * File README.md ini (yang sedang kamu baca) dibuat untuk memberikan dokumentasi informatif mengenai deskripsi proyek, teknologi, langkah penggunaan, dan alur kerja Git yang diterapkan.

---

## Riwayat Git Log

Berikut adalah screenshot dari perintah git log --graph --oneline yang menunjukkan riwayat commit serta alur kerja branching dan merge yang telah dilakukan:
![Git Log Graph](Screenshot/Screenshot 2025-11-03 180510.png")

---

## Kontak
- Email: aryodhito20@gmail.com  
- GitHub: https://github.com/dhitoary  
- LinkedIn: https://www.linkedin.com/in/dhito-aryo-trengginas-1b886629

---

Terima kasih sudah melihat Portofolio saya..
