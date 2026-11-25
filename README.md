# Format Teks Transkrip

Aplikasi web sederhana, cepat, dan responsif untuk merapikan teks transkrip yang memiliki penanda waktu (*timestamp*) secara otomatis dan *real-time*.

Alat ini mengubah format *timestamp* bawaan seperti `(0:00)` menjadi `[0:00]`, memisahkan setiap segmen waktu ke baris baru, menyambung kalimat yang terpotong baris, serta menyediakan opsi penomoran otomatis dan penghitung statistik kata.

---

## ✨ Fitur Utama

- **Konversi Timestamp Otomatis**: Mengubah format `(0:00)` menjadi `[0:00]` dan memecah setiap *timestamp* ke baris tersendiri secara *real-time*.
- **Perapian Kalimat Terpotong**: Menggabungkan baris kalimat yang terpisah secara tidak sengaja dalam satu segmen *timestamp*.
- **Penomoran Baris Opsional**: Menambahkan nomor urut otomatis (`1. [0:00] ...`, `2. [0:06] ...`) di setiap baris hasil format.
- **Spasi Antar Segmen**: Opsi untuk menambahkan baris kosong di antara segmen agar transkrip lebih mudah dibaca.
- **Statistik Teks Real-time**: Menghitung jumlah kata, karakter, baris, dan *timestamp* baik pada panel input maupun output.
- **Dark Mode & Responsif**: Mendukung tema gelap/terang (menyimpan preferensi di `localStorage`) serta tampilan yang nyaman di desktop maupun perangkat mobile.
- **Ekspor & Aksi Cepat**: Dilengkapi tombol **Contoh Teks** (bahasa Indonesia), **Tempel**, **Hapus**, **Salin Hasil**, dan **Unduh .txt**.
- **100% Client-Side**: Seluruh pemrosesan berjalan langsung di browser tanpa mengirim data ke server mana pun.

---

## 📋 Contoh Penggunaan

### Teks Input
```text
(0:00) Halo teman-teman, selamat datang kembali di podcast Teknologi Santai. (0:06) Hari ini kita akan membahas bagaimana kecerdasan buatan membantu pekerjaan sehari-hari. (0:14) Banyak orang mengira teknologi ini rumit,
padahal penggunaannya sangat sederhana.
```

### Hasil Format
```text
[0:00] Halo teman-teman, selamat datang kembali di podcast Teknologi Santai.
[0:06] Hari ini kita akan membahas bagaimana kecerdasan buatan membantu pekerjaan sehari-hari.
[0:14] Banyak orang mengira teknologi ini rumit, padahal penggunaannya sangat sederhana.
```

*(Jika opsi **Beri penomoran per baris** diaktifkan)*:
```text
1. [0:00] Halo teman-teman, selamat datang kembali di podcast Teknologi Santai.
2. [0:06] Hari ini kita akan membahas bagaimana kecerdasan buatan membantu pekerjaan sehari-hari.
3. [0:14] Banyak orang mengira teknologi ini rumit, padahal penggunaannya sangat sederhana.
```

---

## 🛠️ Teknologi yang Digunakan

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript (ES6+)**
- **Google Fonts (`Inter`)**

---
