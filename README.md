# KantinGO — Kantin Sekolah Digital

Prototype website kantin sekolah berbasis HTML, CSS, dan JavaScript tanpa framework.

## Fitur
- Mode siswa dan penjual dengan navigasi yang berfungsi.
- Katalog makanan, snack, dan minuman dengan pencarian serta filter kategori.
- Keranjang, ubah jumlah, total belanja, dan checkout simulasi.
- Riwayat/status pesanan.
- Dashboard penjual: tambah/hapus menu, ubah stok, dan aktif/nonaktif menu.
- Penyimpanan data lokal melalui `localStorage` pada browser yang sama.
- Layout responsif untuk HP dan komputer.

## Jalankan lokal
Buka `index.html` di browser. Tidak perlu instalasi.

## Publikasikan dengan GitHub Pages
1. Buat repositori publik bernama `KantinGO`.
2. Unggah `index.html` ke direktori utama repositori (root), bukan di dalam folder tambahan.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu **Save**.
5. Tunggu deployment selesai. URL biasanya `https://USERNAME.github.io/KantinGO/`.

## Catatan
Ini masih prototipe demo. `localStorage` tidak menyinkronkan data antarpengguna/perangkat. Checkout bukan pembayaran nyata dan belum ada autentikasi atau database server.
