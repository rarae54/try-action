# Simple Login + Dashboard (Static)

Repo ini contoh sederhana untuk deploy ke **Netlify** dengan halaman login dan dashboard.

## File
- `index.html` → halaman login
- `dashboard.html` → halaman setelah login sukses
- `log.php` (tidak termasuk, harus di-host di server PHP terpisah)

## Cara Deploy ke Netlify
1. Upload repo ini ke GitHub (atau fork).
2. Buka Netlify → Add new site → Import from GitHub.
3. Pilih repo ini.
4. Set **Publish directory** = `.` (root).
5. Deploy 🚀
6. Akses `https://namasite.netlify.app/`

> Jangan lupa edit `action` di `index.html` → ganti ke URL `log.php` yang kamu host di server PHP (misalnya 000webhost).
