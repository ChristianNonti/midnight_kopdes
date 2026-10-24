# 🌙 Midnight KOPDES — Story Edition

> *"Kalau ada warga datang malam-malam, kenali mereka baik-baik."*
> — pesan Pak RT Mardi

Game horor investigasi berbasis browser, bernuansa dusun Jawa. Kamu menjaga **minimarket KOPDES Mekar Jaya** di Dusun Karangwuni selama 5 malam, dari pukul **23.00 sampai 06.00**. Tugasmu: layani warga asli, usir makhluk yang menyamar. Salah memilih, dan nyawa atau nama baikmu yang jadi taruhannya.

🎮 **Main sekarang:** [midnight-kopdes.vercel.app](https://midnight-kopdes.vercel.app)

> Proyek ini dibuat sebagai **Tugas Project Desain Game**.

---

## ✨ Fitur

- **5 malam dengan cerita sendiri.** Tiap malam punya prolog, adegan jalan menuju toko, dan event khusus (Malam Tenang, Hujan Deras, Pemadaman Listrik, Bulan Purnama, Malam Jumat Kliwon).
- **45 warga dusun** dan **30 makhluk penyamar** (tuyul, kuntilanak, pocong, genderuwo, wewe gombel, sundel bolong, kuyang, lampor, ngepet, banaspati, blorong, dan lainnya).
- **Doppelganger (peniru).** Makhluk yang menyalin wajah, nama, bahkan kalimat warga asli. Kamu hanya bisa mengenalinya dengan membandingkan petunjuk dari warga aslinya yang datang lebih dulu.
- **Dialog bervariasi.** Tiap tokoh punya 4 kalimat pembuka yang dipilih acak, jadi tidak bisa dihafal satu-satu.
- **8 cara memeriksa pelanggan,** tiap cara punya biaya waktu dan kadang jatah terbatas.
- **Toko upgrade.** Kelebihan kas di atas setoran wajib bisa dibelikan baterai senter, garam, cermin, pulsa telepon, lampu, dan jimat pelindung.
- **3 tingkat kesulitan:** Easy, Normal, Hard.
- **Tamu langka (easter egg)** yang muncul acak.
- **Suasana audio dan visual:** jumpscare, suara yang dibuat lewat kode, adegan jalan beranimasi, dan latar dalam minimarket.
- **Banyak ending:** 2 happy ending dan 4 bad ending.

---

## 🕹️ Cara Bermain

1. Tiap pelanggan datang dengan nama, peran, dan kalimat pembukanya.
2. **Periksa** dia lewat beberapa cara. Setiap pemeriksaan memakan waktu dan menguras *kesabaran* pelanggan. Kalau habis, dia pergi sendiri.
3. Cocokkan hasilnya dengan petunjuk di **Buku Anggota**. Makhluk akan meninggalkan satu atau beberapa kejanggalan.
4. **Putuskan:** layani atau tolak.

| Keputusan | Hasil jika benar | Hasil jika salah |
|---|---|---|
| Layani warga asli | Dapat bayaran, plus bonus beruntun | — |
| Tolak makhluk | Aman | — |
| Layani makhluk | — | Kas berkurang, **nyawa** turun |
| Tolak warga asli | — | **Nama baik** turun |

### Cara memeriksa

| Tombol | Aksi | Catatan |
|:---:|---|---|
| `1` | Amati dari balik meja | Cepat dan tanpa batas |
| `2` | Minta KTP | Cocokkan nama, usia, RT |
| `3` | Periksa belanjaan | |
| `4` | Tanya soal dusun | |
| `5` | Sorot senter | Jatah terbatas, lihat bayangan |
| `6` | Tabur garam | Jatah terbatas |
| `7` | Lihat cermin rak | Jatah terbatas |
| `8` | Telepon pos ronda | Jatah terbatas, kadang ragu atau putus |

### Syarat menang dan kalah

Capai **target setoran kas** tiap malam sampai malam ke-5.

- ❌ **Nyawa habis:** *Terjebak Dalam Gelap*
- ❌ **Nama baik habis:** *Dibuang Warga Dusun*
- ❌ **Kas di bawah target:** *Koperasi Bangkrut & Teror*
- ❌ **3 Doppelganger lolos:** *Dusun Para Peniru*
- ✅ **Selesai malam 5:** *Fajar Karangwuni*, atau ending terbaik *Pahlawan Karangwuni* jika kamu teliti (nyawa dan nama baik minimal 2, dan minimal 8 keputusan benar)

---

## 🎚️ Tingkat Kesulitan

| | Easy | Normal | Hard |
|---|:---:|:---:|:---:|
| Kesabaran pelanggan | ×1,3 | ×1 | ×0,9 |
| Target setoran | 75% | 90% | 100% |
| Makhluk muncul | lebih jarang | standar | standar |
| Jatah alat | +1 | standar | standar |
| Kerugian saat makhluk lolos | ×0,5 | ×1 | ×1,25 |
| Pemulihan nyawa & nama baik | +2 / malam | +1 / malam | +1 / malam |
| Temuan janggal ditandai merah | ✅ | ✅ | ❌ (nilai sendiri) |

---

## 🛠️ Teknologi

Seluruh game ada di **satu file `index.html`**, tanpa framework, tanpa build, dan tanpa dependensi.

- HTML, CSS, dan JavaScript murni
- Grafis tokoh dan latar memakai **SVG** dan animasi **CSS**
- Audio dihasilkan dan disematkan langsung di dalam file
- Progres tersimpan di `localStorage` browser

## ▶️ Menjalankan Secara Lokal

```bash
git clone https://github.com/ChristianNonti/midnight_kopdes.git
cd midnight_kopdes
# buka index.html langsung di browser, atau jalankan server lokal:
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

Disarankan memakai browser modern (Chrome, Edge, Firefox, atau Safari). Pengaturan efek kejut, kecepatan teks, dan kualitas grafis ada di menu **Pengaturan** di dalam game.

---

## 📁 Struktur Repo

```
midnight_kopdes/
├── index.html   # seluruh game
├── README.md
└── LICENSE      # MIT
```

## 📜 Lisensi

Dirilis di bawah lisensi [MIT](LICENSE).

## 🙌 Kredit

Dibuat oleh **ChristianNonti** untuk Tugas Project Desain Game.
Cerita, nama tokoh, dan tempat dalam game adalah fiksi.
