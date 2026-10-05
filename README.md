# umramandiri

Website statis (HTML + CSS + JS, tanpa build step) untuk brand **umramandiri**.

## Sebelum deploy: edit 3 hal di `index.html`

Cari blok `/* ===== EDIT DI SINI ===== */` di bagian bawah file:

1. `WA` : ganti dengan nomor WhatsApp bisnis (format `62812xxxxxxx`).
2. `T`, `FIXED`, `MEAL` : angka estimasi kalkulator. Sesuaikan dengan harga riil terbaru.
3. Harga produk di bagian `#produk` (Rp 199.000, Rp 49.000, dst.).

Cek juga klaim regulasi di FAQ agar sesuai aturan terbaru.

## Deploy ke GitHub

```bash
git init
git add .
git commit -m "Initial commit: website umramandiri"
git branch -M main
git remote add origin https://github.com/USERNAME/umramandiri.git
git push -u origin main
```

## Deploy ke Vercel

1. Buka https://vercel.com/new dan import repo `umramandiri`.
2. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory.
3. Klik **Deploy**. Setiap `git push` ke `main` otomatis memperbarui situs.
4. Domain sendiri: Project Settings > Domains > tambahkan `umramandiri.com` (atau domain Anda).
