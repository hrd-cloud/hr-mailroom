# HR Mailroom

Sistem web statis untuk pencatatan, otomatisasi nomor surat, dan arsip *log* surat HR lintas entitas yang terhubung ke Google Sheets (`Log_Surat`) melalui Google Apps Script.

## Akses Aplikasi & Repository
- **URL Aplikasi Web (GitHub Pages):** `https://hrd-cloud.github.io/hr-mailroom/`
- **Repository:** `hrd-cloud/hr-mailroom`

## Alur Penggunaan Singkat
1. Buka URL aplikasi di *browser* laptop atau HP (bisa di-*Add to Home Screen* di HP).
2. Pada tab **Koneksi Sheets**, pastikan URL Web App Google Apps Script sudah tersimpan.
3. Gunakan tab **Generator & Input** untuk membuat nomor surat baru (nomor urut otomatis me-reset ke `01` per tahun dan per jenis surat) lalu simpan.
4. Gunakan tab **Buku Register** dan klik **Tarik dari Sheets** bila membuka di perangkat atau *browser* lain agar data tersinkron.

## Keamanan & Handover Tim HR
- **Hak Akses Data:** Batasi akses *sharing* file Google Sheets (`Log_Surat`) hanya ke akun email anggota tim HR yang berwenang.
- **Catatan Penting:** Jangan menaruh *password*, kode 2FA, atau data sensitif karyawan di dalam *file* repository.
- **Kolaborasi & Penerus:** Tambahkan anggota tim HR baru melalui **Settings → Collaborators** di GitHub, dan simpan catatan kredensial/akses di dokumen internal tim HR yang terpisah.
