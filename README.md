# Lab2Web
## Praktikum 2: CSS Dasar
### Tujuan
### Pada praktikum ini mahasiswa belajar:
1.Konsep dasar CSS.

2.Aturan penulisan CSS.

3.Selector (elemen, class, id).

4.Penerapan CSS pada HTML dengan internal, eksternal, dan inline.

## Langkah Praktikum

1.Membuat Dokumen HTML
Membuat file HTML dasar berisi struktur halaman dengan header, navigasi, konten, dan link.

2.Menambahkan CSS Internal
Menulis CSS langsung di dalam tag <style> pada bagian <head>. Internal CSS ini mempengaruhi elemen tertentu di halaman.

3.Menambahkan Inline CSS
Menulis aturan CSS langsung pada elemen dengan atribut style. Cara ini hanya mempengaruhi satu elemen saja.

4.Membuat CSS Eksternal
Membuat file terpisah dengan ekstensi .css kemudian dihubungkan dengan HTML menggunakan tag <link>. Dengan eksternal CSS, tampilan dapat dikelola lebih rapi dan konsisten di banyak halaman.

Menambahkan Selector ID dan Class

1.ID selector digunakan untuk memberi gaya khusus pada elemen tertentu dengan tanda #.

2.Class selector digunakan untuk memberi gaya pada kelompok elemen dengan tanda ..

<img width="969" height="925" alt="Screenshot 2025-09-30 110449" src="https://github.com/user-attachments/assets/3a496499-e08e-4158-b555-e4bef8166a3e" />
<img width="968" height="663" alt="Screenshot 2025-09-30 110512" src="https://github.com/user-attachments/assets/9c75c7c4-9d90-488e-a3cd-5eef9b99fbbf" />

Bagian header berisi judul dengan kombinasi teks biasa dan italic. Menu navigasi dibuat dengan tiga link menuju halaman lain. Pada bagian konten terdapat sebuah judul "Hello World", paragraf penjelasan tentang pembelajaran HTML dan CSS, serta sebuah tombol link dengan class khusus agar tampilannya berbeda. Selain itu ada juga sebuah paragraf dengan inline CSS sehingga tampil berwarna abu-abu muda dan berada di posisi tengah.

CSS internal digunakan untuk mengatur gaya umum halaman, seperti jenis font, tampilan header, ukuran dan warna judul, serta warna teks italic pada judul. Inline CSS digunakan untuk memberi gaya pada satu paragraf saja, yaitu dengan warna abu-abu muda.

CSS eksternal dipisahkan ke dalam file lain. Pada file eksternal tersebut, diatur tampilan menu navigasi agar memiliki background hijau, teks berwarna putih, serta efek hover ketika kursor diarahkan ke link. Selain itu, bagian konten dengan id “intro” diberikan background biru dengan border hijau, dan judul di dalamnya diatur agar rata kiri dan berwarna putih. Kemudian class selector digunakan untuk tombol. Class “button” memberikan padding, warna latar abu-abu, teks putih, serta tampilan seperti tombol, sedangkan class “btn-primary” memberi latar belakang merah. Karena tombol pada HTML menggunakan kedua class ini, hasil akhirnya adalah tombol merah dengan teks putih.

Dari kombinasi ini terlihat bagaimana ketiga cara penulisan CSS bekerja secara bersamaan: internal CSS untuk gaya umum, eksternal CSS untuk gaya yang terstruktur dan bisa dipakai ulang, serta inline CSS untuk gaya khusus satu elemen. Selain itu juga terlihat perbedaan antara selector ID yang lebih spesifik dibanding class, serta bagaimana class bisa digunakan bersama-sama pada satu elemen.


