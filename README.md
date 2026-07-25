# Catatan perjalanan darat di Indonesia

Halaman statis berisi catatan lapangan perjalanan darat di Indonesia. Dibuat sebagai halaman tunggal tanpa framework, tanpa skrip pihak ketiga, dan tanpa pelacak, supaya ringan dibuka dari koneksi seluler di jalan.

Halaman live: <https://mcsyauqi.github.io/catatan-perjalanan-darat/>

## Isi

Tulisan di repositori ini membahas cara memilih moda perjalanan antar kota di Indonesia dengan tiga ukuran yang lebih dekat ke pengalaman nyata daripada harga tiket:

1. **Waktu pintu ke pintu**, bukan durasi resmi stasiun ke stasiun. Untuk pesawat, perjalanan menuju dan dari bandara sering lebih panjang daripada waktu terbangnya.
2. **Biaya sebenarnya**, yang mencakup perjalanan ke titik keberangkatan, bagasi, waktu tunggu, dan kemungkinan malam penginapan tambahan.
3. **Keandalan jadwal**, yaitu seberapa mahal konsekuensinya kalau meleset dan seberapa mudah pulih.

Selain itu dibahas pengaruh barang bawaan, jumlah orang, waktu pemesanan, dan kondisi kapan pesawat memang pilihan yang jelas.

## Kenapa dibuat

Catatan ini bagian dari [Jalan Jalan Tiap Hari](https://jalanjalantiaphari.com/), majalah perjalanan digital Indonesia yang mengumpulkan panduan destinasi, penginapan, dan kuliner. Sebagian catatan lapangan lebih cocok berdiri sendiri sebagai halaman ringan yang bisa dibuka cepat, jadi disimpan terpisah di sini.

## Struktur

```
index.html    halaman tunggal, HTML dan CSS inline, tanpa dependensi
README.md     berkas ini
```

Tidak ada langkah build. Halaman dilayani langsung oleh GitHub Pages dari branch `main`.

## Prinsip teknis

- Satu berkas HTML, tanpa framework dan tanpa bundler
- CSS inline seperlunya, memakai `system-ui` supaya tidak perlu mengunduh font
- Tanpa JavaScript, tanpa analitik, tanpa cookie
- Lebar konten dibatasi 44rem supaya nyaman dibaca di layar ponsel maupun desktop
- Ukuran halaman di bawah 15 KB

## Lisensi

Isi tulisan boleh dikutip dengan mencantumkan sumber. Kode HTML dan CSS-nya bebas dipakai ulang.
