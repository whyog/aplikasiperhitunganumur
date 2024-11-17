# 🚀 Aplikasi GUI Penghitung Umur

Selamat datang di proyek ini! 🎉 Proyek ini adalah implementasi GUI berbasis Java untuk menghitung umur berdasarkan tanggal lahir, dengan fitur tambahan seperti menampilkan hari ulang tahun berikutnya dan integrasi dengan API untuk menampilkan peristiwa penting pada tanggal lahir.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **Nur Yoga Andika** 👋  
- 📚 **NPM:** 2210010652  
- 🎓 **Jurusan:** Teknologi Informasi  
- 🌟 Saya selalu berusaha belajar hal-hal baru dan berbagi apa yang saya pelajari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini atau topik lainnya! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna:
1. Memilih **tanggal lahir** dari komponen `JDateChooser`.
2. Menekan tombol:
   - **Hitung:** Untuk menampilkan umur dalam format **tahun**, **bulan**, dan **hari**.
   - **Hapus:** Untuk menghapus input dan memulai perhitungan ulang.
   - **Keluar:** Untuk menutup aplikasi dengan mudah.

Aplikasi ini juga menyediakan informasi tambahan seperti:
- **Hari ulang tahun berikutnya.**
- Integrasi dengan **API eksternal** untuk menampilkan peristiwa penting pada tanggal lahir (opsional).

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:
- **JFrame:** Sebagai jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JDateChooser:** Mempermudah pengguna memilih tanggal.
- **JButton:** Untuk melakukan tindakan seperti hitung, hapus, dan keluar.
- **JTextField:** Menampilkan hasil penghitungan.

---

## 🔍 Logika Program

1. **Manipulasi tanggal menggunakan LocalDate:**
   - Tanggal lahir diubah ke format `LocalDate` untuk mempermudah perhitungan.
2. **Perhitungan selisih waktu:**
   - Umur dihitung berdasarkan perbedaan antara tanggal lahir dan tanggal saat ini.
3. **Informasi tambahan:**
   - Menentukan hari ulang tahun berikutnya.
   - Mengintegrasikan API eksternal untuk menampilkan peristiwa penting pada tanggal lahir (opsional).

---

## 🎯 Events yang Diimplementasikan

- **ActionListener:**  
  - Untuk tombol **Hitung** yang memproses penghitungan umur.  
  - Untuk tombol **Hapus** yang menghapus semua input pengguna.
  - Untuk tombol **Keluar** yang menutup aplikasi.

- **PropertyChangeListener:**  
  - Digunakan pada `JDateChooser` untuk mendeteksi perubahan tanggal lahir secara langsung.

---

## ✨ Variasi

1. Memberikan informasi tambahan:
   - Hari ulang tahun berikutnya.
   - Jumlah hari menuju ulang tahun.
2. Integrasi dengan API eksternal untuk menampilkan **peristiwa penting** pada tanggal lahir.
3. Validasi input:
   - Menampilkan pesan kesalahan jika pengguna belum memilih tanggal atau memasukkan input yang tidak valid.

---

## 🔧 Cara Menggunakan Program

1. Pilih **tanggal lahir** menggunakan komponen `JDateChooser`.
2. Tekan tombol:
   - **Hitung:** Lihat hasil umur Anda dalam format tahun, bulan, dan hari.
   - **Hapus:** Bersihkan semua input dan mulai dari awal.
   - **Keluar:** Tutup aplikasi dengan mudah.
3. Informasi tambahan tentang hari ulang tahun berikutnya akan ditampilkan di bidang yang telah disediakan.

---


