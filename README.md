# KantinGO

Website kantin sekolah berbasis HTML, CSS, dan JavaScript.

## Deploy ke GitHub Pages
1. Buat repositori publik bernama `KantinGO` di GitHub.
2. Upload `index.html`, `README.md`, dan `.nojekyll` ke folder paling atas (root) repositori.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu tekan **Save**.
6. Tunggu proses deployment selesai. URL biasanya berbentuk `https://USERNAME.github.io/KantinGO/`. Ganti `USERNAME` dengan nama akun GitHub kamu.

## Fitur demo
- Mode Siswa dan Penjual.
- Daftar menu, pencarian, kategori, harga, dan stok.
- Keranjang dan checkout demo.
- Nomor dan status pesanan.
- Dashboard penjual untuk mengelola menu, stok, dan status pesanan.
- Penyimpanan lokal dengan `localStorage` di browser/perangkat yang sama.

## Batasan
Ini masih prototipe front-end. Data tidak tersinkron antarperangkat dan belum ada login aman, database/server online, pembayaran, atau notifikasi sungguhan. Jangan gunakan untuk transaksi nyata sebelum backend dan keamanan ditambahkan.
