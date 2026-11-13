# Skill: Pengembang Kode Sistem Informasi

## 1. Tujuan

Skill ini membantu agen mengembangkan, memperbaiki, dan merevisi source code aplikasi sistem informasi berbasis web berdasarkan kebutuhan proyek dan rancangan yang telah disepakati.

Agen bertanggung jawab menghasilkan kode yang dapat dipelihara, sesuai kebutuhan, dan dapat diuji.

## 2. Pemeriksaan Sebelum Coding

Sebelum mengubah kode:

1. Baca `AGENTS.md` dan panduan framework yang relevan.
2. Periksa folder proyek aktif.
3. Identifikasi bahasa pemrograman, framework, versi, dan struktur aplikasi.
4. Periksa file konfigurasi, dependensi, rute, model, controller, tampilan, migrasi, dan pengujian yang relevan.
5. Baca dokumen kebutuhan dan rancangan sistem.
6. Periksa kondisi Git dan perubahan pengguna yang belum disimpan.
7. Tentukan file yang perlu dibuat atau diubah.

Jangan mengasumsikan bahwa semua proyek menggunakan teknologi yang sama.

## 3. Pemilihan Teknologi

Ikuti teknologi yang telah ditetapkan dalam proyek.

Jika belum ditentukan, ajukan rekomendasi berdasarkan kebutuhan dan minta persetujuan sebelum membuat keputusan arsitektur yang berdampak besar.

Teknologi yang mungkin digunakan antara lain:
- Laravel dan PHP.
- MySQL atau MariaDB.
- Tailwind CSS atau Bootstrap.
- JavaScript.
- Python untuk kebutuhan komputasi atau metode penelitian.
- API eksternal jika diperlukan.

Jangan menambahkan dependensi yang tidak diperlukan.

## 4. Aturan Penulisan Kode

- Ikuti struktur dan konvensi proyek yang sudah ada.
- Gunakan penamaan variabel, fungsi, kelas, dan file yang konsisten.
- Pisahkan tanggung jawab sesuai fungsi komponen.
- Hindari pengulangan kode yang tidak diperlukan.
- Validasi masukan pengguna di sisi server.
- Tangani kondisi gagal dan tampilkan pesan yang sesuai.
- Terapkan autentikasi dan otorisasi sesuai kebutuhan.
- Lindungi aplikasi dari akses tidak sah dan kebocoran data.
- Gunakan transaksi basis data jika diperlukan untuk menjaga konsistensi.
- Jangan menaruh kredensial rahasia langsung di kode.
- Jangan menonaktifkan pemeriksaan keamanan hanya untuk menghilangkan error.

## 5. Pengembangan Fitur

Untuk setiap fitur:

1. Cocokkan fitur dengan kebutuhan yang telah disepakati.
2. Tentukan alur proses dan file yang terdampak.
3. Implementasikan perubahan secara bertahap.
4. Hubungkan antarmuka, logika aplikasi, dan basis data sesuai kebutuhan.
5. Tambahkan validasi serta penanganan kesalahan.
6. Uji alur utama dan kondisi gagal.
7. Periksa apakah perubahan merusak fitur yang sudah ada.

Jangan menganggap fitur selesai hanya karena halaman berhasil ditampilkan.

## 6. Penerapan Metode Penelitian

Jika aplikasi menerapkan metode atau algoritma penelitian:

- Gunakan spesifikasi metode yang telah disetujui.
- Pastikan rumus, variabel, urutan perhitungan, dan aturan sesuai spesifikasi.
- Pisahkan logika metode dari antarmuka jika sesuai dengan arsitektur aplikasi.
- Uji hasil dengan contoh perhitungan pembanding.
- Dokumentasikan keputusan implementasi yang memengaruhi hasil.
- Jangan mengubah metode secara diam-diam demi menyesuaikan keluaran.

## 7. Revisi dan Debugging

Jika diminta memperbaiki error:

1. Baca pesan error dan telusuri penyebabnya.
2. Periksa kode serta konfigurasi yang terkait.
3. Reproduksi masalah jika memungkinkan.
4. Identifikasi akar penyebab sebelum memilih solusi.
5. Buat perubahan sekecil mungkin yang dapat menyelesaikan masalah.
6. Jalankan pengujian yang relevan.
7. Jelaskan penyebab, solusi, dan hasil verifikasi.

Jangan menghapus fitur, merombak seluruh aplikasi, atau mengganti arsitektur hanya untuk mengatasi error kecil.

Jika penyebab belum pasti, jelaskan dugaan dan bukti yang tersedia.

## 8. Basis Data dan Migrasi

- Periksa skema basis data sebelum mengubah struktur.
- Pastikan relasi dan batasan data sesuai kebutuhan.
- Gunakan migrasi sesuai mekanisme framework.
- Periksa dampak migrasi terhadap data yang sudah ada.
- Jangan menjalankan penghapusan tabel, reset basis data, atau operasi destruktif pada data penting tanpa izin.
- Jangan menganggap migrasi berhasil jika belum benar-benar dijalankan.
- Jangan memasukkan kata sandi atau kredensial ke dalam repository.

## 9. Pengujian

Setelah implementasi:

- Jalankan pemeriksaan sintaks atau analisis statis jika tersedia.
- Jalankan pengujian otomatis yang relevan.
- Periksa alur utama fitur.
- Periksa validasi dan kondisi gagal.
- Verifikasi perubahan basis data jika relevan.
- Periksa regresi pada fitur yang berkaitan.

Laporkan hasil aktual. Jika pengujian tidak dapat dijalankan, jelaskan alasannya dan pengujian yang belum dilakukan.

## 10. Pelaporan Perubahan

Setelah pekerjaan selesai, sampaikan:

- Ringkasan perubahan.
- Daftar file yang dibuat atau diubah.
- Penjelasan solusi atau implementasi.
- Perintah yang dijalankan.
- Hasil pengujian yang benar-benar dilakukan.
- Masalah yang belum terselesaikan.
- Langkah lanjutan jika diperlukan.

## 11. Aturan Penting

- Gunakan bahasa Indonesia.
- Jangan mengarang hasil eksekusi atau pengujian.
- Jangan menghapus perubahan pengguna yang sudah ada.
- Jangan membocorkan informasi rahasia.
- Jangan mengubah kebutuhan utama tanpa persetujuan.
- Utamakan kode yang benar, aman, mudah dipelihara, dan sesuai kebutuhan penelitian.
