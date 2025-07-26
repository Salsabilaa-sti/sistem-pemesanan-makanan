# Sistem Pemesanan Makanan

Sistem Pemesanan Makanan adalah aplikasi berbasis web yang memungkinkan pengguna untuk memesan makanan secara online. Aplikasi ini dibangun menggunakan framework Django.

## Fitur Utama
- Registrasi dan login pengguna
- Melihat daftar makanan
- Melihat detail makanan
- Menambah makanan ke keranjang
- Melakukan pemesanan dan pembayaran
- Melihat riwayat pemesanan

## Struktur Direktori
- `makanan/` : Berisi gambar makanan
- `media/gambar_makanan/` : Media penyimpanan gambar makanan
- `order_makanan/` : Aplikasi utama untuk pemesanan makanan (model, views, forms, templates, dll)
- `pemesanan_makanan/` : Konfigurasi utama Django project
- `db.sqlite3` : Database SQLite
- `manage.py` : File manajemen Django

## Cara Menjalankan
1. **Clone repository**
2. **Install dependencies**
   
   Pastikan Python dan pip sudah terinstall, lalu jalankan:
   ```bash
   pip install -r requirements.txt
   ```
   *(Buat file requirements.txt jika belum ada, dengan minimal berisi `Django`)*

3. **Migrasi database**
   ```bash
   python manage.py migrate
   ```

4. **Jalankan server**
   ```bash
   python manage.py runserver
   ```

5. **Akses aplikasi**
   Buka browser dan akses `http://127.0.0.1:8000/`

## Kontribusi
Silakan fork repository ini dan buat pull request untuk kontribusi.

## Lisensi
Proyek ini menggunakan lisensi MIT.
