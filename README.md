# Portfolio

---

```markdown
# Portfolio Website - SR Pakpahan, SST

![Status Proyek](https://img.shields.io/badge/Status-Aktif-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat&logo=javascript&logoColor=white)

> **Tagline:** *"Dengan Teknologi PMD (Pedang Mata Dua), Membangun UI/UX web/desktop yang cepat, responsif, dan ramah pengguna."*

---
URL Link Aplikasi:
is live at:
https://srpakpahansst.github.io/Portfolio/
---

## 📖 Deskripsi Proyek

Ini adalah situs web portfolio pribadi statis yang dirancang untuk menampilkan profil profesional, riwayat pendidikan, keahlian teknis, sertifikasi, proyek unggulan, dan testimoni dari **SR Pakpahan, SST**. 

Situs ini dibangun dengan fokus pada **performasi tinggi**, **aksesibilitas**, dan **pengalaman pengguna (UX)**. Desainnya menggunakan pendekatan *mobile-first* dan mendukung mode terang/gelap (Light/Dark Mode) untuk kenyamanan pengguna.

---

## ✨ Fitur Utama

- **Responsif Penuh:** Tampilan optimal di perangkat desktop, tablet, dan ponsel (menggunakan CSS Grid & Flexbox).
- **Dark Mode Interaktif:** Fitur toggle tema dengan penyimpanan preferensi pengguna di `localStorage`.
- **Navigasi Halus:** Implementasi *smooth scrolling* dan menu hamburger yang responsif untuk pengguna seluler.
- **Animasi On-Scroll:** Elemen muncul dengan animasi halus saat pengguna menggulir halaman menggunakan *Intersection Observer API*.
- **Formulir Kontak:** Halaman formulir yang dilengkapi validasi input dan simulasi pengiriman pesan.
- **Grid Sertifikat Dinamis:** Bagian sertifikat menggunakan CSS Grid 3 kolom yang otomatis memanjang ke bawah saat dokumen baru ditambahkan.
- **Aksesibilitas:** Struktur HTML semantik dan label ARIA untuk mendukung pembaca layar.

---

## 🛠️ Teknologi & Tools

Proyek ini dibangun menggunakan teknologi web standar tanpa ketergantungan pada framework eksternal (Vanilla Stack):

- **HTML5:** Struktur semantik dan aksesibel.
- **CSS3:** Styling modern menggunakan *CSS Custom Properties* (Variables) untuk manajemen tema, Flexbox, dan Grid Layout.
- **JavaScript (ES6+):** Interaktivitas halaman, pengelolaan tema, dan animasi.
- **Font Awesome 6:** Ikon grafis profesional dan responsif.
- **Google Fonts (Inter):** Tipografi modern yang bersih dan mudah dibaca.

---

## 📂 Struktur Direktori

```plaintext
portfolio-sr-pakpahan/
├── index.html          # Berkas utama halaman portfolio (berisi HTML, CSS, dan JS)
├── assets/             # (Opsional) Folder untuk file statis seperti gambar
│   ├── images/
│   │   ├── profile.jpg # Foto profil utama
│   │   └── certificates/
│   │       ├── certificate-1.jpg
│   │       └── certificate-2.jpg
└── README.md           # Dokumentasi proyek (file ini)
```

---

🚀 Cara Menjalankan Proyek

Karena proyek ini hanya terdiri dari satu file index.html yang mandiri (Self-contained), Anda dapat menjalankannya dengan mudah tanpa proses build atau instalasi dependensi.

Opsi 1: Buka Langsung di Browser

Unduh atau salin kode index.html ke komputer Anda, lalu klik dua kali file tersebut untuk membukanya di browser web (Chrome, Firefox, Edge, Safari).

Opsi 2: Menggunakan Local Server (Direkomendasikan)

Untuk hasil pengembangan terbaik dan menghindari masalah CORS (jika ada), gunakan server lokal:

1. Python 3:
   ```bash
   cd portfolio-sr-pakpahan/
   python -m http.server 8000
   ```
   Buka http://localhost:8000 di browser.
2. VS Code Live Server:
   · Install ekstensi Live Server.
   · Klik kanan pada index.html.
   · Pilih "Open with Live Server".

---

🧩 Kustomisasi

1. Mengganti Foto Profil

Cari tag <img> di dalam bagian hero-image dan about-image pada index.html, lalu ganti nilai atribut src dengan direct link atau path lokal foto Anda:

```html
<img class="avatar" src="assets/images/profile.jpg" alt="Foto SR Pakpahan">
```

2. Menambahkan Sertifikat Baru

Untuk menambahkan sertifikat, salin blok .certificate-item di dalam <section id="certificates"> dan tempel di bawahnya:

```html
<div class="certificate-item reveal">
    <img src="assets/images/certificates/new-certificate.jpg" alt="Nama Sertifikat">
</div>
```

Catatan: Grid akan otomatis menyesuaikan dan memanjang ke bawah karena menggunakan CSS Grid repeat(3, 1fr).

3. Mengubah Warna Tema

Seluruh skema warna dikelola di dalam CSS Custom Properties pada bagian :root. Anda dapat mengubah nilai warna utama untuk menyesuaikan branding:

```css
:root {
    --color-primary: #6366f1;  /* Ganti dengan warna branding Anda */
    --color-secondary: #8b5cf6;
    --color-accent: #f59e0b;
}
```

---

📌 Bagian Utama Halaman

1. Hero: Pengenalan singkat, tagline, dan tautan media sosial.
2. Tentang Saya: Latar belakang profesional dan statistik pengalaman.
3. Keahlian: Rincian Hard Skills, Soft Skills, dan Tools.
4. Sertifikat: Galeri dokumentasi sertifikasi resmi dalam format grid.
5. Karya Pilihan: Studi kasus proyek dengan pendekatan STAR (Situation, Task, Action, Result).
6. Testimoni: Ulasan dari kolega dan rekan tim.
7. Kontak: Formulir pesan dan informasi kontak langsung.

---

📄 Lisensi

© 2026 SR Pakpahan, SST. Hak cipta dilindungi undang-undang. Kode ini dibuat untuk keperluan portofolio pribadi dan tidak untuk didistribusikan ulang secara komersial tanpa izin tertulis dari penulis.

---

📬 Kontak

· Email: pakpahan.ministry@gmail.com
· Telepon/WA: +62 821 7081 4310
· GitHub: github.com/SRPakpahanSST
· LinkedIn: linkedin.com/in/srpakpahansst
· YouTube: youtube.com/@mmag_recipes
· Instagram: instagram.com/srpakpahansst

```

---