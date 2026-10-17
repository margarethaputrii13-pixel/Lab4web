# Lab4web
# Laporan Praktikum 4 - Layout Sederhana (Lab4Web)

Nama: margaretha futri irwan  
NIM: 312510337
Kelas: I253C 
Mata Kuliah: Pemrograman Web  

---

## 1. Deskripsi Praktikum
Praktikum ini bertujuan untuk mengimplementasikan tata letak web (layout) sederhana menggunakan HTML5 dan CSS3. Pokok bahasan meliputi:
- Penggunaan elemen kontainer (`#container`, `#wrapper`, `#main`, `#sidebar`).
- Pengaturan kolom menggunakan `float` dan `clear`.
- Penataan elemen halaman utama (Hero section, Tiga Box Lingkaran, Featurette Article).
- Pembuatan layout halaman About (Single Layout) dan Contact (Form Input).

---

## 2. Langkah-Langkah Pengerjaan

### Langkah 1: Struktur Dasar HTML dan CSS Reset
Membuat struktur dasar HTML pada `home.html` dan menerapkan CSS Reset pada `style.css` agar tampilan antar-browser konsisten.

### Langkah 2: Menambahkan Navigasi dan Hero Section
Membuat bagian header, menu navigasi, dan banner jumbotron (*hero section*) untuk menampilkan teks judul utama dan deskripsi singkat.

### Langkah 3: Membuat Konten Tiga Kolom (Box Element)
Menyusun 3 kotak konten berjejer secara horizontal menggunakan `float: left` dan pengaturan `width: 33.33%`. Menambahkan styling `border-radius: 50%` pada gambar agar berbentuk lingkaran.

### Langkah 4: Menambahkan Article / Featurette
Menambahkan section artikel di bawah box lingkaran dengan pembatas garis (`<hr class="divider">`). Mengatur gambar artikel pertama di kiri (`float: left`) dan artikel kedua di kanan (`float: right`).

### Langkah 5: Membuat Halaman About dan Contact
- `about.html`: Halaman dengan *single layout* berisi informasi biografi dan portofolio.
- `contact.html`: Halaman berisi formulir isian (Nama, Email, dan Pesan).

---

## 3. Hasil Tampilan (Screenshot)

<img width="1013" height="519" alt="Tangkapan Layar 2026-10-17 pukul 22 49 49" src="https://github.com/user-attachments/assets/d4be5b0e-adcf-4b78-8502-48bdcdd25ad9" />
<img width="849" height="469" alt="Tangkapan Layar 2026-10-17 pukul 22 44 45" src="https://github.com/user-attachments/assets/1ecae0df-eac8-4d74-8d5b-8e0eb1bbd53f" />



### Tampilan Halaman Utama (Home)
<img width="1048" height="598" alt="Tangkapan Layar 2026-10-17 pukul 22 57 47" src="https://github.com/user-attachments/assets/7fee3603-21ce-4827-8baf-c1cbc8e093dc" />


### Tampilan Artikel / Featurette
<img width="1025" height="803" alt="Tangkapan Layar 2026-10-18 pukul 00 10 10" src="https://github.com/user-attachments/assets/330e0bbd-90db-424c-ac39-dc2c0fcf48ad" />

### Tampilan Halaman About
<img width="1451" height="831" alt="Tangkapan Layar 2026-10-18 pukul 00 27 27" src="https://github.com/user-attachments/assets/fd91680d-cef8-43b4-a0b0-d2914e0cc00d" />


### Tampilan Halaman Contact
<img width="1456" height="831" alt="Tangkapan Layar 2026-10-18 pukul 00 27 43" src="https://github.com/user-attachments/assets/10f660af-e08b-4196-9914-33ecafd49fac" />

---

## 4. Kesimpulan
Melalui praktikum ini, pembuatan layout web menggunakan CSS Float dan Positioning berhasil diterapkan. Penggunaan struktur pembungkus (`#container`) dengan `margin: 0 auto` terbukti efektif untuk menjaga posisi tampilan web tetap berada di tengah layar secara teratur.
