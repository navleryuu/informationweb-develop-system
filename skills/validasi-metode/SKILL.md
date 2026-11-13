# Skill: Validasi Metode Penelitian

## 1. Tujuan

Skill ini membantu agen memahami, menerapkan, dan memvalidasi metode penelitian yang digunakan dalam sistem informasi.

Metode dapat berupa algoritma klasifikasi, sistem pendukung keputusan, peramalan, optimasi, pengelompokan, sistem berbasis aturan, atau metode lain yang ditentukan dalam proposal.

## 2. Identifikasi Metode

Sebelum melakukan implementasi:

1. Baca bagian proposal yang menjelaskan metode penelitian.
2. Identifikasi tujuan dan fungsi metode.
3. Catat variabel, kriteria, parameter, rumus, aturan, dan ambang batas.
4. Identifikasi format data masukan dan keluaran yang diharapkan.
5. Tentukan tahapan perhitungan sesuai sumber yang dapat diverifikasi.
6. Catat informasi yang belum tersedia atau masih ambigu.

Jangan memilih metode pengganti tanpa persetujuan pengguna.

## 3. Penyusunan Spesifikasi

Buat spesifikasi metode yang berisi:

- Nama dan tujuan metode.
- Sumber teori atau referensi.
- Variabel dan definisinya.
- Data masukan.
- Tahapan algoritma.
- Rumus dan aturan perhitungan.
- Kondisi khusus dan penanganan data kosong.
- Format hasil keluaran.
- Contoh kasus untuk pengujian.

Setiap rumus dan aturan penting harus memiliki dasar yang jelas. Jika sumber belum tersedia, tandai untuk diverifikasi.

## 4. Perhitungan Manual

Sebelum menerapkan metode ke kode:

1. Siapkan contoh data yang mewakili kasus penggunaan.
2. Hitung hasil setiap tahapan secara manual atau melalui perhitungan independen.
3. Catat nilai antara dan hasil akhirnya.
4. Periksa pembulatan, satuan, batas nilai, dan kondisi khusus.
5. Gunakan hasil tersebut sebagai pembanding implementasi program.

Untuk metode yang memerlukan data nyata, gunakan data yang diizinkan dan tersedia. Jangan mengarang hasil penelitian atau mengubah data agar sesuai dengan hasil yang diinginkan.

## 5. Implementasi dalam Sistem

Saat menerapkan metode ke kode:

- Pisahkan logika metode dari tampilan jika sesuai dengan arsitektur aplikasi.
- Gunakan nama variabel yang jelas dan konsisten.
- Validasi masukan sebelum perhitungan.
- Tangani data kosong, nilai di luar batas, dan kondisi yang tidak valid.
- Pastikan setiap aturan yang diterapkan dapat ditelusuri ke spesifikasi.
- Hindari perubahan rumus atau aturan secara diam-diam.
- Dokumentasikan setiap penyederhanaan atau keputusan implementasi.

## 6. Pengujian dan Pembandingan

Uji implementasi menggunakan:

- Kasus normal.
- Kasus batas.
- Data kosong atau tidak valid.
- Kasus khusus yang relevan dengan metode.
- Contoh yang sudah dihitung secara manual.

Bandingkan keluaran program dengan hasil pembanding.

Jika terdapat perbedaan:

1. Periksa kembali rumus dan sumber metode.
2. Periksa data masukan dan transformasinya.
3. Periksa urutan tahapan perhitungan.
4. Periksa presisi angka dan pembulatan.
5. Periksa aturan kondisi dan batas klasifikasi.
6. Perbaiki penyebab perbedaan dan jalankan pengujian ulang.

Jangan menyatakan metode tervalidasi jika bukti pengujian belum cukup.

## 7. Format Laporan

Simpan spesifikasi dan hasil validasi di folder proyek aktif, bukan di repository framework.

Gunakan format laporan berikut:

# Laporan Validasi Metode

## A. Identitas Metode
- Nama metode:
- Tujuan:
- Sumber referensi:
- Versi spesifikasi:

## B. Komponen Metode
- Variabel:
- Parameter:
- Rumus atau aturan:
- Data masukan:
- Keluaran:

## C. Contoh Perhitungan
- Data contoh:
- Tahapan perhitungan:
- Hasil manual:
- Catatan asumsi:

## D. Hasil Pengujian
- Kasus uji:
- Hasil yang diharapkan:
- Hasil aktual:
- Status: LULUS atau GAGAL.

## E. Temuan
Catat perbedaan, keterbatasan, risiko, dan informasi yang perlu dikonfirmasi.

## F. Kesimpulan
Jelaskan apakah implementasi sudah sesuai dengan spesifikasi dan bukti yang tersedia.

## 8. Aturan Penting

- Gunakan bahasa Indonesia.
- Jangan mengarang rumus, referensi, atau hasil pengujian.
- Jangan menganggap semua metode memiliki tahapan yang sama.
- Ikuti metode yang ditentukan dalam proposal yang telah disetujui.
- Pisahkan fakta, asumsi, dan rekomendasi.
- Jangan mengubah kode sumber ketika pengguna hanya meminta analisis metode.
- Minta persetujuan sebelum mengubah metode penelitian atau spesifikasi yang telah disepakati.
