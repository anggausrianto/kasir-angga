
Kasir Angga — PWA Bundle
========================

Isi:
- index.html → launcher PWA (mendaftar service worker + manifest)
- app.html → file aplikasi (custom yang sudah kamu minta)
- manifest.webmanifest → metadata PWA (name: Kasir Angga)
- sw.js → service worker untuk offline cache
- icons/ → ikon PWA berbagai ukuran

Cara pakai (hosting HTTPS disarankan agar kamera aktif):
1. Upload seluruh folder ini ke hosting (GitHub Pages / Netlify / Vercel).
2. Akses https://<domain>/<path>/
3. Klik menu browser → Add to Home Screen / Install App.

Offline/Local:
- Jalankan `python -m http.server 8000` di folder ini.
- Buka `http://localhost:8000/` di Chrome.
- Kamera tidak akan aktif jika dibuka dari file:// atau content://.
