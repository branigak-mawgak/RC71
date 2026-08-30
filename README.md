# Amalan Muslim RC71 V6.2.4 — iPad 10 PWA

Aplikasi ini dibuat langsung dari file baseline:
`AMALAN_MUSLIM_RC71_V6_2_4_FORCE_GALERI_MEDIA.html`

## Yang dipertahankan
- Isi dan logika HTML baseline tidak diubah.
- PDF, Auto Fokus, Smart Counter, Library, Catatan, dan Galeri Media tetap menggunakan kode baseline.
- Penambahan hanya berupa lapisan PWA/iPad:
  - `manifest.webmanifest`
  - `sw.js`
  - ikon aplikasi
  - metadata iPad/iOS
  - registrasi Service Worker

## Instalasi GitHub Pages
Upload seluruh isi folder ini ke root repository:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

GitHub Pages:
Settings → Pages → Deploy from a branch → main → /(root)

URL biasanya:
https://USERNAME.github.io/NAMA-REPOSITORY/

## Instalasi di iPad
Safari → buka URL aplikasi → Share → Add to Home Screen.

Catatan:
Jangan membuka `github.com/...` untuk menjalankan aplikasi.
Gunakan alamat GitHub Pages `USERNAME.github.io/...`.
