# Pembaruan melalui Google Sheets

1. Buka Google Sheets yang telah diberikan. Pastikan nama tab data adalah Rate dan header FASKES tetap tersedia.
2. Klik Bagikan > Akses umum > Siapa saja yang memiliki link > Pelihat > Selesai. Hak edit hanya diberikan kepada petugas BPJS. Data pada tabel ini akan dapat dibaca publik.
3. Ekstrak ZIP ini. Unggah index.html ke folder utama repositori GitHub dashboard, menggantikan index.html lama, lalu Commit changes. Jangan unggah ZIP atau Excel ke repositori.
4. Tunggu publikasi GitHub Pages selesai. Buka tautan dashboard dan klik Muat data Google Sheets. Pastikan status menyatakan berhasil dibaca, bukan data sebelumnya.
5. Cocokkan beberapa fasilitas dengan Google Sheets. Uji satu perubahan angka yang sah lalu muat ulang; periksa di browser lain.
6. Minggu berikutnya, edit tabel Google Sheets yang sama. Pertahankan nama tab Rate. Kolom Capaian Jlh Rujukan sd 5 Oktober dapat diubah tanggalnya sepanjang tetap bulan Oktober. Dashboard mengambil data saat dibuka atau tombol muat ditekan. Pembaruan Google dapat mengalami jeda.

## Batasan yang perlu diketahui
- Akses tanpa login telah berhasil diuji pada 10 Oktober 2026: 36 fasilitas terbaca. Format angka Google Sheets menggunakan lokal Indonesia (titik ribuan, koma desimal). Pengujian tampilan pada situs GitHub dilakukan setelah file dipasang.
- Fitur unggah lokal tetap pratinjau sementara, bukan pembaruan publik. Sumber publik adalah Google Sheets.
- Analisis utama masih September dan pemantauan berjalan Oktober. Pergantian bulan memerlukan penyesuaian kode.
- Bila koneksi gagal, status memperingatkan bahwa data sebelumnya sedang ditampilkan.
- Angka dan satuan target mengikuti workbook lama; perubahan definisi indikator tidak dilakukan.
