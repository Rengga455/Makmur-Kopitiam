# ☕ MAKMUR KOPITIAM — Digital Menu & Cafe Profile

Website katalog menu digital dan profil resmi untuk **MAKMUR KOPITIAM**, dirancang dengan pendekatan estetika *Modern Luxury (Fancy)* yang memadukan nuansa gelap elegan (*obsidian*) dengan aksen emas sampanye (*gold*).
Dibuat Oleh: Barengga Ss
🔗 **Live Demo:** [Lihat Website di Sini](https://username-anda.github.io/makmur-kopitiam/) *(Ganti dengan link GitHub Pages Anda)*

---

## 📌 Latar Belakang Proyek
Banyak kedai kopi dan kopitiam lokal masih mengandalkan daftar menu cetak atau gambar statis yang sulit diperbarui ketika terjadi perubahan harga maupun ketersediaan item. Proyek ini dibuat sebagai solusi katalog digital yang responsif, mudah diakses oleh pelanggan melalui perangkat seluler, serta memiliki struktur kode yang mudah dikelola oleh pemilik kafe tanpa perlu memahami pemrograman tingkat lanjut.

## ✨ Fitur Utama
* **Desain Elegan & Responsif:** Tampilan antarmuka bertema *Fancy* yang optimal di layar ponsel maupun desktop.
* **Katalog Menu Terstruktur:** Menampilkan daftar lengkap 20 minuman dan 10 camilan lengkap dengan foto, deskripsi, dan harga.
* **Filter Kategori & Pencarian Cepat:** Pengunjung dapat menyaring menu berdasarkan kategori (*Semua*, *Minuman*, *Camilan*) atau mencari menu spesifik secara *real-time*.
* **Manajemen Data Terpusat:** Seluruh daftar menu, harga, foto, serta informasi kontak kafe dikumpulkan dalam satu objek konfigurasi JavaScript (`KONFIGURASI_KAFE` & `MENU_DATA`) sehingga sangat mudah diubah sewaktu-waktu.
* **Integrasi Media Sosial:** Tautan langsung ke profil Instagram resmi kafe untuk memudahkan pelanggan melihat pembaruan terbaru.

## 🛠️ Teknologi yang Digunakan
* **HTML5** — Struktur semantik halaman web.
* **Tailwind CSS (via CDN)** — Penataan gaya (*styling*) modern dan tata letak responsif.
* **Vanilla JavaScript (ES6+)** — Logika rendering menu dinamis, fitur pencarian, filter kategori, dan fallback gambar otomatis.

---

## 📂 Struktur Folder
```text
makmur-kopitiam/
├── index.html          # File utama (HTML, CSS konfigurasi, & data menu JS)
└── README.md           # Dokumentasi proyek
