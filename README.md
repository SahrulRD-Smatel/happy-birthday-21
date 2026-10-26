# 🎀 Happy Birthday 21 - Ruru Nicole Putri 🎀

Website ulang tahun 3D romantis bertema coquette pink — dibuat untuk merayakan ulang tahun ke-21 pada **26 October 2026**.

- `index.html` — website 3D interaktif (Three.js: hati melayang, tabur hati saat diklik, galeri foto, 21 alasan, dan foto bonus spesial)
- `assets/` — foto-foto (5 foto utama + 1 foto bonus)
- `happy-birthday-21.pdf` — kartu ucapan PDF romantis, siap dikirim lewat email

Buka `index.html` langsung, atau aktifkan GitHub Pages dari branch `main` untuk link publik.

## Tiga pengalaman yang saling terhubung

- `index.html` adalah halaman utama dan pintu masuk.
- `game.html` adalah **Game 1 — Quest HTML** yang sudah ada.
- `manus/index.html` adalah **Game 2 — Secret Quest Manus**, hasil build terbaru dari proyek Manus.

Dari halaman utama, Game 2 sengaja dikunci dengan mini-gate. Masukkan nama kode `Dhani` untuk membuka `manus/index.html`. Build Manus memakai path relatif sehingga tetap bekerja di GitHub Pages pada subfolder `/manus/`.
Folder `manus/photos/` memakai foto dari folder `assets/` repository, dan `manus/happy-birthday-21.pdf` adalah PDF resmi yang diunduh oleh tombol Surat Rahasia. Penutup love note tetap `xoxo, Dhani`.

## Deploy GitHub Pages

Aktifkan **Settings → Pages → Source: Deploy from a branch**, pilih branch `main` dan folder `/ (root)`. Setelah push ke `main`, buka `https://sahrulrd-smatel.github.io/happy-birthday-21/`.
