# Rifandi-Praktikum

Penjelasan latihan1.html:

Menggunakan CSS Internal
Semua style ditempatkan di dalam tag <style> pada bagian <head>.

Selektor Elemen (Tag Selector)

h1 { ... } berarti semua tag <h1> akan diberi style ini:

warna teks biru

font Verdana

ukuran 300% (3 kali ukuran normal)

p { ... } berarti semua tag <p> diberi:

warna teks merah

font Courier

ukuran 160%

Efeknya pada halaman:

Judul <h1> tampil besar dan biru.

Paragraf <p> tampil dalam warna merah dengan font monospace.

👉 Intinya:
HTML pertama menggunakan selektor berdasarkan elemen (h1, p) sehingga semua tag tersebut otomatis terkena style yang sama.

Penjelasan latihan2.html:

Selektor Class (.error)
CSS menargetkan hanya paragraf yang memiliki class error.

Selektor p.error artinya:

Apply CSS hanya untuk tag <p> yang memiliki class "error".

Efeknya:

<p class="error"> akan berwarna hijau

<p> biasa (tanpa class) tidak berubah warnanya (default hitam)

Contoh:

Ini tidak terkena style:

<p>Ini Paragraph</p>


Ini terkena style hijau:

<p class="error">Ini paragraph setelan class error.</p>


👉 Intinya:
HTML kedua menggunakan selektor class sehingga hanya elemen tertentu yang memiliki class tersebut yang mendapatkan style.
