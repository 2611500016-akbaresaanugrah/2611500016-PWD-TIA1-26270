
# Pertemuan 3 - Formulir HTML dan CSS Dasar

## Baseline
- Menggunakan hasil P2 sebagai dasar pengembangan P3.
- Menyalin `index.html` dan `img/foto-profil.jpg` ke `pertemuan-03/`.

## Implementasi Formulir
- Elemen form yang digunakan: [form, label, input, textarea, select + option, dan button]
- Tipe input yang digunakan: [teks,email,number,date,radio,dan checkbox]
- Atribut validasi yang digunakan: [required,min,max,minlength,dan placeholder]

## Pengujian GET dan POST
- Hasil pengujian GET: [berhasil dan muncul di url]
- Contoh URL encoding yang ditemukan: [(https://2611500016-akbaresaanugrah.github.io/2611500016-PWD-TIA1-26270/pertemuan-03/index.html?nama=Akbar+Esa+Anugrah&email=2611500016%40mahasiswa.atmaluhur.ac.id&semester=1&tanggal=2008-02-09&jenis_pesan=pertanyaan&minat=HTML&minat=CSS&prodi=TI&pesan=apakah+ini+sudah+benar)]
- Hasil pengujian POST: [saat formulir dikirim menggunakan post muncul tulisan 405 not allowed,berarti tidak mendukung menggunakan metode post]

## CSS Dasar
- Selector elemen: [body,label,input,textarea,dan button]
- Selector class: [form-grup dan input-form]
- Selector ID: [#about dan #contact]
- Properti CSS dasar yang digunakan: [collor,background-collor,font-family,font-size,margin,border,dan pading]

## Pengujian dan Perbaikan
- Galat yang ditemukan: Pada pengujian awal interaksi formulir, label harus dipastikan tepat menarget kontrol masukan terkait, dan seluruh kontrol masukan harus memiliki atribut name agar nilainya terkirim saat submit.
- Penyebab galat: Atribut for pada <label> harus identik dengan id kontrol masukan agar klik label dapat memfokuskan kursor; peramban tidak akan mengirim kontrol masukan ke dalam parameter GET jika atribut name belum ditentukan.
- Perbaikan yang dilakukan: Memastikan sinkronisasi seluruh pasangan atribut for dan id, melengkapi atribut name pada semua kontrol masukan, memastikan path gambar img/foto-profil.jpg valid, serta memastikan formulir kembali menggunakan method="get" setelah demonstrasi pengujian POST.
- Hasil pengujian ulang: Klik pada seluruh label berhasil mengarahkan fokus ke kontrol input pasangannya, validasi bawaan HTML (required, format email, batasan semester, dan panjang karakter) berfungsi dengan tepat menahan submit saat belum valid, query string GET terbentuk dengan rapi beserta URL encoding yang valid, dan tampilan visual formulir tersusun konsisten serta mudah dibaca.

## GitHub Pages
URL: [(https://2611500016-akbaresaanugrah.github.io/2611500016-PWD-TIA1-26270/pertemuan-03/)]