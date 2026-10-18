# SELAYAR BISA — Portal Inovasi BPS Kepulauan Selayar

Website katalog ringkas, modern, minimalis, dan responsif yang menghimpun seluruh inovasi digital serta tautan panduan operasional di lingkungan **Badan Pusat Statistik (BPS) Kabupaten Kepulauan Selayar (Satker 7301)**.

Dikelola oleh **[@stat-selayar](https://github.com/stat-selayar)**.

---

## 🌟 Daftar Inovasi

| Inovasi | Kategori | Akses Langsung | Panduan & Repository |
| :--- | :--- | :--- | :--- |
| **PUSAT 7301** | Tata Naskah & Administrasi | [s.bps.go.id/pusat7301](https://s.bps.go.id/pusat7301) | [GitHub @stat-selayar/pusat7301](https://github.com/stat-selayar/pusat7301) |
| **SLS Finder Selayar** | WebGIS & Geospasial | [Buka SLS](https://stat-selayar.github.io/sls/) | [GitHub @stat-selayar/sls](https://github.com/stat-selayar/sls) |
| **BUMAKO** | Master Komoditas SPDT NTP 2026 | [Buka BUMAKO](https://stat-selayar.github.io/bumako/) | [GitHub @stat-selayar/bumako](https://github.com/stat-selayar/bumako) |
| **SIPH Sulsel** | Analisis Inflasi & Harga Pangan | [Buka SIPH](https://stat-selayar.github.io/siph/) | [GitHub @stat-selayar/siph](https://github.com/stat-selayar/siph) |
| **Sampel SPDT** | Pergantian Sampel DSRT 7301 | [sampel-spdt.vercel.app](https://sampel-spdt.vercel.app) | [GitHub @stat-selayar/sampel-spdt](https://github.com/stat-selayar/sampel-spdt) |
| **Gemerlap** | Monitoring Tanaman & Lahan | [Buka Gemerlap](https://stat-selayar.github.io/gemerlap/) | [GitHub @stat-selayar/gemerlap](https://github.com/stat-selayar/gemerlap) |

---

## 🚀 Fitur Utama

- **Minimalist & Zero Dependency:** Murni Static HTML5, modern CSS3, dan Vanilla JavaScript tanpa framework berat.
- **Fast Instant Search:** Pencarian instan kata kunci inovasi, nama subsektor, atau kegunaan.
- **Category Filter Pills:** Filter cepat berdasarkan kategori teknis (Administrasi, Geospasial, Survei Pertanian, Analisis Harga).
- **Dark & Light Mode:** Mendukung switch tema gelap/terang otomatis mengikuti preferensi OS atau manual via toggle.
- **Copy Link Action:** Tombol cepat salin tautan langsung ke clipboard beserta toast konfirmasi.
- **Fully Responsive:** Tampilan rapi dan nyaman diakses lewat smartphone, tablet, maupun layar desktop.

---

## 📂 Struktur Berkas

```text
selayarbisa/
├── index.html       # Antarmuka web utama
├── style.css        # Tata letak, tokens desain, dark/light theme & responsivitas
├── app.js           # Logika interaktif pencarian, filter, tema, dan salin tautan
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
   cd /mnt/data/Project/stat-selayar.github.io
   git add .
   git commit -m "feat: perbarui tautan inovasi ke stat-selayar"
   git push origin main
   ```
3. Buka **Settings > Pages** pada repository GitHub, pilih branch `main` folder `/(root)`.
4. Website akan langsung aktif di `https://stat-selayar.github.io/`.
