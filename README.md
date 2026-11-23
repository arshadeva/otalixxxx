# Otalix
Pemutar musik web tanpa login, tema liquid glass biru. Developer: Oscar Mandala.

## Deploy ke GitHub Pages
1. Buat repo baru, upload semua isi folder ini ke branch `main`.
2. Buka Settings → Pages → Source: pilih **GitHub Actions**.
3. Setiap push ke `main` otomatis deploy lewat `.github/workflows/deploy.yml`.

## Catatan
- Pencarian memakai instance publik Piped/Invidious (daftar `PIPED` dan `INV` di `index.html`). Kalau ada yang mati, ganti URL-nya.
- Pemutaran lewat YouTube IFrame Player. Tempel link YouTube di kolom Cari untuk memutar langsung.
- Semua data (playlist, favorit, streak) tersimpan di localStorage perangkat.
