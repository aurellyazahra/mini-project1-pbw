# MINI PROJECT 1 PBW
NAMA: ZAHRA AURELLYA HERDIANSYAH

NIM: 2409116062

KELAS: SI B 2024

# Personal Portfolio Website

Website ini merupakan project portfolio pribadi yang dibuat menggunakan HTML, CSS, dan Bootstrap 5. Tujuan dari project ini adalah untuk menampilkan informasi tentang diri saya, latar belakang pendidikan, keterampilan, serta sertifikat yang telah saya peroleh dalam bentuk website yang modern, responsive, dan user-friendly.
Website ini dirancang dengan tampilan yang bersih, warna yang konsisten, serta tambahan animasi agar terlihat lebih menarik.

# Tampilan Setiap Section / Fitur

## Navbar
<img width="1879" height="77" alt="image" src="https://github.com/user-attachments/assets/1a30de93-51fa-40b7-877a-2243f4241fab" />

Navbar berisi:
- Nama Website

Menu navigasi:
- Home
- About Me
- Certificates

Navbar selalu berada di bagian atas dan memiliki tampilan yang bersih serta minimalis.

## Hero Section
Hero section adalah bagian pertama yang muncul saat website dibuka.

<img width="1878" height="880" alt="image" src="https://github.com/user-attachments/assets/e12f34cd-9ccb-433e-a7cf-6903abe19af2" />

### Tampilan:
- Nama lengkap
- Deskripsi singkat tentang diri saya
- Subtitle dengan warna custom
- Layout yang berada di tengah halaman

### Fitur:
- Menggunakan text rata kanan kiri (justify) pada deskripsi
- Warna subtitle disesuaikan dengan tema website
- Responsive pada berbagai ukuran layar
- Spacing yang proporsional agar terlihat rapi

Hero section dibuat semenarik mungkin karena merupakan bagian pertama yang dilihat oleh pengunjung.

## About me section
Section ini berisi informasi lebih detail tentang diri saya.

<img width="1882" height="882" alt="image" src="https://github.com/user-attachments/assets/ab8742ef-f30b-45bb-b138-73005352fe9b" />

### Tampilan:
- Profile singkat
- Education (riwayat pendidikan)
- Skills (kemampuan yang dimiliki)
- Informasi ditampilkan menggunakan card agar lebih terstruktur dan mudah dibaca.

### Fitur:
- Menggunakan Bootstrap Grid System (row, col) agar responsif
- Setiap card memiliki jarak yang rapi
- Menggunakan animasi fade dan slide saat di-scroll
- Layout berubah otomatis di tampilan mobile

Animasi ditambahkan agar website tidak terlihat statis dan lebih interaktif.

## Certificate section
Section ini menampilkan daftar sertifikat yang telah saya peroleh.

<img width="1883" height="896" alt="image" src="https://github.com/user-attachments/assets/685fe450-c52f-4740-a15e-5d56b31ff6c7" />

### Tampilan:
- Gambar sertifikat
- Judul sertifikat
- Ditampilkan dalam bentuk card

### Fitur:
- Menggunakan Bootstrap Card Component
- Menggunakan CSS linear-gradient() untuk background card
- Gradient dibuat dari atas ke bawah (top to bottom)
- Hover effect (card akan sedikit naik dan memiliki shadow saat disentuh)

### Responsive grid:
- 1 kolom pada mobile
- 3 kolom pada desktop

Section ini bertujuan untuk menunjukkan pencapaian dan pengalaman yang saya miliki.

## Footer section
Footer merupakan bagian paling bawah dari website.

<img width="494" height="38" alt="image" src="https://github.com/user-attachments/assets/90fdedff-d03f-4b34-9a26-5babb7fdc289" />

### Tampilan:
- Copyright
- Tampilan minimalis

### Fitur:
- Tinggi footer diperkecil agar terlihat compact
- Warna kontras dengan isi website
- Responsive di semua ukuran layar

Footer dibuat sederhana agar tidak mengganggu fokus utama website.


# Penjelasan Code Setiap Section

## Hero section
Struktur menggunakan:
`<section>`

Styling menggunakan CSS untuk:
- Mengatur warna subtitle
- Mengatur font-weight
- Mengatur text-align: justify
- Mengatur margin dan spacing

Bootstrap digunakan untuk membantu positioning dan alignment.

## About Me Section
Menggunakan Bootstrap Grid:
- container
- row
- col-md-4

Animasi dibuat dengan:
- opacity
- transform
- transition
- JavaScript untuk mendeteksi scroll

Class .visible ditambahkan saat elemen masuk ke viewport sehingga animasi berjalan dengan smooth.

## Certificates Section

Menggunakan:
- Bootstrap .card
- .card-body
- .card-img-top

Gradient dibuat dengan:
`background: linear-gradient(to bottom, color1, color2);`

Hover effect dibuat menggunakan:
`transform: translateY(-5px);
box-shadow: ...`

Ini membuat tampilan lebih modern dan interaktif.

## Footer
Menggunakan:
`<footer>`

CSS digunakan untuk:
- Mengatur padding
- Mengatur font-size
- Mengatur warna background dan teks

# Desain dan Styling
Website ini menggunakan kombinasi warna yang soft dan konsisten agar terlihat estetik.
Beberapa elemen desain yang digunakan:
- Border radius pada card
- Shadow halus
- Gradient background
- Hover animation
- Spacing yang konsisten

Semua styling dibuat menggunakan CSS custom dan Bootstrap utility class.

# Teknologi yang Digunakan
Website ini dibuat menggunakan:

### HTML5
Digunakan untuk membuat struktur halaman website.

### CSS3
Digunakan untuk styling, layout, animasi, dan gradient.

### Bootstrap 5
Digunakan untuk grid system, card component, dan responsive layout.

