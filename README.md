# Moonlight Art Shop

Web promosi satu halaman untuk Moonlight Art Shop (keramik, gerabah & dekorasi interior): alamat, peta, nomor WhatsApp, jam buka dengan status buka/tutup otomatis, dan galeri contoh produk. Bahasa Indonesia + English, dioptimalkan untuk HP.

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
| `zonaWaktu` | Zona waktu toko untuk status buka/tutup (`Asia/Makassar` = WITA, `Asia/Jakarta` = WIB) |
| `jam` | Jam buka per hari (`hari`: 0 = Minggu … 6 = Sabtu, `buka`/`tutup` format `HH:MM`) |
| `galeri` | Foto contoh produk (tanpa nama/stok). Taruh foto di folder `images/` lalu isi `foto: "images/produk-1.jpg"`. Tambah/kurangi baris untuk jumlah foto. |

Simpan, commit, push: GitHub Pages akan memperbarui web dalam 1–2 menit.

## File gambar

- `images/logo-mark.png`: logo lingkaran M
- `images/hero.jpg`: foto di bagian atas
- `images/produk-*.jpg`: galeri contoh produk
- `images/og-cover.jpg`: gambar preview saat link dibagikan
