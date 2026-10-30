# SELAYAR BISA — Berbagi Inovasi Statistik Antarpegawai

**BISA** = **B**erbagi **I**novasi **S**tatistik **A**ntarpegawai.

Website katalog ringkas, modern, minimalis, dan responsif yang menghimpun seluruh inovasi digital serta tautan panduan operasional di lingkungan **Badan Pusat Statistik (BPS) Kabupaten Kepulauan Selayar (Satker 7301)**.

Dikelola oleh **[@stat-selayar](https://github.com/stat-selayar)**.

---

## 🌟 Daftar Inovasi

| Inovasi | Kategori | Akses Langsung | Panduan & Repository |
| :--- | :--- | :--- | :--- |
| **PUSAT 7301** | Tata Naskah & Administrasi | [s.bps.go.id/pusat7301](https://s.bps.go.id/pusat7301) | [GitHub @ridsonap/pusat7301](https://github.com/ridsonap/pusat7301) |
| **SLS Finder Selayar** | WebGIS & Geospasial | [Buka SLS](https://stat-selayar.github.io/sls/) | [GitHub @stat-selayar/sls](https://github.com/stat-selayar/sls) |
| **BUMAKO** | Master Komoditas SPDT NTP 2026 | [Buka BUMAKO](https://stat-selayar.github.io/bumako/) | [GitHub @stat-selayar/bumako](https://github.com/stat-selayar/bumako) |
| **SIPH Sulsel** | Analisis Inflasi & Harga Pangan | [Buka SIPH](https://stat-selayar.github.io/siph/) | [GitHub @stat-selayar/siph](https://github.com/stat-selayar/siph) |
| **Sampel SPDT** | Pergantian Sampel DSRT 7301 | [sampel-spdt.vercel.app](https://sampel-spdt.vercel.app) | [GitHub @ridsonap/sampel-spdt](https://github.com/ridsonap/sampel-spdt) |
| **Gemerlap** | Monitoring Tanaman & Lahan | [Buka Gemerlap](https://stat-selayar.github.io/gemerlap/) | [GitHub @stat-selayar/gemerlap](https://github.com/stat-selayar/gemerlap) |
| **Generator SPD** | Perjalanan Dinas & Administrasi | [Buka SPD](https://stat-selayar.github.io/spd/) | [GitHub @stat-selayar/spd](https://github.com/stat-selayar/spd) |

---

## 🚀 Fitur Utama

- **Minimalist & Zero Dependency:** Murni Static HTML5, modern CSS3, dan Vanilla JavaScript tanpa framework berat.
- **Fast Instant Search:** Pencarian instan kata kunci inovasi, nama subsektor, atau kegunaan.
- **Category Filter Pills:** Filter cepat berdasarkan kategori teknis (Administrasi, Geospasial, Survei, Analisis Harga).
- **Dark & Light Mode:** Tema terang secara default, bisa diganti ke gelap lewat tombol; pilihan disimpan di peramban.
- **Copy Link Action:** Tombol cepat salin tautan langsung ke clipboard beserta toast konfirmasi.
- **Fully Responsive:** Tampilan rapi dan nyaman diakses lewat smartphone, tablet, maupun layar desktop.

---

## 📂 Struktur Berkas

```text
stat-selayar.github.io/
├── index.html       # Antarmuka web utama
├── style.css        # Tata letak, tokens desain, dark/light theme & responsivitas
├── app.js           # Logika interaktif pencarian, filter, tema, dan salin tautan
├── favicon.svg      # Ikon tab peramban
└── README.md        # Dokumentasi proyek
```

---

## 🌐 Cara Menjalankan & Deploy

### 1. Jalankan Lokal
Cukup buka file `index.html` langsung di browser, atau jalankan static server lokal:
```bash
# Menggunakan Python
python3 -m http.server 8080
```
Buka `http://localhost:8080` di browser.

### 2. Deploy ke GitHub Pages (100% Gratis)
1. Repository GitHub: `stat-selayar.github.io`.
2. Push direktori ini ke branch `main`:
   ```bash
   git add .
   git commit -m "feat: tambahkan inovasi baru"
   git push origin main
   ```
3. Pages sudah aktif dari branch `main` folder `/ (root)`; setiap push ke `main` langsung terbit.
4. Website akan langsung aktif di `https://stat-selayar.github.io/`.
