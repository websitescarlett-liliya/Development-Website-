# DEVSPHERE

Playground 180 bahasa dengan fitur tambah bahasa custom dan multi-file editor dalam satu file HTML.

## Fitur Utama
- Auth sederhana (Login, Daftar, Gmail, GitHub)
- Playground 180 bahasa pemrograman
- Tambah bahasa baru via tombol + Bahasa
- Tambah file baru via tombol + File
- Search bahasa
- UI Glassmorphism dengan video background
- Responsive untuk mobile dan desktop

## Cara Pakai
1. Simpan kode sebagai `index.html`
2. Buka file tersebut di browser
3. Klik Daftar atau Masuk
4. Pilih bahasa, tulis kode, klik Jalankan

## Struktur File
Proyek ini hanya menggunakan satu file:

index.html
- Bagian <style> berisi seluruh CSS
- Bagian <body> berisi seluruh HTML
- Bagian <script> berisi seluruh JavaScript dan daftar 180 bahasa

Tidak memerlukan instalasi, build, atau server khusus.

## Menambah Bahasa Baru
Klik tombol + Bahasa, masukkan nama bahasa contoh: JSON.
Bahasa akan otomatis masuk ke dropdown dan halaman Fitur, serta tersimpan di localStorage.

Untuk menambah permanen via kode, edit array DEFAULT_LANGS di dalam tag script.

## Menambah File Baru
Klik tombol + File, masukkan nama file contoh: data.json atau style.css.
Gunakan tab di atas editor untuk berpindah file.

## Kustomisasi
- Video background: ganti URL pada tag source di dalam video id="bg-video"
- Kontak admin: ganti nomor pada fungsi chatAdmin() yaitu wa.me/6288801883795
- Reset bahasa custom: buka halaman Setting lalu klik Reset Bahasa Custom

## Teknologi
- HTML5
- CSS3
- JavaScript (Vanilla, tanpa framework)

## Lisensi
MIT - Bebas digunakan dan dimodifikasi.
