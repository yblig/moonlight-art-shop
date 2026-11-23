# Moonlight Art Shop

Web promosi satu halaman untuk Moonlight Art Shop (keramik, gerabah & dekorasi interior): cara pesan lewat WhatsApp, lokasi Art Shop dengan peta, dan galeri contoh produk. Bahasa Indonesia + English, dioptimalkan untuk HP.

Live: https://yblig.github.io/moonlight-art-shop/

## Cara mengubah data toko

Semua data ada di objek `TOKO` di bagian bawah `index.html`:

| Isian | Keterangan |
|---|---|
| `telepon` | Nomor WhatsApp format internasional tanpa `+`, contoh `6281234567890` |
| `teleponTampil` | Nomor yang tampil di halaman, contoh `+62 812-3456-7890` |
| `alamat`, `area` | Alamat Art Shop dan lokasi singkat |
| `linkMaps` | Link "Bagikan" dari Google Maps (`https://maps.app.goo.gl/...`) |
| `cariDiMaps` | Koordinat (`-8.5069,115.2625`) atau nama toko persis seperti di Google Maps, dipakai untuk peta di halaman |
| `galeri` | Foto contoh produk (tanpa nama/stok). Taruh foto di folder `images/` lalu isi `foto: "images/produk-1.jpg"`. Tambah/kurangi baris untuk jumlah foto. |

Simpan, commit, push: GitHub Pages akan memperbarui web dalam 1–2 menit.

## File gambar

- `images/logo-mark.png`: logo lingkaran M
- `images/hero.jpg`: foto di bagian atas
- `images/produk-*.jpg`: galeri contoh produk
- `images/og-cover.jpg`: gambar preview saat link dibagikan
