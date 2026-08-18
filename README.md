# Situs AJOINVEST

Situs statis pribadi: screening akumulasi asing harian (IDX) + blog + tentang.

## Isi
- `index.html` — Beranda
- `about.html` — Tentang Saya
- `screening.html` — Screening harian (diganti tiap hari)
- `blog.html` — Daftar artikel blog
- `posts/` — Artikel blog
- `.nojekyll` — memberitahu GitHub Pages agar menyajikan file apa adanya

Catatan: setiap halaman punya CSS-nya sendiri di dalam file (inline `<style>`),
supaya upload ke GitHub tidak pernah gagal karena file terpisah. File
`assets/style.css` TIDAK dipakai oleh halaman mana pun (boleh diabaikan/dihapus).

## Cara update screening harian
1. Kirim PDF Foreign Transaction (Sesi 1) ke asisten, minta "buatkan screening.html".
2. Ganti file `screening.html` di repo ini (Edit → paste → Commit).
3. Situs otomatis ter-update dalam 1–2 menit.

## Personalisasi
- Instagram sudah terpasang di footer: https://www.instagram.com/ajo.invest
- (Opsional) Nama asli di `about.html` jika ingin lebih personal

Bukan rekomendasi jual/beli. Konten untuk edukasi.
