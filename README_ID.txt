PRICE LIST SETIA ABADI — PWA SHELL

ISI PAKET
- index.html: halaman PWA yang menampilkan web app Apps Script dalam iframe, dengan tombol Buka penuh sebagai cadangan.
- manifest.webmanifest: nama, ikon, dan pengaturan instalasi PWA.
- sw.js: cache untuk file kerangka PWA saja. Data produk tetap memerlukan internet.
- icons/: ikon aplikasi.

PENTING
Paket ini adalah tahap awal PWA/launcher. Google Apps Script dapat membatasi embedding/iframe. Jika tampilan aplikasi tidak muncul di dalam frame, gunakan tombol “Buka penuh”. Untuk pengalaman PWA yang sepenuhnya mulus dan kompatibilitas yang terjamin, frontend perlu dipindahkan ke hosting PWA dan integrasi backend Apps Script perlu disesuaikan.

CARA HOSTING GRATIS DI GITHUB PAGES
1. Buat repository baru di GitHub, misalnya price-list-setia-abadi-pwa.
2. Upload SEMUA isi folder paket ini ke root repository (index.html, manifest.webmanifest, sw.js, folder icons).
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch main dan folder /(root), lalu Save.
6. Tunggu URL https://USERNAME.github.io/price-list-setia-abadi-pwa/ aktif.
7. Buka URL itu di Chrome Android. Pilih menu ⋮ > Install app / Tambahkan ke layar utama.

CATATAN
- Ganti USERNAME dan nama repository sesuai milik Anda.
- Jangan hanya membuka index.html dari file lokal; PWA perlu HTTPS/localhost untuk installasi.
- Jika GitHub Pages mengaktifkan path repository, gunakan link Pages yang dihasilkan GitHub.
