Razy Al Farisi

 312410524

 ![foto](https://github.com/razyyalfarisi/foto/blob/926bc207eda811097af453e57dd7bca1dd7fe281/Screenshot%202025-10-29%20221947.png)

 Diletakkan di bagian atas.

Warna biru (`bg-primary`) dengan teks putih.

Berisi nama website dan menu: Home, About, ``Contact.

Menu berubah jadi tombol (☰) saat layar kecil → disebut responsive navbar.

 ![foto](https://github.com/razyyalfarisi/foto/blob/926bc207eda811097af453e57dd7bca1dd7fe281/Screenshot%202025-10-29%20221817.png)

 ```html
<div class="container mt-5">
  <div class="card p-4 shadow-sm">
```
`container` untuk memberi jarak dari tepi layar, card untuk tampilan seperti kotak putih dengan bayangan lembut.

```html
<div class="modal fade" id="berhasilModal">
```
Muncul setelah form dikirim. `bg-success` = header warna hijau tanda sukses. Menampilkan teks “Data telah berhasil dikirim 🎉”

```js
function tampilkanModal(event) {
  event.preventDefault();
  const modal = new bootstrap.Modal(document.getElementById('berhasilModal'));
  modal.show();
}
```
Mencegah halaman reload saat klik “Kirim”. Menampilkan modal pop-up sukses menggunakan fitur JS dari Bootstrap.

![foto](https://github.com/razyyalfarisi/foto/blob/926bc207eda811097af453e57dd7bca1dd7fe281/Screenshot%202025-10-29%20225451.png)

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
```
Navbar hitam di bagian atas halaman dengan teks putih. Berisi nama situs “Portfolio Saya”.

```html
<section class="container my-5">
  <div class="row align-items-center">
```
Menampilkan foto diri di kiri (`col-md-4`) dan deskripsi diri di kanan (`col-md-8`). `img-fluid rounded-circle` membuat foto berbentuk bulat dan menyesuaikan ukuran layar.

```html
<section class="container my-5">
  <h2 class="text-center mb-4">Portfolio Saya</h2>
```
Menampilkan 3 proyek dalam bentuk card Bootstrap yang rapi sejajar dalam 3 kolom (`col-md-4`). Setiap card berisi:

Gambar proyek (`img`)

Judul proyek (`card-title`)

Deskripsi singkat (`card-text`)
