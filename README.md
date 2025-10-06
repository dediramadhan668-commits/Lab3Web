<h1><b>Langkah pertama:</b></h1>

Langkah pertama yang perlu kita lakukan adalah membuat sebuah dokumen HTML baru dengan nama lab3_list.html. Simpan file tersebut di dalam folder yang sesuai dengan struktur proyek atau direktori praktikum yang sedang digunakan, sehingga proses pengelolaan dan akses file akan lebih mudah dilakukan.
Untuk membuat file ini, kamu dapat memanfaatkan berbagai editor teks sesuai preferensi, misalnya Visual Studio Code, Sublime Text, atau bahkan aplikasi sederhana seperti Notepad. Setelah file berhasil dibuat, simpan dengan ekstensi .html agar sistem mengenali file tersebut sebagai dokumen HTML. File ini nantinya berfungsi sebagai media latihan untuk memahami dan menerapkan penggunaan list dalam HTML.

Tahap persiapan ini menjadi dasar sebelum masuk ke langkah berikutnya, yaitu menuliskan struktur utama dokumen HTML di dalam file tersebut.
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>
```



<h1><b>Langkah Kedua :</b></h1>
Membuat Ordered List
Setelah tahap persiapan selesai, langkah selanjutnya adalah menambahkan kode untuk membuat Ordered List. Ordered List atau daftar berurutan digunakan ketika elemen-elemen yang ditampilkan memiliki urutan yang jelas, biasanya ditandai dengan angka secara otomatis.

Masukkan potongan kode berikut ke dalam file lab3_list.html setelah struktur dasar HTML selesai dibuat:
```html
<section id="order-list">
  <h2>Ordered List</h2>
  <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
  </ol>
</section>
```
Hasil akhirnya seperti di gambar bawah ini.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/eae9f826-faa6-4cb1-8420-1da83b45ccfa" />


<h1><b>Langkah Ketiga:</b></h1>
Membuat Unorderd List
Setelah mendefinisikan Ordered List, tahap berikutnya adalah menambahkan Unordered List. Berbeda dengan Ordered List yang menggunakan penomoran, Unordered List menampilkan elemen dalam bentuk simbol atau bullet. Jenis bullet juga dapat diatur, misalnya lingkaran, kotak, atau default bulat kecil.

Tambahkan kode berikut setelah deklarasi Ordered List:
```html
<section id="unorder-list">
  <h2>Unordered List</h2>
  <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
  </ul>
</section>
```
Hasilnya akan seperti di bawah ini.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e14b6c12-9a9c-44ac-96a3-7524fc1340dc" />


<h1><b>Langkah Keempat:</b></h1>
Membuat Description List
Setelah menambahkan Unordered List, lanjutkan dengan membuat Description List. Jenis list ini digunakan untuk menampilkan pasangan istilah dan penjelasannya. Biasanya dipakai ketika ada istilah utama (ditulis dengan tag <dt>) yang diikuti oleh satu atau beberapa deskripsi (ditulis dengan tag <dd>).

Tambahkan potongan kode berikut setelah deklarasi Unordered List:
```html
<section id="unorder-list">
  <h2>Description List</h2>
  <dl>
    <dt>Fakultas Teknik</dt>
    <dd>Teknik Industri</dd>
    <dd>Teknik Informatika</dd>
    <dd>Teknik Lingkungan</dd>
    
    <dt>Fakultas Ekonomi dan Bisnis</dt>
    <dd>Akuntansi</dd>
    <dd>Manajemen</dd>
    <dd>Bisnis Digital</dd>
  </dl>
</section>
```
Akan menambahkan  Description List seperti di gambar ini.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/abd068f2-2c35-4471-8fc6-24e043972ad0" />


<h1><b>Langkah Kelima:</b></h1>
Membuat Table
Selanjutnya buat file HTML baru dengan nama lab3_tabel.html. File ini akan digunakan untuk latihan membuat tabel dalam HTML. Mulailah dengan menuliskan struktur dasar dokumen HTML seperti berikut:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat Table</h1>
  </header>
</body>
</html>
```
Setelah struktur dasar selesai, tambahkan kode tabel di dalam bagian <body> setelah tag <header>. Kode berikut akan membuat tabel dengan border, jarak antar sel, dan beberapa data fakultas serta program studi:

```html
<table border="1" cellpadding="4" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```
Tabel ini menampilkan tiga baris data di bawah judul kolom: No., Fakultas, dan Program Studi.Tabel ini menampilkan tiga baris data di bawah judul kolom: No., Fakultas, dan Program Studi.Tabel ini menampilkan tiga baris data di bawah judul kolom: No., Fakultas, dan Program Studi. Hasilnya seperti yang terdapat di gambar bawah ini.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/8ef5f75a-5627-452d-99ae-e005f416c69c" />


