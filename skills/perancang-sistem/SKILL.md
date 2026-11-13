# Skill: Perancang Sistem Informasi

## 1. Tujuan

Skill ini bertugas menerjemahkan hasil analisis proposal dan kebutuhan pengguna menjadi rancangan sistem informasi yang terstruktur, konsisten, dan siap dijadikan dasar pengembangan aplikasi.

Rancangan harus sesuai dengan masalah penelitian, tujuan sistem, batasan penelitian, dan metode yang digunakan.

## 2. Prasyarat

Sebelum merancang sistem:

1. Baca `AGENTS.md` pada framework.
2. Periksa hasil analisis proposal proyek aktif.
3. Pahami kebutuhan pengguna dan ruang lingkup penelitian.
4. Baca kode sumber yang sudah ada jika proyek merupakan pengembangan sistem lama.
5. Identifikasi informasi yang belum tersedia dan minta klarifikasi jika informasi tersebut memengaruhi rancangan utama.

Jangan membuat rancangan berdasarkan asumsi yang tidak dijelaskan.

## 3. Analisis Kebutuhan

Kelompokkan kebutuhan menjadi:

### Kebutuhan fungsional
Fungsi yang harus dapat dilakukan sistem, seperti:
- Login dan autentikasi.
- Pengelolaan data.
- Proses utama sesuai tujuan penelitian.
- Perhitungan atau penerapan metode.
- Penyajian hasil.
- Laporan dan ekspor data jika diperlukan.

### Kebutuhan nonfungsional
Persyaratan kualitas sistem, seperti:
- Keamanan.
- Kemudahan penggunaan.
- Kinerja.
- Keandalan.
- Kemudahan pemeliharaan.

Jangan menambahkan fitur hanya karena umum ditemukan pada aplikasi lain. Setiap fitur harus memiliki alasan yang jelas.

## 4. Identifikasi Pengguna

Untuk setiap peran pengguna, tentukan:
- Nama peran.
- Tanggung jawab.
- Hak akses.
- Fitur yang dapat digunakan.
- Batasan akses terhadap data.

Gunakan jumlah dan jenis peran yang sesuai dengan proses bisnis nyata.

## 5. Perancangan Alur Sistem

Jelaskan alur dari awal sampai akhir:

1. Pengguna memulai proses.
2. Sistem memvalidasi masukan.
3. Sistem mengambil atau menyimpan data jika diperlukan.
4. Sistem menjalankan proses bisnis atau metode penelitian.
5. Sistem menghasilkan keluaran.
6. Pengguna melihat hasil dan melakukan tindakan lanjutan.

Bedakan tindakan pengguna, proses sistem, dan aktivitas basis data.

Jika diminta membuat flowchart, gunakan simbol flowchart yang tepat, termasuk terminator, proses, input/output, keputusan, serta panah alur.

Jika sistem melibatkan beberapa pihak, gunakan swimlane untuk membedakan aktivitas masing-masing pihak.

## 6. Perancangan Basis Data

Identifikasi:
- Entitas dan tabel.
- Atribut setiap tabel.
- Primary key dan foreign key.
- Relasi antartabel.
- Kardinalitas relasi.
- Aturan integritas data.
- Kebutuhan indeks dan validasi.

Pastikan rancangan basis data mendukung seluruh kebutuhan sistem dan penerapan metode penelitian.

Hindari menyimpan data yang sama berulang kali tanpa alasan yang jelas.

Untuk proyek yang sudah memiliki basis data, periksa skema aktual sebelum mengusulkan perubahan.

## 7. Perancangan Antarmuka

Tentukan:
- Daftar halaman.
- Tujuan setiap halaman.
- Komponen utama.
- Formulir dan validasi masukan.
- Tabel, pencarian, filter, dan navigasi jika diperlukan.
- Kondisi kosong, berhasil, dan gagal.
- Perbedaan tampilan sesuai hak akses pengguna.

Utamakan antarmuka yang konsisten, mudah dipahami, responsif, dan sesuai kebutuhan pengguna.

Jangan menganggap rancangan visual sebagai pengganti validasi kebutuhan fungsional.

## 8. Rancangan Penerapan Metode

Jika sistem menggunakan algoritma atau metode penelitian:

1. Identifikasi titik proses ketika metode dijalankan.
2. Tentukan data masukan yang diperlukan.
3. Jelaskan alur pemrosesan dan keluaran.
4. Pastikan setiap variabel tersedia dalam rancangan data.
5. Gunakan spesifikasi metode dari skill validasi metode.
6. Tentukan cara menguji hasil penerapan metode.

Jangan mengubah algoritma atau rumus yang telah disetujui tanpa izin pengguna.

## 9. Dokumen Hasil Rancangan

Simpan hasil rancangan pada folder proyek aktif, bukan di repository framework.

Jika sesuai kebutuhan, buat dokumen berikut:

- `analisis/kebutuhan-sistem.md`
- `analisis/daftar-pengguna.md`
- `analisis/alur-sistem.md`
- `analisis/rancangan-basis-data.md`
- `analisis/rancangan-antarmuka.md`
- `analisis/rancangan-metode.md`

Dokumen yang tidak relevan dengan proyek tidak perlu dibuat.

## 10. Pemeriksaan Konsistensi

Sebelum menyelesaikan rancangan, pastikan:
- Semua rumusan masalah memiliki dukungan solusi yang jelas.
- Fitur sesuai dengan ruang lingkup penelitian.
- Setiap fitur memiliki peran pengguna yang sesuai.
- Alur sistem konsisten dengan kebutuhan.
- Struktur basis data mendukung alur sistem.
- Data yang dibutuhkan metode tersedia.
- Rancangan dapat diuji.
- Tidak ada perubahan besar yang bertentangan dengan proposal.

## 11. Aturan Penting

- Gunakan bahasa Indonesia.
- Bedakan kebutuhan wajib dari rekomendasi tambahan.
- Jangan mengarang kebutuhan yang tidak didukung informasi proyek.
- Jelaskan asumsi dan risiko rancangan.
- Jangan mulai mengubah kode sumber hanya karena rancangan sudah dibuat.
- Sampaikan rancangan kepada pengguna dan tunggu persetujuan sebelum implementasi besar.
- Jika mengembangkan sistem lama, pertahankan bagian yang sudah berjalan kecuali ada alasan dan persetujuan untuk mengubahnya.
