# Element HTML
element html adalah komponent dasar dari dokumen html. setiap elemen terdiri dari tag pembuka, konten, dan tag penutup. sebagai contoh, elemen pragraf di tulis sebagai berikut:

```html
<p>ii adalah sebuah pragraf</p>
```
### setruktur elemen umum
```html
<tagename>konten</tagname>
```
### contoh elemen html umum

#### paragraf(`<p>`)
Digunakan untuk menampilkan teks dalam bentuk paragraf.
```html
<p>Ini adalah paragraf pertama.</p>
```
#### Heading (`<h1>` hingga `<h6>`)
Digunakan untuk judul dan subjudul. `<h1>` adalah yang paling penting, sedangkan `<h6>` adalah yang paling tidak penting.
```html
<h1>ini adalah h1</h1>
<h2>ini adalah h2</h2>
<h3>ini adalah h3</h3>
<h4>ini adalah h4</h4>
<h5>ini adalah h5</h5>
<h6>ini adalah h6</h6>

```
#### reselut
<h1>ini adalah h1</h1>
<h2>ini adalah h2</h2>
<h3>ini adalah h3</h3>
<h4>ini adalah h4</h4>
<h5>ini adalah h5</h5>
<h6>ini adalah h6</h6>

#### Link (`<a>`)
Digunakan untuk membuat hyperlink.
```html
<a href="https://www.example.com">Kunjungi Example</a>
```
<a href="https://www.example.com">ini link</a>

#### gambar (`<img>`)
Digunakan untuk menampilkan gambar.
```html
<img src="gambar.jpg" alt="Deskripsi Gambar">
```
#### Daftar ( `<ul>`, `<ol>`, `<li>`)

Digunakan untuk membuat daftar tak terurut ( `<ul>`) atau terurut ( `<ol>`).

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```
#### Atribut HTML

Definisi Atribut: Atribut adalah tambahan informasi yang dapat ditambahkan ke elemen HTML untuk memberikan lebih banyak konteks atau mengubah perilaku elemen tersebut. Atribut dituliskan di dalam tag pembuka.

#### Atribut `href` pada `<a>`

href berfungsi untuk menentukan URL yang  akan di buka saat link di klik

### Atribut `class` dan `id`

`class` di gunakan untuk mengelompokkan beberapa elemen dengan gaya yang sama, sedangkan `id` memberikan identifikasi unik untuk elemen tertentu.

#### Atribut `style`
atribut ini di gunakan untuk menambahkan css pada suatu elemen langsung pada HTML. contohnya:
```html
<p style="color: red;">Ini adalah paragraf berwarna merah.</p>
```

#### Contoh Penggunaan Elemen dan Atribut
Berikut adalah contoh dokumen HTML sederhana yang menggabungkan elemen dan atribut:
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Elemen dan Atribut HTML</title>
</head>
<body>
    <h1>Selamat Datang di Website Saya</h1>
    <p>Ini adalah paragraf pertama di halaman ini.</p>
    <p>Untuk informasi lebih lanjut, <a href="https://www.example.com" target="_blank">klik di sini</a>.</p>
    <img src="gambar.jpg" alt="Deskripsi Gambar">
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
    </ul>
</body>
</html>
```
