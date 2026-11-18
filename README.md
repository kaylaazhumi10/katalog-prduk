# Katalog Produk UPI Store

Aplikasi desktop sederhana untuk mengelola katalog produk (Create, Read, Update, Delete) dengan antarmuka yang bersih dan mudah digunakan[cite: 1].

## Fitur Utama

1. **Tambah Produk (Create)**
   * Pengguna dapat memasukkan **Nama produk**, **Harga (Rp)**, dan memilih **Foto contoh** melalui dropdown yang tersedia (`roti.png`, dll.)[cite: 1].
   * Menekan tombol **Simpan** akan menyimpan data produk ke dalam sistem dan menampilkan notifikasi *"Produk berhasil disimpan."* serta memperbarui total jumlah produk[cite: 1].

2. **Lihat Katalog (Read)**
   * Setiap produk yang tersimpan ditampilkan dalam bentuk kartu (*card*) katalog yang memuat gambar produk, nama produk, harga, serta nomor **ID** unik[cite: 1].

3. **Edit Produk (Update)**
   * Setiap kartu produk dilengkapi dengan tombol **Edit**[cite: 1].
   * **Cara Kerja:** Saat tombol **Edit** diklik, data produk terkait (Nama produk, Harga, dan Foto contoh) akan dimuat kembali ke dalam form input di bagian atas[cite: 1]. Pengguna dapat mengubah informasi yang diinginkan lalu menekan tombol **Simpan** (atau *Update*) untuk memperbarui data produk berdasarkan ID tersebut tanpa membuat data duplikat[cite: 1].

4. **Hapus Produk (Delete)**
   * Setiap kartu produk dilengkapi dengan tombol **Hapus**[cite: 1].
   * **Cara Kerja:** Saat tombol **Hapus** diklik, sistem akan menghapus data produk tersebut dari daftar penyimpanan berdasarkan ID produk[cite: 1]. Kartu produk akan hilang dari tampilan katalog dan indikator **Jumlah produk** di bagian atas akan otomatis berkurang[cite: 1].



1. **Clone repository ini:**
   ```bash
   git clone [https://github.com/username-anda/nama-repository.git](https://github.com/username-anda/nama-repository.git)
   cd nama-repository