<h1><b>Langkah Keenam:</b></h1>
Menggabungkan Sel Data
Dalam HTML, kita dapat menggabungkan sel pada tabel dengan menggunakan atribut rowspan dan colspan.

rowspan berfungsi untuk menggabungkan sel secara vertikal (baris).
colspan digunakan untuk menggabungkan sel secara horizontal (kolom).

Contoh berikut menunjukkan penggunaan rowspan untuk menggabungkan kolom Fakultas menjadi satu sel, karena semua baris memiliki nilai yang sama, yaitu "Teknik":
```html
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>No.</th>
      <th>Fakultas</th>
      <th>Program Studi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td rowspan="3">Teknik</td>
      <td>Teknik Informatika</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Teknik Industri</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Teknik Lingkungan</td>
    </tr>
  </tbody>
</table>
```
Pada kode di atas, atribut rowspan="3" pada sel Fakultas membuat teks "Teknik" menempati tiga baris sekaligus. Hasilnya, tampilan tabel menjadi lebih rapi karena data fakultas tidak diulang. Hasil akhirnya seperti gamabar di bawah ini.


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ca66c8ad-d195-411b-a4cb-e2207978220d" />


<h1><b>Langkah Keenam:</b></h1>
Membuat Form
Buat terlebih dahulu file HTML baru dengan nama lab3_form.html. Tulis struktur dasar HTML seperti berikut:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML Lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat Form</h1>
  </header>
</body>
</html>
```
Setelah itu, tambahkan kode form di dalam elemen <body> setelah bagian <header>. Form ini berfungsi untuk menginput data pelanggan sederhana:

```html
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama">
    </p>
    
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L">
      <label for="jk_l">Laki-laki</label>
      
      <input id="jk_p" type="radio" name="kelamin" value="P">
      <label for="jk_p">Perempuan</label>
    </p>
    
    <p>
      <input type="submit" value="Login">
    </p>
  </fieldset>
</form>
```
Hasilnya seperti gambar di bawah ini:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9ccfd3a6-2290-4ab7-a3ef-904d4034ecb5" />


<h1><b>Langkah Ketujuh:</b></h1>
Menabahkan Style pada Form
Agar form yang sudah dibuat terlihat lebih menarik dan rapi, kita bisa menambahkan kode CSS sederhana. CSS ini mengatur tata letak label, mempercantik input teks, textarea, serta memberi gaya pada tombol submit.

Tambahkan kode berikut di dalam tag <head> sebelum penutup </head>:

```html
<style>
  form p > label {
    display: inline-block;
    width: 100px;
  }

  form input[type="text"], form textarea {
    border: 1px solid #197a43;
  }

  form input[type="submit"] {
    border: 1px solid #197a43;
    background-color: #197a43;
    color: #ffffff;
    font-weight: bold;
    padding: 5px 15px;
  }
</style>
```
Dengan kode di atas:
Label akan memiliki lebar tetap sehingga form lebih sejajar.
Input teks dan textarea diberi garis tepi berwarna hijau tua.
Tombol submit tampil dengan latar hijau, teks putih, serta gaya tegas karena font dibuat tebal.
Hasil akhirnya form jadi lebih enak dilihat dan lebih profesional.
Hasilnya seperti gambar di bawah ini.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/798b62a9-e98d-4521-a302-5469cee695fe" />


Kalian juga bisa improve CSS nya agar terlihat seperti yang kalian inginkan, contoh seperti di bawah ini:
<img width="1362" height="698" alt="image" src="https://github.com/user-attachments/assets/0df2fb09-95d8-4592-b6e8-c63ef29fae3a" />

## Pertanyaan dan Tugas

**1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.**

### Jawaban:

**Dropdown Menu**  
Dropdown menu digunakan untuk memilih satu opsi dari beberapa pilihan. Dibuat dengan tag `<select>` tanpa atribut `multiple`.  

```html
<label for="kota">Pilih Kota:</label>
<select id="kota" name="kota">
  <option value="jakarta">Jakarta</option>
  <option value="bandung">Bandung</option>
  <option value="surabaya">Surabaya</option>
  <option value="medan">Medan</option>
</select>
```

**Listbox dengan Multiple Selection**  
Listbox digunakan untuk menampilkan beberapa pilihan sekaligus. Dengan menambahkan atribut `multiple`, user bisa memilih lebih dari satu opsi.  

```html
<label for="hobi">Pilih Hobi:</label>
<select id="hobi" name="hobi[]" multiple size="4">
  <option value="membaca">Membaca</option>
  <option value="olahraga">Olahraga</option>
  <option value="musik">Musik</option>
  <option value="traveling">Traveling</option>
</select>
```

**Jika disatukan dalam sebuah form sederhana:**
<img width="1362" height="683" alt="image" src="https://github.com/user-attachments/assets/08366c8e-8fd1-4e58-b6eb-b971e0cc0040" />









