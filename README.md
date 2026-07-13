# 🌸 DIY by Liyaaa — Website E-Commerce Fashion Handmade

> *"Setiap produk bukan sekadar pakaian — ia adalah pelukan hangat yang kami jahit untukmu."*

Website e-commerce single-file untuk brand fashion handmade **DIY by Liyaaa**. Semua gambar produk, logo, dan QRIS tertanam langsung di dalam file HTML sebagai base64 — tidak memerlukan server, database, atau file eksternal apapun.

---

## 📋 Daftar Isi

- [Fitur Utama](#-fitur-utama)
- [Katalog Produk](#-katalog-produk)
- [Cara Penggunaan](#-cara-penggunaan)
- [Cara Deploy](#-cara-deploy)
- [Alur Pembelian](#-alur-pembelian)
- [Metode Pembayaran](#-metode-pembayaran)
- [Pilihan Ongkos Kirim](#-pilihan-ongkos-kirim)
- [Teknologi](#-teknologi)
- [Desain & Tema](#-desain--tema)
- [Kontak & Informasi Brand](#-kontak--informasi-brand)

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|---|---|
| 🎉 Welcome Screen | Layar sambutan animasi saat pertama membuka website |
| 🎠 Hero Carousel | Slider produk unggulan otomatis dengan tombol navigasi |
| 🗂️ Filter Kategori | Sidebar filter produk berdasarkan kategori |
| 🔍 Pencarian | Cari produk berdasarkan nama atau deskripsi cerita |
| 📖 Story Modal | Setiap produk punya cerita, pilihan warna, ukuran, dan jumlah |
| 🛍️ Keranjang Belanja | Drawer slide-in dengan daftar item, update qty, dan hapus item |
| 📋 Form Checkout | Isi nama, nomor HP, dan alamat lengkap di dalam keranjang |
| 🚚 Pilih Kurir | 4 pilihan kurir dengan estimasi dan harga ongkir |
| 💳 Metode Pembayaran | Transfer Bank (QRIS + Mandiri) atau COD |
| ⏳ Status Pembayaran | Layar pending countdown → konfirmasi admin → sukses + konfeti |
| 💬 WhatsApp Otomatis | Pesan WA otomatis terisi detail pesanan |
| 🎊 Konfeti | Animasi konfeti saat pesanan berhasil |
| 📱 Fully Responsive | Tampilan optimal di HP, tablet, iPad, dan laptop |
| 🔗 Floating Contact | Tombol WhatsApp, Instagram, dan Email yang selalu terlihat |

---

## 🛒 Katalog Produk

| No | Nama Produk | Harga | Kategori | Badge |
|---|---|---|---|---|
| 1 | Baju Krunek Manik | Rp 120.000 | Baju | Handmade |
| 2 | Tank Top Raisa Marie | Rp 100.000 | Atasan | Bestseller |
| 3 | Sandal Pantai | Rp 270.000 | Sandal | Limited |
| 4 | Belt Aksesoris | Rp 130.000 | Aksesoris | — |
| 5 | Tas Slingbag Selempang | Rp 300.000 | Tas | Handwoven |
| 6 | Rok Prisket | Rp 220.000 | Bawahan | — |
| 7 | Kain Pantai Bali | Rp 99.000 | Kain | Bali Vibes |
| 8 | Bandana | Rp 60.000 | Aksesoris | — |
| 9 | Jepit Rambut | Rp 26.000 | Aksesoris | — |
| 10 | Dompet | Rp 35.000 | Aksesoris | — |
| 11 | Bando Manik | Rp 20.000 | Aksesoris | — |
| 12 | Kardigan Manik | Rp 180.000 | Baju | New |

### Kategori yang Tersedia
`Semua` · `Baju` · `Atasan` · `Bawahan` · `Rok` · `Sandal` · `Aksesoris` · `Tas` · `Kain`

---

## 🚀 Cara Penggunaan

### Membuka Website
Cukup buka file `index.html` di browser manapun — tidak perlu koneksi internet khusus (font Google Fonts memerlukan internet).

```
Klik dua kali → index.html → otomatis terbuka di browser
```

### Struktur File
```
index.html          ← Satu file ini sudah cukup untuk menjalankan website
README.md           ← Dokumentasi ini
```

> Semua gambar produk, logo brand, dan QRIS pembayaran sudah **tertanam di dalam** `index.html` sebagai data base64. Tidak perlu folder `images/` terpisah.

---

## 🌐 Cara Deploy

Website ini bisa langsung di-deploy ke hosting statis manapun:

### GitHub Pages (Gratis)
```bash
# 1. Buat repository baru di GitHub
# 2. Upload file index.html
# 3. Buka Settings → Pages → pilih branch main
# 4. Website aktif di: https://username.github.io/nama-repo
```

### Netlify (Gratis, Drag & Drop)
```
1. Buka netlify.com → Log in
2. Drag & drop file index.html ke area deploy
3. Website langsung aktif dengan URL otomatis
```

### Hosting Lain
Upload `index.html` ke folder `public_html` atau `www` di cPanel / FTP hosting manapun.

---

## 🛍️ Alur Pembelian

```
1. Buka website
        ↓
2. Lihat produk → klik "Lihat Cerita" atau "+ Keranjang"
        ↓
3. Pilih warna, ukuran, dan jumlah di Story Modal
        ↓
4. Klik "Tambah ke Keranjang"
        ↓
5. Buka keranjang (ikon tas di kanan atas)
        ↓
6. Isi Nama, Nomor HP, dan Alamat Lengkap
        ↓
7. Pilih Kurir Pengiriman
        ↓
8. Pilih Metode Pembayaran (Transfer / COD)
        ↓
9. Klik "Lanjut Pembayaran"
        ↓
   [Transfer Bank]              [COD]
        ↓                         ↓
10. Scan QRIS /           Langsung ke layar
    Transfer Mandiri       pesanan berhasil 🎉
        ↓
11. Klik "Saya Sudah Transfer"
        ↓
12. Tunggu countdown 60 detik
        ↓
13. Konfirmasi via WhatsApp Admin
        ↓
14. Pesanan Berhasil 🎉 + Konfeti
```

---

## 💳 Metode Pembayaran

### Transfer Bank
| Info | Detail |
|---|---|
| Bank | Bank Mandiri |
| Nomor Rekening | 1320030631197 |
| Atas Nama | SHANDA AMELIA NUR VADILAH |

### QRIS
Scan QR Code yang tampil di layar pembayaran (NMID: ID1026518484906 — DIY by Liyaaa)

### COD (Bayar di Tempat)
Tersedia untuk area yang dilayani GoSend / Grab Same Day

---

## 🚚 Pilihan Ongkos Kirim

| Kurir | Estimasi | Ongkir |
|---|---|---|
| JNE REG | 2–4 hari | Rp 18.000 |
| J&T Express | 2–4 hari | Rp 16.000 |
| SiCepat REG | 1–3 hari | Rp 15.000 |
| GoSend / Grab | Same day | Rp 12.000 |

---

## 🛠️ Teknologi

Website ini dibangun dengan **HTML, CSS, dan JavaScript murni** — tanpa framework, tanpa library eksternal, tanpa backend.

| Komponen | Detail |
|---|---|
| Struktur | HTML5 Semantik |
| Styling | CSS3 (Custom Properties, Flexbox, Grid, Animasi) |
| Logika | Vanilla JavaScript (ES5 kompatibel) |
| Font | Google Fonts — Playfair Display, Quicksand, Caveat |
| Gambar | Embedded Base64 (tidak perlu file eksternal) |
| Hosting | Static file — kompatibel dengan semua hosting |

### Kompatibilitas Browser
- ✅ Google Chrome
- ✅ Mozilla Firefox
- ✅ Safari (iOS & macOS)
- ✅ Microsoft Edge
- ✅ Browser HP Android & iPhone

---

## 🎨 Desain & Tema

### Palet Warna
| Nama | Kode Hex | Penggunaan |
|---|---|---|
| Navy | `#2C3E66` | Warna utama, teks judul, tombol |
| Navy Soft | `#41557F` | Hover state |
| Pink | `#F4A7BB` | Aksen, highlight |
| Pink Deep | `#E78AA3` | Tombol utama, harga |
| Pink Pale | `#FBE2E9` | Background elemen sekunder |
| Cream | `#FBF3E7` | Background halaman |
| White | `#FFFFFF` | Card, modal |
| Ink | `#3A2E35` | Teks body |

### Tipografi
| Font | Kegunaan |
|---|---|
| Playfair Display | Judul, nama brand, heading |
| Quicksand | Body teks, tombol, label |
| Caveat | Aksen script, cerita produk |

### Responsif
| Layar | Tampilan |
|---|---|
| Desktop (>900px) | Sidebar kategori + grid produk |
| Tablet iPad (~820px) | Sidebar tersembunyi, hero menyesuaikan |
| HP Portrait (≤520px) | Hero vertikal (foto atas, teks bawah) |
| HP Landscape | Hero ringkas, badge disembunyikan |

---

## 📞 Kontak & Informasi Brand

| Platform | Info |
|---|---|
| 📱 WhatsApp | [0851-4239-9263](https://wa.me/6285142399263) |
| ✉️ Email | shandaamelia90@gmail.com |
| 📷 Instagram | [@DIYbyLiyaaa](https://instagram.com/DIYbyLiyaaa) |
| 📍 Alamat | Jl. Kota Baru Parahyangan No.17 |

---

## 📝 Catatan untuk Admin

- Setiap pesanan masuk akan mengirim **pesan WhatsApp otomatis** ke nomor admin yang berisi detail lengkap (nama, HP, alamat, produk, kurir, dan total bayar).
- Untuk **menambah produk baru**, edit array `PRODUCTS` di dalam tag `<script>` pada file `index.html`.
- Untuk **mengubah harga ongkir**, edit nilai `data-price` pada elemen `.ongkir-opt` di bagian cart drawer HTML.
- Untuk **mengubah rekening bank**, cari teks `1320030631197` di dalam file dan ganti sesuai kebutuhan.
- Semua gambar disimpan dalam objek `const IMG = { ... }` di bagian atas script — ganti nilai base64-nya untuk mengubah foto produk.

---

*© 2026 DIY by Liyaaa — Fashion Handmade dengan Cerita 🌸*
