# Aplikasi Pertambahan Dua Angka

**Aplikasi Pertambahan Dua Angka** adalah aplikasi Java yang memungkinkan pengguna untuk memasukkan dua angka dan menghitung hasil penjumlahannya. Program ini juga dilengkapi dengan fitur untuk membersihkan input setelah klik tombol "Hapus" dan memberikan konfirmasi keluar aplikasi menggunakan tombol "Keluar". Aplikasi ini juga menerapkan pembatasan input hanya untuk angka.

## Fitur Aplikasi

- Menghitung hasil pertambahan dua angka yang dimasukkan
- Membersihkan input setelah tombol "Hapus" ditekan
- Menutup aplikasi saat tombol "Keluar" ditekan
- Pembatasan input hanya angka menggunakan `KeyAdapter`
- Menampilkan pesan kesalahan jika input bukan angka menggunakan `JOptionPane`
- Menghapus nilai pada kolom input dan mengatur fokus pada kolom input pertama menggunakan `FocusListener`

## Komponen Utama

- **JFrame, JPanel, JLabel, JTextField, JButton** untuk membuat antarmuka pengguna grafis (GUI).
- **KeyAdapter** digunakan untuk membatasi input hanya angka di **JTextField**.
- **JOptionPane** untuk menampilkan pesan error ketika input tidak valid.
- **FocusListener** untuk membersihkan **JTextField** saat mendapatkan fokus.

## Cara Menggunakan

1. Masukkan dua angka yang ingin dijumlahkan pada kolom **Angka 1** dan **Angka 2**.
2. Klik tombol **TAMBAH** untuk menghitung hasil penjumlahan.
3. Klik tombol **HAPUS** untuk menghapus input dan mengatur fokus pada kolom **Angka 1**.
4. Klik tombol **KELUAR** untuk menutup aplikasi.

## Authors

- **Khairul Ilham** - 2210010082 - 5C REG BANJARMASIN

## Screenshots

![App Screenshot](URL_Screenshot)
