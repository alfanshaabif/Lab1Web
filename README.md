# Praktikum 1 
# Pemrograman Web

```
Alfansha Abiftyo Hadyatama
311910321
TI.19.A.2
Universitas Pelita Bangsa
```

## Langkah 1 
Buka VSCode dan buat file HTML baru. Setelah itu buat struktur dasar HTML.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
<img width="960" alt="1" src="https://user-images.githubusercontent.com/56286071/112790768-4906c880-908a-11eb-8c96-36a6388453ba.png">

## Langkah 2
Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut.
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
    HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
    tag dasar html.</p>
```
<img width="960" alt="2" src="https://user-images.githubusercontent.com/56286071/112790951-b0bd1380-908a-11eb-9bad-0b6b919aaeb6.png">

## Langkah 3
Selanjutnya silakan ubah-ubah nilai atributnya (align => justify, left, right, dan center) untuk melihat 
perbedaan lainnya. 
```
<!-- Ini adalah paragraf pertama -->
<p align=”center”>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman 
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama 
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa 
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat 
    dengan menggunakan tag dasar html.</p>
```
<img width="960" alt="3(1)" src="https://user-images.githubusercontent.com/56286071/112791204-36d95a00-908b-11eb-9ab1-4442b08a158f.png">


Kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum 
paragraf kedua.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

<img width="960" alt="3(2)" src="https://user-images.githubusercontent.com/56286071/112791890-9a17bc00-908c-11eb-804a-45ef0406edb0.png">

## Langkah 4 
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
  
```
<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
<img width="960" alt="4" src="https://user-images.githubusercontent.com/56286071/112792802-532ac600-908e-11eb-884c-07e2b4cfe860.png">

## Langkah 5
Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian 
simpan file gambar tersebut satu folder dengan file dokumen html.


<img width="960" alt="5(1)" src="https://user-images.githubusercontent.com/56286071/112793129-ec59dc80-908e-11eb-8270-e338621dc9ef.png">

Kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3
sebelumnya.
``` 
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="logo_upb.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
<img width="960" alt="5(2)" src="https://user-images.githubusercontent.com/56286071/112793295-39d64980-908f-11eb-9ac8-06f89565a202.png">

## Langkah 6
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>  
```

<img width="960" alt="6" src="https://user-images.githubusercontent.com/56286071/112793937-52932f00-9090-11eb-8eaf-6e75cd6b0b69.png">

## Langkah 7
Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakan Hyperlink.
```
!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Alfansha Abiftyo Hadyatama, 311910321, TI.19.A.2.</p>

</body>
</html>
```
<img width="960" alt="7" src="https://user-images.githubusercontent.com/56286071/112795405-a56de600-9092-11eb-9de4-48abd022c74f.png">


# Jawab Pertanyaan

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ada, beda huruf besar dan kecilnyapun bisa menjadi penyebabnya program eror.
```
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!

```
Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.
```
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
Ketika gambar di tampilkan akan terlihat sebuah title. sedangkan, jika gambar gagal ditampilkan akan menampilkan teks atribut alt.
```
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Harus di isi semua, karena jika hanya salah satunya maka gambar tersebut akan terlihat terlalu lebar atau tinggi.
```
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
Menambah hyperlink baru dan menampilkan yg telah di tentukan, untuk blank dia akan menambah tab baru terlebih dahulu baru dia akan menampilkan link yang di tuju.
```
