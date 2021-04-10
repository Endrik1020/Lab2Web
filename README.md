![1a](https://user-images.githubusercontent.com/81820421/114268443-57aa9380-9a2b-11eb-8687-0b243799bcfe.JPG)
![1b (2)](https://user-images.githubusercontent.com/81820421/114268445-5a0ced80-9a2b-11eb-9655-58b2871841d1.JPG)

# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
## 1. Membuat dokumen HTML
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

## 1. Mendeklarasikan CSS Internal
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

## Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag
~~~
<p style="text-align: center; color: #ccd8e4;">
~~~![3](https://user-images.githubusercontent.com/81820421/114268645-50d05080-9a2c-11eb-8bf1-1aba60dda5c2.JPG)
![3b](https://user-images.githubusercontent.com/81820421/114268646-53cb4100-9a2c-11eb-9e01-90ed47fd8d8b.JPG)

