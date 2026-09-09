# Webmaster RW 09 Kaligawe

Admin RW sekarang memiliki CMS penuh untuk seluruh menu publik yang sudah ada.

## Yang dapat diedit Admin RW
1. Nama setiap menu utama.
2. Deskripsi setiap menu.
3. Urutan menu utama.
4. Tampil/sembunyikan menu utama.
5. Judul halaman.
6. Subjudul/deskripsi halaman.
7. Isi teks/deskripsi.
8. Banyak blok konten pada satu menu.
9. Gambar, video, PDF, dan lampiran.
10. Draft / publikasi.
11. Mode "isi utama halaman" untuk mengganti isi bawaan halaman dengan CMS.
12. Nama RW, slogan, badge hero, judul hero, deskripsi hero.
13. Nama Ketua RW, WhatsApp, email, jam pelayanan, footer.

## Menu yang dikendalikan CMS
Beranda, Profil, Layanan, Surat Online, Berita, Agenda, Data RT, Data Warga, Dokumen, Galeri, Keuangan, Aspirasi.

## Database
Jalankan `supabase/schema.sql`. Versi ini menambahkan:
- `site_menu`
- `site_settings`
- `replace_default` pada `site_content`

## Catatan
Aplikasi tetap menggunakan autentikasi Supabase. Hanya profile dengan role `rw_admin` yang boleh mengubah CMS/menu.
