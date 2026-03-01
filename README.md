# minpro-pwb1# Website Portfolio (HTML, CSS, Bootstrap 5, Vue JS)

## Deskripsi Project
Project ini merupakan website portofolio statis berbasis website yang dibuat untuk memenuhi tugas pengembangan web. Website ini dirancang untuk menampilkan informasi pribadi, kemampuan (skills), dan sertifikat dalam tampilan yang rapi, modern, dan responsif.

Website dibangun menggunakan **HTML**, **CSS**, **Bootstrap 5**, dan **Vue JS**. Meskipun bersifat statis, penggunaan Vue JS diterapkan untuk meningkatkan interaktivitas tampilan melalui data binding.

---

---

## Tampilan dan Penjelasan Setiap Section

### 1. Navbar
**Tampilan:**
- Navbar berada di bagian atas halaman.
- Menyediakan navigasi ke section Home, About Me, dan Certificates.
- Bersifat responsif dan otomatis collapse pada ukuran layar kecil.

**Penjelasan Code:**
- Menggunakan komponen Navbar dari Bootstrap 5.
- Menu navbar dirender secara dinamis menggunakan Vue JS dengan perulangan `v-for`.
- Navigasi menggunakan anchor link ke setiap section.

---

### 2. Home (Hero Section)
**Tampilan:**
- Menampilkan background gambar fullscreen.
- Menggunakan overlay gelap untuk meningkatkan keterbacaan teks.
- Menampilkan nama dan deskripsi singkat.

**Penjelasan Code:**
- Background gambar diatur menggunakan CSS dengan `height: 100vh`.
- Overlay menggunakan warna semi-transparan.
- Teks nama dan tagline ditampilkan menggunakan Vue interpolation (`{{ }}`).

---

### 3. About Me
**Tampilan:**
- Berisi deskripsi diri.
- Menampilkan daftar pengalaman.
- Menampilkan skill dalam bentuk progress bar.

**Penjelasan Code:**
- Layout dibuat menggunakan Grid System Bootstrap (`row` dan `col-md-*`).
- Progress bar menggunakan komponen `progress` dari Bootstrap 5.
- Data skill dikelola menggunakan Vue JS dan ditampilkan dengan `v-for`.
- Warna dan persentase skill dapat diatur secara dinamis.

---

### 4. Certificates
**Tampilan:**
- Sertifikat ditampilkan dalam bentuk card.
- Menggunakan layout grid yang rapi dan responsif.
- Setiap card berisi gambar sertifikat dan deskripsi singkat.

**Penjelasan Code:**
- Menggunakan komponen Card dari Bootstrap 5.
- Grid layout menggunakan `row` dan `col-md-4`.
- Data sertifikat bersifat statis dan dikelola melalui Vue JS.

---

### 5. Footer
**Tampilan:**
- Footer sederhana di bagian bawah halaman.
- Menampilkan informasi copyright.

**Penjelasan Code:**
- Menggunakan utility class dari Bootstrap 5.
- Teks footer terhubung dengan data Vue JS.

---

## Penggunaan Vue JS
Vue JS digunakan pada project ini untuk:
- Data binding menggunakan interpolation (`{{ }}`).
- Pengelolaan data statis menggunakan fungsi `data()`.
- Perulangan data menggunakan `v-for`.
- Menghubungkan Vue ke elemen HTML menggunakan `.mount('#app')`.

---

## Teknologi yang Digunakan
- **HTML5** – Struktur dasar website.
- **CSS3** – Styling dan pengaturan tampilan.
- **Bootstrap 5** – Layouting, Navbar, Grid System, Card, Button, Progress Bar, dan Responsive Design.
- **Vue JS (CDN)** – Interaktivitas tampilan dan data binding.

---
