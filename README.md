# Modul Pembelajaran

Deskripsi singkat:

Proyek ini berisi kumpulan halaman pembelajaran sederhana berbasis HTML dan CSS. File-file di dalam folder menyediakan halaman utama, materi, kuis, dan permainan kecil yang dapat dibuka langsung di browser.

**Struktur File**

- `index.html`: Halaman utama (entry point) untuk proyek.
- `materi.html`: Halaman yang berisi materi pembelajaran.
- `quiz.html`: Halaman kuis untuk menguji pemahaman.
- `game.html`: Halaman permainan edukatif (jika ada).
- `style.css`: File CSS umum untuk tampilan dasar.
- `materi.css`: Gaya khusus untuk `materi.html`.
- `quiz.css`: Gaya khusus untuk `quiz.html`.
- `game.css`: Gaya khusus untuk `game.html`.

**Cara Menjalankan (Local)**

1. Buka file `index.html` dengan browser (klik dua kali atau buka lewat menu Open File).
2. Untuk mengakses bagian tertentu, buka `materi.html`, `quiz.html`, atau `game.html` langsung di browser.
3. Tidak diperlukan server — proyek ini berjalan sebagai static HTML/CSS.

Catatan: Jika ada skrip JavaScript eksternal atau fitur yang membutuhkan server (mis. fetch API), jalankan server lokal sederhana seperti Live Server di VS Code atau `python -m http.server`.

**Mengedit / Mengembangkan**

- Gunakan editor teks (VS Code, Notepad++, Sublime, dll.) untuk mengedit file HTML/CSS.
- Jika menambahkan gambar, letakkan di folder terpisah (mis. `assets/` atau `images/`) dan perbarui path di HTML.
- Untuk perubahan gaya global, sesuaikan `style.css`. Untuk perubahan bagian spesifik, edit file CSS khusus (`materi.css`, `quiz.css`, `game.css`).

**Panduan Singkat untuk Kontributor**

- Pastikan menjaga struktur file agar mudah dinavigasi.
- Beri nama file gambar dan aset secara deskriptif.
- Jika menambahkan fitur interaktif, dokumentasikan dependensi atau langkah setup di README ini.


