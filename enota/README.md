# E-NOTA CV.SRHJ — halaman unduh APK (Vercel)

Halaman statis untuk mengunduh APK E-NOTA v4.5.2 — Jurnal Penjualan Telur CV. Sri Rejeki Horn Jember.

APK (sudah ditandatangani dengan keystore baru SRHJ, sertifikat SHA-256 1285b489a6a01ec5c4bce7ce88e379c943b038c647abbc629baa4a2bf16801fb)
disimpan sebagai base64 di `apk.b64`; tombol unduh di `index.html` mengambilnya dari
raw.githubusercontent.com lalu merakit ulang jadi file APK di browser.

Untuk mengganti APK: ganti `apk.b64` (dan SHA/versi di `index.html`), lalu push ke repo —
halaman Vercel tidak perlu deploy ulang.
