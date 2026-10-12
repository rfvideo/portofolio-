# Portofolio Azka (Yuura)

Website portofolio statis (HTML, CSS, JS). Tanpa build step, jadi langsung jalan di Vercel.

## Struktur
- `index.html` : isi halaman
- `style.css` : tampilan
- `script.js` : animasi ketik di hero + tahun footer
- `vercel.json` : konfigurasi Vercel
- `favicon.svg` : ikon tab

## Deploy ke Vercel
1. Buat repo kosong di GitHub (misal `portofolio`).
2. Di folder ini jalankan:
   ```bash
   git init
   git add .
   git commit -m "portofolio pertama"
   git branch -M main
   git remote add origin https://github.com/USERNAME/portofolio.git
   git push -u origin main
   ```
3. Buka vercel.com, klik **Add New > Project**, pilih repo `portofolio`.
4. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory. Klik **Deploy**.

Setiap `git push` berikutnya akan otomatis ter-deploy ulang.

## Yang perlu kamu cek
- Teks proyek di `index.html` (bagian "Proyek yang saya kerjakan") sesuaikan dengan peran aslimu.
- Tambahkan link thread/infografis terbaik di tiap proyek kalau ada.
- Ganti `ritualface.vercel.app` kalau URL dApp berubah.
- Bagian "Dalam pengembangan" di Velixir: ganti dengan link kalau sudah live.
