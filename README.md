### HTML Lanjutan
## Membuat list

Buat file HTML dengan nama lab3_list.html kemudian tulis tag dasar HTML seperti dibawah.

![Gambar 1](screenshot1/ss1a.png)

List terbagi kedalam 3 bagian, yakni ordered list, unordered list dan description list.

# Membuat ordered list

Pertama beri judul dengan menggunakan tag `<h2>`. Untuk membuat ordered list menggunakan tag `<ol>`, di dalam tag `<ol>` ada tag `<li>` agar ada nomornya. Dan ordered list ini di bungkus oleh tag `<section>` yang di beri ID agar mudah di berikan style CSS.

![Gambar 2](screenshot1/ss2a.png)

Dan ordered list ini di simpan di tag `<body>` seperti gambar berikut.

![Gambar 3](screenshot1/ss2b.png)

Kemudian ini tampilannya di browser.

![Gambar 4](screenshot1/ss2c.png)

# Membuat unordered list

Untuk membuat unordered list menggunakan tag `<ul>` yang diberi ***type="square"*** agar yang tadinya angka akan berubah jadi kotak. Di dalam tag `<ul>` ada tag `<li>`, dan unordered list ini di bungkus oleh tag `<section>` yang di beri ID agar mudah di berikan style CSS dan diberi judul dengan tag `<h2>`. Penempatannya juga di simpan di tag `<body>`.

![Gambar 5](screenshot1/ss3a.png)

Ini tampilannya di browser.

![Gambar 6](screenshot1/ss3b.png)

# Membuat description list

Untuk membuat description list menggunakan tag `<dl>`, di dalamnya ada tag `<dt>` dan tag `<dd>`. Untuk tag `<dd>` tulisan akan otomatis bergeser ke kanan, sehingga tag `<dt>` menjadi sebuah judul dari tag `<dd>`. dan description list ini di bungkus oleh tag `<section>` yang di beri ID agar mudah di berikan style CSS dan diberi judul dengan tag `<h2>`. Penempatannya juga di simpan di tag `<body>`.

![Gambar 7](screenshot1/ss4a.png)

Dan ini tampilannya di browser.

![Gambar 8](screenshot1/ss4b.png)

## Membuat tabel

Buat file HTML dengan nama lab3_tabel.html kemudian tulis tag dasar HTML seperti dibawah.

![Gambar 9](screenshot2/ss1a.png)

Kemudian untuk membuat tabel menggunakan tag `<table>` yang di dalamnya di tambahkan ***border*** untuk mengatur tebal tabel, dan ***cellpadding*** untuk memberi jarak antara border dengan content/bacaan dalam sel. 

Tabel mempunyai head dan body, untuk head menggunakan tag `<thead>` dan untuk body menggunakan tag `<tbody>`.  Di dalam tag `<thead>` terdapat tag `<tr>` yang merupakan tag untuk membuat tabel kolom secara horizontal, dan di dalam tag `<tr>` terdapat tag `<th>` untuk mengisikan data atau judul dari masing masing kolom.

Kemudian body menggunakan tag `<tbody>` yang di dalamnya ada tag `<tr` dan di dalam tag `<tr` ada tag `<td>`, dimana tag `<td>` fungsinya sama dengan tag `<th>`.
Untuk tag `<tr` yang pertama merupakan baris kedua,  tag `<tr` yang kedua merupakan baris ketiga dan seterusnya. Contohnya seperti gambar dibawah.

![Gambar 10](screenshot2/ss1b.png)

Ini tampilannya di browser.

![Gambar 11](screenshot2/ss1c.png)

Agar tampilan tabelnya lebih bagus lagi, tambahkan ***cellspacing="0"*** pada tag `<table>` seperti gambar di bawah.

![Gambar 12](screenshot2/ss1d.png)

Ini tampilannya di browser.

![Gambar 13](screenshot2/ss1e.png)

Jadi spasi antar selnya hilang karena  ***cellspacing="0"***.

# Menggabungkan Sel Data

Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk 
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara 
horizontal). Di dalam tag `<table>` tambahkan ***border="1" cellpadding="6" cellspacing="0"***. Untuk tag `<tr>` pertama pada tag `<tbody>`, tag `<td>` yang kedua tambahkan atribut ***rowspan="3"***. Perhatikan gambar di bawah.

![Gambar 14](screenshot2/ss2a.png)

Ini tampilannya di browser.

![Gambar 15](screenshot2/ss2b.png)

## Membuat form

Buat file HTML dengan nama lab3_form.html kemudian tulis tag dasar HTML seperti dibawah.

![Gambar 16](screenshot3/ss1a.png)

Untuk membuat form menggunakan tag `<form>` kemudian tambahkan atribut ***action="proses.php" method="post"***, maksud dari  atribut ***action="proses.php"*** adalah data yang akan di proses di ambil dari file proses.php dengan ***method="post"*** adalah metode pengiriman data yang terpisah dengan url.

Untuk menambahkan garis yang berbentuk kotak gunakan tag `<fieldset>` dan gunakan tag `<legend>` untuk memberi nama form tersebut. 

Untuk setiap elemen di bungkus dengan tag `<p>`.

1. Tag `<p>` yang pertama berisi tag `<label>` dengan isi ***nama***, dan berisi tag `<input>` dengan ***type="text"***. 

2. Tag `<p>` yang kedua berisi tag `<label>` dengan nama ***alamat***, dan berisi tag `<textarea>`.

3. Tag `<p>` yang ketiga berisi tag `<label>` dengan nama ***jenis kelamin***, dan berisi dua tag `<input>` dengan ***type="radio"***. 

4. Tag `<p>` yang keempat berisi tag `<input>` dengan ***type="submit" value="login"***.

Perhatikan gambar di bawah.

![Gambar 17](screenshot3/ss1b.png)

Ini tampilannya di browser.

![Gambar 18](screenshot3/ss1c.png)

# Menabahkan Style pada Form

Agar tampilannya lebih cantik tambahkan deklarasi CSS menggunakan tag `<style>` yang di simpan pada tag `<head>`.

![Gambar 19](screenshot3/ss2a.png)

Ini tampilannya di browser.

![Gambar 20](screenshot3/ss2b.png)

## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.

![Gambar 21](screenshot3/ss3a.png)

Ini tampilannya di browser.

![Gambar 22](screenshot3/ss3b.png)
