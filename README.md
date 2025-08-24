# Portfolio Website — Beta

Portfolio Website — Beta adalah situs portofolio statis yang dibuat sebagai latihan saat mempelajari HTML dan CSS. Situs ini menampilkan hero (jumbotron) dengan teks animasi, bagian About, Projects (kartu proyek), dan Contact dengan form sederhana yang terhubung ke Google Apps Script. Cocok sebagai demo awal untuk menampilkan profil dan contoh kerja.

---

## Demo / Pratinjau
> File proyek ini bersifat statis. Untuk melihat hasilnya lokal, buka `index.html` di browser atau jalankan server lokal (instruksi di bawah).

---

## Fitur utama
- Desain responsif berbasis Bootstrap (navbar, grid, cards)
- Hero / jumbotron dengan efek teks animasi (GSAP TextPlugin)
- Bagian About, Projects, dan Contact yang terstruktur
- Animasi scroll / entrance (AOS)
- Form kontak sederhana dengan integrasi Google Apps Script (mengirim pesan via `fetch`)
- CSS ringkas dan mudah dimodifikasi — fokus pembelajaran HTML & CSS

---

## Teknologi
- HTML5
- CSS3 (file `style.css`)
- Bootstrap 5
- JavaScript (vanilla)
- AOS (Animate On Scroll)
- GSAP (TextPlugin)
- Integrasi optional: Google Apps Script (untuk endpoint form)

---

## Cara menjalankan (lokal)
**Opsi 1 — Buka langsung**
1. Klik dua kali `index.html` atau buka file melalui browser (`File -> Open File`).

**Opsi 2 — Jalankan server HTTP sederhana (direkomendasikan untuk fetch/endpoint)** 
- Menggunakan Python 3:
``bash
`di folder proyek
python -m http.server 8000
`buka http://localhost:8000

**Opsi 3 — Menggunakan Node (serve)**  
npm install -g serve
serve .
`lalu buka URL yang ditampilkan

