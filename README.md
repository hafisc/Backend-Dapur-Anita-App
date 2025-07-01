# 🍽️ Dapur Anita Backend

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-10.x-red?logo=laravel" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-8.1-blue?logo=php" alt="PHP">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Build-Passing-brightgreen" alt="Build Status">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/laravel/laravel.png" width="100" alt="Laravel Logo"/>
</p>

---

## ✨ Deskripsi

**Dapur Anita Backend** adalah RESTful API berbasis Laravel yang mendukung aplikasi Dapur Anita. Backend ini menyediakan layanan otentikasi, manajemen produk, transaksi, dan fitur lain yang dibutuhkan aplikasi dapur modern.

---

## 🚀 Fitur Utama

- 🔐 Otentikasi & Otorisasi (Laravel Sanctum)
- 📦 Manajemen Produk
- 🛒 Transaksi & Pembayaran
- 📊 Laporan Penjualan
- 📁 Upload & Manajemen File
- 📬 Notifikasi
- 🌐 API Terstruktur & Dokumentasi

---

## 🗂️ Struktur Folder

```
Backend/
├── app/            # Source code utama (Models, Controllers, dll)
├── bootstrap/      # Bootstrap file Laravel
├── config/         # Konfigurasi aplikasi
├── database/       # Migrasi, Seeder, Factory
├── public/         # Public assets & entry point
├── resources/      # View, CSS, JS
├── routes/         # Routing API & Web
├── storage/        # File storage
├── tests/          # Unit & Feature tests
└── vendor/         # Dependency composer
```

---

## ⚡ Instalasi & Setup

1. **Clone repository**
   ```bash
   git clone https://github.com/username/dapur-anita.git
   cd dapur-anita/Backend
   ```
2. **Install dependency**
   ```bash
   composer install
   ```
3. **Copy file environment**
   ```bash
   cp .env.example .env
   ```
4. **Generate key**
   ```bash
   php artisan key:generate
   ```
5. **Migrasi database**
   ```bash
   php artisan migrate --seed
   ```
6. **Jalankan server**
   ```bash
   php artisan serve
   ```

---

## 🧪 Testing

Jalankan unit test:
```bash
php artisan test
```

---

## 🤝 Kontribusi

Kontribusi sangat terbuka! Silakan fork, buat branch, dan ajukan pull request.

---

## 📄 Lisensi

Proyek ini menggunakan lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail.

---

## 👩‍🍳 Kontak

- Email: dapuranita@example.com
- Instagram: [@dapuranita](https://instagram.com/dapuranita)

<p align="center">
  <img src="https://user-images.githubusercontent.com/674621/71187811-6b7cfa80-2258-11ea-9aa2-ecbfa2b8b1a5.png" width="120" alt="Cooking"/>
</p>

<details>
<summary>🎨 ASCII Art</summary>

```
   (\__/) ||
   (•ㅅ•) ||  Dapur Anita
   / 　 づ
```
</details>
