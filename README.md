# UAS_KBP_POMODORO
Pomodoro Timer Application
Deskripsi
Aplikasi Pomodoro ini dirancang untuk membantu pengguna meningkatkan produktivitas dengan menerapkan teknik Pomodoro. Teknik ini melibatkan sesi kerja terfokus diikuti dengan waktu istirahat, yang dapat membantu meningkatkan konsentrasi dan efisiensi. Aplikasi ini menyediakan antarmuka yang sederhana dan intuitif untuk mengelola waktu belajar dan tugas.

Struktur Proyek
Proyek ini terdiri dari tiga file utama:

index.html: File HTML yang berisi struktur dan konten aplikasi.
style.css: File CSS yang mengatur tampilan dan gaya aplikasi.
script.js: File JavaScript yang mengelola logika dan interaksi aplikasi.
Penjelasan Kode
1. index.html
Struktur Dasar: Menggunakan elemen HTML5 dengan pengaturan karakter dan viewport untuk responsivitas.
Link CSS: Menghubungkan file style.css untuk menerapkan gaya pada aplikasi.
Ikon Pengaturan: Menggunakan Font Awesome untuk menampilkan ikon pengaturan di sudut kanan atas.
Timer Pomodoro: Menampilkan timer dengan format menit dan detik, diatur untuk sesi belajar 25 menit.
Kontrol Timer: Tombol untuk mengatur ulang timer.
To-Do List: Input untuk menambahkan tugas baru dan daftar tugas yang ditampilkan di bawahnya.
Spotify Widget: Menyediakan widget untuk mendengarkan musik dari Spotify, meningkatkan suasana saat bekerja.
Modal Pengaturan: Menyediakan pengaturan untuk durasi Pomodoro dan waktu istirahat, yang dapat disesuaikan oleh pengguna.
2. style.css
Gaya Umum: Mengatur font, latar belakang, dan warna teks untuk seluruh aplikasi agar terlihat menarik.
Pengaturan Timer: Mengatur ukuran font dan efek hover untuk meningkatkan interaksi pengguna.
Tombol Kontrol: Mengatur gaya untuk tombol kontrol dengan efek hover yang responsif.
Modal: Mengatur tampilan modal pengaturan, termasuk latar belakang transparan dan bayangan untuk memberikan efek kedalaman.
To-Do List: Mengatur gaya untuk daftar tugas, termasuk item dan tombol hapus, agar mudah dibaca dan digunakan.
3. script.js
Inisialisasi Variabel: Menyimpan status timer, durasi Pomodoro, dan durasi istirahat dalam detik.
Fungsi Penyimpanan dan Pemulihan Pengaturan: Menggunakan localStorage untuk menyimpan dan memuat durasi Pomodoro dan istirahat agar tetap konsisten antar sesi.
Fungsi Timer: Mengatur logika untuk menghitung mundur timer dan memperbarui tampilan setiap detik.
Event Listeners:
Mengatur durasi Pomodoro dan istirahat melalui input slider.
Mengelola interaksi pengguna dengan timer (mulai, jeda, reset).
Menambahkan dan menghapus tugas dari To-Do List dengan interaksi yang mudah.
Fungsi Suara: Memutar suara alarm saat waktu habis untuk memberi tahu pengguna.
Cara Menggunakan
Clone Repository:
bash
Insert Code
Run
Copy code
git clone <URL_REPOSITORY>
Jalankan Server Lokal:
Gunakan XAMPP atau server lokal lainnya untuk menjalankan aplikasi.
Akses Aplikasi:
Buka browser dan akses http://localhost/pomodoro/index.html.
