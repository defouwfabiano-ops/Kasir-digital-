# Kasir-digital-
# Kasir Wamena
Aplikasi Kasir dan Agen BRILink untuk kios di Wamena. Aplikasi ini dirancang untuk mencatat transaksi penjualan barang, pengelolaan stok, dan aktivitas layanan keuangan BRILink.

## Rencana Pengembangan (Roadmap) v2.0
Daftar fitur yang akan ditambahkan untuk memperkuat sistem Kasir & Agen BRILink:

* **Keamanan & Data**: 
    * Menambahkan sistem PIN/Password untuk login aplikasi.
    * Integrasi *Cloud Backup* ke Google Drive untuk mengamankan data transaksi agar tidak hilang jika HP rusak.
* **Efisiensi Transaksi**: 
    * Fitur "Keranjang Belanja" untuk memproses banyak barang dalam satu kali transaksi pembayaran.
    * Integrasi koneksi *Bluetooth Thermal Printer* untuk mencetak struk belanja pelanggan.
* **Modul Agen BRILink**: 
    * Penambahan tabel `transaksi_brilink` untuk mencatat *fee* admin (Tarik Tunai, Transfer, & Pembayaran) secara terpisah dari stok barang.
    * Logika kalkulasi otomatis untuk total pendapatan bersih (Keuntungan Toko + *Fee* BRILink).
