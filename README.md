# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
## 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
</head>
<body>
    <header>
      <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
    <nav>
      <a href="lab2_css_dasar.html">CSS Dasar</a>
      <a href="lab2_css_eksternal.html">CSS Eksternal</a>
      <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- CSS ID Selector -->
    <div id="intro">
      <h1>Hello World</h1>
      <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML dan CSS.</p>
      <!-- CSS Class Selector -->
      <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>
</body>
</html>
~~~~
![1a](https://user-images.githubusercontent.com/81820421/114268443-57aa9380-9a2b-11eb-8687-0b243799bcfe.JPG)
![1b (2)](https://user-images.githubusercontent.com/81820421/114268445-5a0ced80-9a2b-11eb-9655-58b2871841d1.JPG)

## 2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
~~~
+<head>
    <title>CSS Dasar</title>
    <style>
        body {
            font-family:'Open Sans', sans-serif;
        }
        header {
            min-height: 80px;
            border-bottom:1px solid #77CCEF;
        }
        h1 {
            font-size: 24px;
            color: #0F189F;
            text-align: center;
            padding: 20px 10px;
        }
        h1 i {
            color:#6d6a6b;
        }
    </style>
</head>
~~~
![2a](https://user-images.githubusercontent.com/81820421/114268549-cee02780-9a2b-11eb-89bf-f596e85a287a.JPG)
![2b](https://user-images.githubusercontent.com/81820421/114268551-d0115480-9a2b-11eb-9394-2ee39aa6f8df.JPG)

## 3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag
~~~
<p style="text-align: center; color: #ccd8e4;">
~~~
![1a](https://user-images.githubusercontent.com/81820421/114268443-57aa9380-9a2b-11eb-8687-0b243799bcfe.JPG)
![1b (2)](https://user-images.githubusercontent.com/81820421/114268445-5a0ced80-9a2b-11eb-9655-58b2871841d1.JPG)
## 4. Membuat CSS Ekstrernal
Buatlah file baru dengan nama Style_eksternakl.css kemudian deklarasi CSS seperti berikut.
~~~4nav {
    background: #20A759;
    color:#fff;
    padding: 10px;
}
nav a {
    color: #fff;
    text-decoration: none;
    padding:10px 20px;
}
nav .active,
nav a:hover {
    background: #0B6B3A;
}
~~~

![4a](https://user-images.githubusercontent.com/81820421/114268887-b6710c80-9a2d-11eb-9f66-7323af96f584.JPG)
![4b](https://user-images.githubusercontent.com/81820421/114268889-ba9d2a00-9a2d-11eb-99c0-c7b8c589f9e7.JPG)

Kemudian tambahkan tag untuk merujuk ke file css yag sudah dibuat pada bagian 
    ~~~
    <head>
        <!-- menyisipkan css eksternal -->
        <link rel="stylesheet" href="style_eksternal.css" type="text/css">
    </head>
    ~~~
 ![4c](https://user-images.githubusercontent.com/81820421/114268921-051ea680-9a2e-11eb-9b65-61e2cee473bd.JPG)
![4d](https://user-images.githubusercontent.com/81820421/114268923-064fd380-9a2e-11eb-9a07-d10be4775ecb.JPG)

## 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.
~~~
/* ID Selector */
#intro {
    background: #418fb1;
    border: 1px solid #099249;
    min-height: 100px;
    padding: 10px;
}
#intro h1 {
    text-align: left;
    border: 0;
    color: #fff;
}
/* Class Selector */
.button {
    padding: 15px 20px;
    background: #bebcbd;
    color: #fff;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
}
.btn-primary {
    background: #E42A42;
}
~~~


![6a](https://user-images.githubusercontent.com/81820421/114269063-e10f9500-9a2e-11eb-922f-511771ba1dd1.JPG)
![6b](https://user-images.githubusercontent.com/81820421/114269065-e240c200-9a2e-11eb-81e0-a4f8577d2bf2.JPG)
