# Pengenalan HTML

#### Daftar Isi

- [Pengenalan HTML](#pengenalan-html)
      - [Daftar Isi](#daftar-isi)
    - [Pengenalan awal](#pengenalan-awal)
    - [Membuat dokumen awal html](#membuat-dokumen-awal-html)
    - [Struktur dasar html](#struktur-dasar-html)
      - [1. Deklarasi](#1-deklarasi)
      - [2. Bagian Head](#2-bagian-head)
      - [3. Bagian Body](#3-bagian-body)
   



### Pengenalan awal

HTML (_Hypertext Markup Language_) adalah bahasa markup yang digunakan untuk membuat dan mendesain konten halaman web. HTML menggunakan serangkaian tag atau elemen untuk menentukan struktur dan konten dari sebuah halaman web.

HTML itu seperti batu bata untuk membangun rumah. Batu bata ini dapat disusun, hingga menjadi fondasi dasar.

![](./assets/html-css-js.png)

### Membuat dokumen awal html

- Membuka teks editor (vscode)
- Menuliskan struktur code html 
  
  ```cs
  <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
   
    </body>
    </html>

  ```

- Nama file untuk html
  - Setiap file HTML harus berekstensi .html, .xhtml (untuk XHTML), dan .htm saja. Jika tidak menggunakan ekstensi ini, maka ia tidak akan bisa dibaca oleh web browser.
  
  - Nama file HTML biasanya akan tercantum pada URL, maka sebaiknya hindari menggunakan spasi pada nama file HTML, agar URL yang dibentuk lebih bagus.
  
    ![](./assets/spasi.png)

### Struktur dasar html

![](./assets/struktur-html.png)


#### 1. Deklarasi 
   Ini adalah tag deklarasi untuk menyatakan tipe dokumen dan versinya. Pada contoh di atas, kita menyatakan dokumen ini bertipe HTML dan versinya adalah HTML 5.
    
#### 2. Bagian Head
Pada bagian HEAD, biasanya digunakan untuk menuliskan tag-tag yang akan dibaca oleh mesin.

Seperti:

- Tag meta untuk SEO;
- Tag ```<title>``` untuk judul;
- Tempat menulis kode CSS dan Javascript;

#### 3. Bagian Body
Bagian BODY adalah bagian yang akan ditampilkan pada web browser. Penulisannya di mulai dari tag ```<body>``` dan ditutup dengan ```</body>```.

