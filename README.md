# Lab2Web
## Praktikum 2: CSS Dasar
### Tujuan
### Pada praktikum ini mahasiswa belajar:
1.Konsep dasar CSS.

2.Aturan penulisan CSS.

3.Selector (elemen, class, id).

4.Penerapan CSS pada HTML dengan internal, eksternal, dan inline.

## Langkah Praktikum
1. Membuat Dokumen HTML

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>
    <link rel="stylesheet" href="style_eksternal.css" type="text/css">
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
        <p>Kami sedang belajar HTML dan CSS dasar pada mata kuliah <b>Pemrograman Web</b> 
        di <i>Universitas Pelita Bangsa</i>.</p>

        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya</a>
    </div>

    <!-- Inline CSS -->
    <p style="text-align: center; color: #ccd8e4;">
        Paragraf dengan inline CSS
    </p>
</body>
</html>

```
2.Membuat File Eksternal CSS
```
/* NAVBAR */
nav {
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

/* ID Selector */
#intro {
    background: #418fb1;
    border: 1px solid #099249;
    min-height: 100px;
    padding: 10px;
}
#intro h1 {
    text-align: left;
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
```
3.input
<img width="1294" height="490" alt="image" src="https://github.com/user-attachments/assets/16c6abbe-4a54-4647-8328-4d21b5594f00" />




