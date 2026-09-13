<div align="center">

#  html-book

### Belajar HTML, tapi jangan cuma hafal. Pahami.

Study book HTML interaktif yang dibuat untuk membantu belajar HTML dari dasar
dengan contoh kode, preview langsung, penjelasan, playground, dan quiz.

<sub>made with HTML, CSS, JavaScript & a suspicious amount of motivation </sub>

<br>

![HTML](https://img.shields.io/badge/HTML-Study%20Book-orange)
![CSS](https://img.shields.io/badge/CSS-Responsive-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Interactive-yellow)
![Status](https://img.shields.io/badge/status-learning%20project-success)

</div>

---

##  Apa sebenarnya project ini?

`html-book` adalah website belajar HTML sederhana yang dibuat dengan satu
tujuan:

> **Biar belajar HTML nggak berhenti di "oh iya, `<p>` itu paragraf".**

Karena waktu belajar HTML, gampang banget buat sekadar menghafal:

```html
<p> = paragraf
<img> = gambar
<table> = tabel
<form> = form
````

Tapi saat ditanya:

> "Kenapa pakai tag ini?"

atau:

> "Apa bedanya `<th>` dan `<td>`?"

atau bahkan:

> "Sebenernya `<tbody>` itu bagian dari apa?"

langsung:

> 

Jadi website ini mencoba membawa alur belajar seperti ini:

```text
 Baca
   ↓
 Lihat kode
   ↓
 Lihat hasilnya
   ↓
 Pahami penjelasannya
   ↓
 Coba sendiri
   ↓
 Kerjakan quiz
   ↓
 Mulai paham
```

---

##  Fitur

###  HTML Tags

Belajar berbagai tag HTML melalui kartu yang berisi:

- nama tag
- fungsi
- contoh penggunaan
- preview
- contoh kode
- penjelasan tambahan

Beberapa kategori yang tersedia:

- Text
- Media
- Table
- Form
- Semantic HTML
- Interactive elements

---

###  Accurate HTML Preview

Preview dibuat supaya hasilnya sedekat mungkin dengan bagaimana browser
benar-benar merender HTML.

Ini penting karena tujuan project ini bukan sekadar membuat preview yang
"cantik", tapi membuat preview yang **berguna untuk belajar**.

Contohnya:

```html
<table>
  <thead>
    <tr>
      <th>Nama</th>
      <th>Nilai</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Alya</td>
      <td>95</td>
    </tr>
  </tbody>
</table>
```

Bukan hanya menampilkan tulisan `THEAD` atau `TBODY`, tetapi memperlihatkan
bagaimana mereka berada **di dalam struktur** **`<table>`**.

---

###  Table Learning

Bagian table dibuat sedikit lebih serius karena struktur tabel sering
membingungkan pemula.

Alurnya:

```text
<table>
 ├── <thead>
 │    └── <tr>
 │         └── <th>
 │
 ├── <tbody>
 │    └── <tr>
 │         └── <td>
 │
 └── <tfoot>
      └── <tr>
           └── <td>
```

Termasuk pembahasan:

- `<table>`
- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`
- `<tr>`
- `<th>`
- `<td>`
- `colspan`
- `rowspan`

---

###  HTML Playground

Ada playground kecil supaya kamu tidak cuma melihat contoh orang lain.

Tulis:

```html
<h1>Hello!</h1>
<p>Aku sedang belajar HTML.</p>
```

Lalu jalankan.

Hasilnya langsung muncul di preview.

Jadi konsepnya sederhana:

> **"Tulis HTML → lihat hasil → ubah → lihat lagi."**

---

###  Interactive Explanation

Beberapa materi punya penjelasan tambahan yang bisa dibuka ketika ingin
belajar lebih dalam.

Jadi tidak semua informasi dilempar sekaligus.

Kamu bisa:

```text
Penjelasan singkat
      ↓
"Pahami lebih dalam"
      ↓
Penjelasan tambahan
```

Supaya orang yang baru mulai nggak langsung ketemu dinding teks panjang. 

---

###  Search & Filter

Kalau sedang mencari sesuatu, tidak harus scroll satu halaman penuh.

Bisa mencari tag seperti:

```text
table
form
image
heading
semantic
```

dan menyaring berdasarkan kategori.

---

###  Quiz

Setelah belajar, ada quiz untuk melihat apakah materi tadi benar-benar
dipahami.

Quiz memberikan:

- soal
- pilihan jawaban
- progress
- skor
- feedback
- penjelasan jawaban

Jadi bukan cuma:

> "Benar / salah."

Tetapi juga:

> **"Kenapa jawaban ini benar?"**

---

###  Responsive

Project ini juga dibuat supaya tidak hanya nyaman digunakan di laptop.

Layout menyesuaikan:

-  Desktop
-  Laptop
-  Mobile
-  Small screen
-  Tablet

Beberapa bagian menggunakan layout responsif supaya kartu, form, playground,
dan quiz tidak berantakan ketika ukuran layar berubah.

---

##  Kenapa tampilannya colorful?

Karena belajar HTML tidak harus terlihat seperti dokumentasi browser tahun 2008. 

Warna digunakan untuk membantu membedakan jenis materi:

 konsep utama
 informasi penting
 form / interaction
 semantic & reference
 highlight
 special examples

Tapi preview HTML sendiri tetap dibuat supaya **tidak keliru dengan styling**
**website belajar**.

Dengan kata lain:

> **warna untuk membantu belajar, bukan untuk memalsukan hasil HTML.**

---

##  Tech Stack

Project ini sengaja dibuat sesederhana mungkin.

### HTML

Digunakan untuk:

- struktur halaman
- materi pembelajaran
- contoh HTML
- semantic structure

### CSS

Digunakan untuk:

- layout
- responsive design
- warna
- spacing
- card system
- visual feedback

### JavaScript

Digunakan untuk:

- interactive preview
- playground
- search
- filter
- quiz
- progress
- modal
- personalized greeting
- small interactions

---

##  Tidak menggunakan framework

Tidak ada:

- React
- Vue
- Next.js
- Tailwind
- build system
- package manager

Untuk project ini, vanilla HTML/CSS/JS sudah cukup.

Kenapa?

Karena project-nya sendiri tentang **belajar HTML**.

Rasanya agak lucu kalau untuk belajar HTML malah harus install 17 dependency
dulu. 

---

##  Cara Menjalankan

Clone repository:

```bash
git clone https://github.com/your-username/html-book.git
```

Masuk ke folder:

```bash
cd html-book
```

Kemudian buka file HTML di browser.

Atau lebih nyaman menggunakan VS Code + Live Server.

Tidak diperlukan proses build khusus.

---

##  Struktur Project

```text
html-book/
│
├── for her.html
└── README.md
```

Project ini masih intentionally sederhana.

Tidak banyak file karena fokus utamanya memang pengalaman belajar di satu
halaman.

---

##  Hal yang Bisa Dipelajari

Project ini saat ini mencakup topik seperti:

### HTML Basics

- Apa itu HTML
- Struktur dokumen
- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<body>`

### Text

- headings
- paragraph
- line break
- emphasis
- highlight
- subscript
- superscript
- links
- lists

### Media

- images
- `src`
- `alt`

### Tables

- table structure
- rows
- header cells
- data cells
- thead
- tbody
- tfoot
- caption
- colspan
- rowspan

### Forms

- form
- input
- label
- textarea
- select
- option
- button
- input types
- required
- placeholder
- name
- value

### Semantic HTML

- header
- nav
- main
- section
- article
- aside
- footer
- details
- summary
- figure
- figcaption

### Extra

- attributes
- id vs class
- comments
- HTML entities
- code / pre
- time
- abbr

---

##  Status Project

Project ini masih merupakan **learning project**.

Artinya:

- masih bisa ada bug
- beberapa materi bisa terus diperbaiki
- preview bisa terus dibuat lebih akurat
- UI masih bisa berubah
- materi masih bisa bertambah

Dan itu memang bagian dari proses.

Project ini tidak dibuat dengan tujuan menjadi dokumentasi HTML paling
lengkap di internet.

Tujuannya jauh lebih sederhana:

> **Membuat tempat belajar HTML yang enak dipakai dan gampang dipahami.**

---

##  Roadmap

Beberapa ide yang mungkin ditambahkan:

-  Dark mode
-  Save learning progress
-  More quiz questions
-  HTML challenges
-  Small coding challenges
-  Achievement / badges
-  Bookmark lessons
-  Better accessibility
-  CSS Study Book
-  JavaScript Study Book

---

##  Known Limitations

Beberapa hal yang perlu diketahui:

- Preview tetap bergantung pada browser yang digunakan.
- Tidak semua perilaku HTML dapat disimulasikan hanya dengan preview sederhana.
- Beberapa fitur browser membutuhkan permission tertentu.
- Project ini masih lebih fokus pada pembelajaran dasar daripada simulasi
  browser secara penuh.

Jadi kalau ada perbedaan kecil antara preview dan browser asli:

> **browser asli tetap menjadi sumber kebenaran.**

---

##  Contributing

Project ini masih kecil, jadi contribution sederhana sangat dihargai.

Kalau menemukan:

- typo
- penjelasan yang membingungkan
- contoh yang kurang tepat
- preview yang aneh
- responsive layout yang rusak

silakan buka:

**Issue** atau **Pull Request**.

---

##  Kenapa namanya `html-book`?

Karena project ini memang dimaksudkan seperti sebuah buku belajar.

Bukan buku yang harus dibaca dari halaman 1 sampai akhir.

Tapi buku yang bisa dibuka ketika kamu berpikir:

> "Eh, `<tbody>` tuh buat apa ya?"

Lalu belajar.

Lalu coba.

Lalu ngerti.

---

##  Easter Eggs

Ada beberapa detail kecil di project ini yang memang sengaja disembunyikan.

Kalau kamu menemukan sesuatu yang terasa:

> "kok ini kayaknya terlalu personal?"



...

ya.

Memang.

---

##  One last thing

Project ini awalnya tidak dibuat sebagai project besar.

It was kinda a:

> **"yaudah bikin aja sekarang"**

project.

Dan akhirnya...

jadi satu website belajar HTML yang lumayan panjang. 

### yes, i speedrun this buat u.



---

### Thanks for stopping by. 

Belajar pelan-pelan.

Coba sendiri.

Kalau salah, baca lagi.

Kalau masih salah, coba lagi.

**That's literally how we learn.**

⭐ Star kalau project ini membantu
 Fork kalau mau dikembangkan
 Open an issue kalau menemukan sesuatu

made with HTML, CSS, JavaScript & questionable sleep schedules.
