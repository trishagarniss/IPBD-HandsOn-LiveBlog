# 🚀 Panduan Menjalankan LiveBlogVerse

Project ini menggunakan **Vanilla JavaScript** dengan **Tailwind CSS (CDN)**. Karena aplikasi ini mengambil data dari API eksternal berbasis HTTP (`http://143.198.223.28:8000`), disarankan untuk menjalankannya melalui **Local Server** agar fitur CRUD berjalan lancar tanpa kendala blokir protokol keamanan browser (Mixed Content).

## 🛠️ Cara Menjalankan Secara Lokal
Pilih salah satu cara di bawah ini yang paling sesuai dengan *tools* yang terinstal di komputer Anda:

### 1. Menggunakan Python
Kalo punya Python, buka terminal/command prompt di folder project ini dan jalanin:
```bash
python -m http.server 8000
```
Lalu buka browser di alamat: http://localhost:8000

### 2. Menggunakan Node.js (npx)
Kalo punya Node.js terinstal, jalanin perintah ini:
```bash
npx serve
```
Lalu buka alamat yang tertera di terminal.

### 3. Akses via GitHub Pages
Kalo akses melalui link GitHub Pages, browser bakal memblokir data API secara otomatis karena perbedaan protokol (HTTPS ke HTTP).
**Agar data muncul, ikuti langkah berikut:**
1. Klik ikon **View site information** di sebelah kiri URL bar browser.
2. Pilih **Site Settings**
3. Cari bagian **Insecure Content**, lalu ubah menjadi **Allow**.
4. **Refresh** halaman web.
