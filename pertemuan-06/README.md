# Pertemuan 6 - PHP Dasar dan Pemrograman Sisi Peladen

Pengembangan

Pada pertemuan ini, halaman profil mahasiswa dari pertemuan sebelumnya dikembangkan menggunakan PHP. File "index.html" diubah menjadi "index.php" agar dapat menjalankan kode PHP di sisi peladen.

Materi yang diterapkan meliputi:

- Penggunaan variabel dan konstanta PHP.
- Penggunaan tipe data dan operator.
- Percabangan "if", "elseif", "else", dan "switch".
- Operator ternary.
- Perulangan "for" dan "while".
- Fungsi bawaan PHP "number_format()" dan "date()".
- Penanganan nilai "null".
- Penggunaan sintaks singkat "<?= ... ?>".

File "style.css", "script.js", dan foto profil tetap digunakan dari pertemuan sebelumnya.

Pengujian

Pengujian dilakukan menggunakan Laragon dengan menjalankan Apache dan membuka halaman melalui browser menggunakan alamat localhost.

Hal-hal yang diuji:

1. Menjalankan PHP: Memastikan halaman "index.php" dapat dibuka melalui localhost tanpa menampilkan kode PHP sebagai teks.
2. Variabel dan konstanta: Memastikan nama mahasiswa, NIM, mata kuliah, dan tahun akademik tampil dengan benar.
3. Operator dan percabangan: Memastikan informasi semester, status mahasiswa, dan program studi ditampilkan sesuai nilai variabel.
4. Perulangan "for": Memastikan lima target belajar ditampilkan.
5. Perulangan "while": Memastikan daftar Semester 1 sampai Semester 3 ditampilkan.
6. Fungsi bawaan PHP: Memastikan IPK ditampilkan dalam format dua angka desimal dan tahun pada footer mengikuti tahun berjalan.
7. Tampilan halaman: Memastikan CSS, foto profil, navigasi, dan JavaScript tetap berfungsi.
8. Formulir: Memastikan formulir mengarah ke "index.php". Pemrosesan data formulir menggunakan PHP belum diterapkan pada pertemuan ini.

Hasil Pengujian

Isi berdasarkan hasil pengujian yang sebenarnya:

- Status akses localhost: [Berhasil / Gagal]
- Tampilan variabel dan konstanta: [Sesuai / Belum sesuai]
- Percabangan dan operator: [Sesuai / Belum sesuai]
- Perulangan "for" dan "while": [Sesuai / Belum sesuai]
- Fungsi bawaan PHP: [Sesuai / Belum sesuai]
- CSS, foto, dan JavaScript: [Berfungsi / Belum berfungsi]
- Formulir: [Sesuai / Belum sesuai]

Kendala dan Perbaikan

Kendala yang mungkin ditemukan adalah halaman tidak dapat diakses melalui localhost, kode PHP tidak berjalan, atau file pendukung tidak ditemukan.

Perbaikan dilakukan dengan memastikan Apache aktif di Laragon, nama file menggunakan "index.php", serta lokasi "style.css", "script.js", dan "img/foto-profil.jpg" sudah benar.

Catatan: Tuliskan kendala dan perbaikan yang benar-benar terjadi selama pengujian.

Kesimpulan

Melalui pertemuan ini, mahasiswa mempelajari dasar pemrograman PHP di sisi peladen, mulai dari variabel dan konstanta hingga percabangan, perulangan, dan fungsi bawaan PHP. Pengujian melalui localhost digunakan untuk memastikan kode PHP dapat dijalankan dengan benar.

Repository

- Repository GitHub: https://github.com/2611500016-akbaresaanugrah/2611500016-PWD-TIA1-26270
- Folder: "pertemuan-06"
- File utama: "index.php"