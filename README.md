# Moonlight Art Shop

Web promosi satu halaman untuk Moonlight Art Shop: alamat, peta, nomor WhatsApp, jam buka, dan contoh produk (Bahasa Indonesia + English).

Live: https://yblig.github.io/moonlight-art-shop/

## Cara mengubah data toko

Semua data ada di objek `TOKO` di bagian bawah `index.html`:

| Isian | Keterangan |
|---|---|
| `telepon` | Nomor WhatsApp format internasional tanpa `+`, contoh `6281234567890` |
| `teleponTampil` | Nomor yang tampil di halaman, contoh `+62 812-3456-7890` |
| `alamat`, `area` | Alamat lengkap dan kota singkat |
| `linkMaps` | Link "Bagikan" dari Google Maps (`https://maps.app.goo.gl/...`) |
| `cariDiMaps` | Koordinat (`-8.5069,115.2625`) atau nama toko persis seperti di Google Maps, dipakai untuk peta di halaman |
| `jam`, `jamSingkat` | Jam buka |
| `produk` | Daftar produk. Untuk pakai foto asli, taruh file di folder `images/` lalu isi `foto: "images/nama-file.jpg"` |

Simpan, commit, push: GitHub Pages akan memperbarui web dalam 1–2 menit.
