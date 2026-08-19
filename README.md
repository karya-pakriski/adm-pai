# adm-pai
Administrasi PAI SK Kakanwil Kemenag 522 Tahun 2026

## Cara Penggunaan

1. Buka URL GitHub Pages.
2. Masukkan ID dan PIN, klik **Masuk**.
3. Setelah masuk, pilih kelas pada sidebar untuk melihat daftar dokumen.
4. Klik judul dokumen untuk membuka pratinjau.
5. Di dalam pratinjau, klik **Unduh PDF** atau **Unduh DOCX**.

## Kustomisasi Template

- Template HTML menggunakan placeholder `{{...}}` yang akan diganti dengan data pengguna, misalnya `{{NAMA_GURU}}`, `{{NAMA_SEKOLAH}}`, `{{NIP_GURU}}`, dll.
- Gunakan HTML tradisional dengan **inline CSS** untuk hasil terbaik di Google Docs/Word.
- Hindari CSS modern seperti `flex`, `grid`, `calc`, `position: fixed/absolute`.
- Gunakan tabel untuk layout data dan paragraf dengan `text-align: justify` untuk kerapian.
- Jika ingin menambah template baru, cukup upload file HTML ke folder `templates/`, lalu tambahkan baris baru di sheet `Templates`.

## Catatan Penting

- Konversi DOCX melalui Google Docs membutuhkan waktu 3-10 detik.
- Terdapat kuota harian Google Apps Script (URL Fetch, Drive). Gunakan caching untuk menghemat.
- Pastikan file template di GitHub dapat diakses publik (raw URL).
- Jangan simpan PIN di `localStorage`; gunakan `sessionStorage` seperti pada contoh.

## Lisensi

Proyek ini bebas digunakan untuk keperluan pendidikan.
