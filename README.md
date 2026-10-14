# Lab4Web - Praktikum 4: CSS Layout

Nama  : [isi nama]
NIM   : [isi NIM]
Kelas : [isi kelas]

## Struktur Folder

```
Lab4Web/
├── lab4_box.html          # Box element, CSS float, clearfix
├── lab4_layout/
│   ├── home.html
│   ├── artikel.html
│   ├── about.html         # Tugas 1
│   ├── kontak.html        # Tugas 2
│   └── style.css
└── screenshots/
```

## 1. Box Element dan CSS Float (lab4_box.html)

Elemen `div` secara default adalah elemen block sehingga tersusun ke bawah.

![Tanpa float](screenshots/01_box_tanpa_float.png)

Dengan `float: left` ketiga div berjajar ke samping.

![Float](screenshots/02_box_float.png)

### Clearfix
`div4` diberi `clear: left` dan `float: none` sehingga turun ke baris baru.

![Clear left](screenshots/03_clearfix_left.png)

Eksperimen nilai `clear`:
- `both`: div4 turun, karena membersihkan float kiri dan kanan.
![Clear both](screenshots/04_clear_both.png)
- `right`: div4 tidak turun karena tidak ada elemen yang float ke kanan.
![Clear right](screenshots/05_clear_right.png)

## 2. Layout Web Sederhana (lab4_layout)

| Langkah | Penjelasan | Screenshot |
|---|---|---|
| Kerangka layout | header, nav, section hero, section wrapper (main + aside), footer | ![](screenshots/06_kerangka_layout.png) |
| Header | reset CSS, font, container 980px, header | ![](screenshots/07_header.png) |
| Navigasi | link inline-block dengan latar biru | ![](screenshots/08_navigasi.png) |
| Hero panel | judul, paragraf, tombol Learn more | ![](screenshots/09_hero_panel.png) |
| Main & sidebar | `float: left` dengan lebar 640px dan 260px, plus widget | ![](screenshots/10_sidebar_widget.png) |
| Footer | `clear: both` dan latar gelap | ![](screenshots/11_footer.png) |
| Content box | tiga box 33,33% dengan gambar bulat | ![](screenshots/12_content_box.png) |
| Artikel | dua artikel, gambar kiri dan kanan | ![](screenshots/13_home_artikel.png) |

## 3. Tugas

### Halaman About (about.html)
Berisi hero, profil, deskripsi, keahlian, dan portfolio.

![About](screenshots/15_halaman_about.png)

### Halaman Kontak (kontak.html)
Berisi form: nama, email, telepon, subjek, message.

![Kontak](screenshots/16_halaman_kontak.png)

### Halaman Artikel (artikel.html)
![Artikel](screenshots/14_halaman_artikel.png)

## Catatan Perbaikan dari Modul
- `box img` diperbaiki menjadi `.box img`.
- Class gambar kanan disamakan menjadi `right-img` (HTML dan CSS).
- CSS `.btn`, `.btn-large`, `.btn-default` ditambahkan.
