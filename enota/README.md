# E-NOTA CV.SRHJ — halaman unduh APK (Vercel)

Halaman statis untuk mengunduh APK E-NOTA v4.5.0 (Jurnal Penjualan Telur CV. Sri Rejeki Horn Jember).

APK disematkan sebagai base64 di dalam `index.html` (tombol unduh merakit ulang file di browser),
karena file biner tidak bisa diunggah lewat konektor Vercel/MCP.

Untuk mengganti APK (mis. setelah di-sign di PC): ganti string base64 di `index.html`
dengan base64 dari APK baru, lalu push ke repo — Vercel deploy ulang otomatis.
