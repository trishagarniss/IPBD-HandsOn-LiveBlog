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

