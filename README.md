# 🏪 Midnight KOPDES — Story Edition

> **"Siapa yang sedang berdiri di balik pintu toko jam 3 pagi? Warga Karangwuni asli... atau Peniru?"**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blue?style=for-the-badge)

**Midnight KOPDES — Story Edition** adalah *indie horror-simulation web game* berbasis teks & visual bergaya retro-arcade. Pemain bertugas sebagai penjaga shift malam (21.00 – 03.00) di minimarket **KOPDES Mekar Jaya**, Dusun Karangwuni. Tugas utamanya adalah memverifikasi identitas pelanggan, mengumpulkan setoran kas harian, dan mencegah makhluk halus (*Doppelganger*, Tuyul, Kuntilanak, Pocong, Kuyang, dll.) masuk ke dalam toko.

---

## 📖 Latar Belakang Cerita

Tiga hari lalu, pohon asam tua di pertigaan Dusun Karangwuni ditebang. Sejak malam itu, gerbang menuju kebun bambu kuno terbuka. Sesepuh desa dan para peniru dari alam lain berkeliaran menyamar sebagai warga asli. Pak RT Mardi memberimu kunci minimarket dan **Buku Anggota Desa**. Tugasmu sederhan: **layani warga asli, usir para peniru.**

---

## 🎮 Fitur Utama

- **8 Saluran Pemeriksaan Kritis:**
  - 👁️ **Amati:** Cek detail fisik, kancing, tato, atau kejanggalan baju.
  - 🪪 **Cek KTP:** Cocokkan nama, RT, dan tanda tangan dengan Buku Anggota.
  - 🛍️ **Cek Belanjaan:** Analisis barang bawaan dan keanehan mata uang/uang basah.
  - 🗣️ **Tanya Dusun:** Uji pengetahuan pelanggan tentang batas RT Karangwuni.
  - 🔦 **Sorot Senter:** Cek apakah ada bayangan atau ciri fisik yang melayang.
  - 🧂 **Tabur Garam:** Reaksi fisik terhadap zat penolak makhluk halus.
  - 🪞 **Cermin Rak:** Cek pantulan asli pelanggan di cermin.
  - 📞 **Telepon Pos Ronda:** Konfirmasi keberadaan warga asli secara langsung ke Pak RT.
- **Dynamic Procedural Audio Engine:** Efek suara dan *ambient drone* dibuat secara lansung melalui Web Audio API tanpa *asset* eksternal.
- **Multiple Endings:**
  - 🏆 **Happy End (True / Normal):** Pahlawan Karangwuni & Bertahan 5 Malam.
  - 💀 **Bad End (Teror Hantu):** 3x mengizinkan entitas jahat masuk.
  - 🚪 **Bad End (Dipecat):** 3x salah menolak warga asli.
  - 💸 **Bad End (Bangkrut):** Gagal memenuhi target kas wajib harian.
  - 👥 **Bad End (Doppelganger):** Terlalu banyak peniru yang meloloskan diri ke desa.
- **Responsive & Mobile-Optimized:** Tampilan retro CRT dengan dukungan khusus mode *portrait* pada smartphone.

---

## 🕹️ Cara Bermain & Tombol Kontrol

1. **Periksa Pelanggan:** Setiap analisis membutuhkan waktu beberapa menit. Perhatikan sisa kesabaran pelanggan.
2. **Bandingkan Data:** Buka **Buku Anggota** untuk mencocokkan identitas resmi.
3. **Ambil Keputusan:**
   - **Layani (`L`):** Terima uang belanjaan jika pelanggan adalah warga asli.
   - **Tolak (`T`):** Usir jika ditemukan indikasi peniru / entitas jahat.

| Tombol Keyboard | Aksi |
| :---: | :--- |
| `1` – `7` | Melakukan analisis/pemeriksaan fisik & dokumen |
| `8` | Telepon Pos Ronda (Konfirmasi Pak RT) |
| `L` | Layani pelanggan & terima uang |
| `T` | Tolak pelanggan & usir keluar |
| `Enter` | Melanjutkan ke pelanggan berikutnya / Tutup Toko |

---

## 🛠️ Teknologi yang Digunakan

- **HTML5:** Struktur dokumen tunggal tanpa dependensi eksternal.
- **CSS3:** Retro CRT Scanlines, Responsive Grid, Flexbox, Custom Variables, dan CSS Keyframe Animations.
- **Vanilla JavaScript (ES6+):** Game loop, pembuat antrean prosedural, state management, dan evaluasi narasi.
- **Web Audio API:** Synthesizer suara (BiquadFilter, OscillatorNode) untuk *ambience* dan *sound effects*.

---
