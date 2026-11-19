# Tugas-jawaban
## Perbedaan Form Handling dan Validasi Form pada PHP

1. Form Handling (Penanganan Form)**
•Pengertian: Proses mengumpulkan, menerima, dan mengolah data yang dikirimkan oleh pengguna melalui formulir HTML ke server PHP.
•Waktu Terjadi: Saat pengguna menekan tombol *Submit* pada form.
•Cara Kerja / Fungsi:** Menggunakan metode pengiriman `GET` atau `POST` yang ditangkap oleh variabel superglobal PHP seperti `$_GET['nama']`, `$_POST['nama']`, atau `$_REQUEST['nama']`.
* Contoh:Mengambil input nama yang diketik pengguna lalu menampilkannya ke layar menggunakan `echo $_POST['nama'];`.

2. Validasi Form (Form Validation)**
•Pengertian: Proses memeriksa dan memastikan bahwa data yang dimasukkan oleh pengguna sudah lengkap, sesuai dengan format/aturan yang ditentukan, serta aman sebelum diproses lebih lanjut atau disimpan ke database.
•Waktu Terjadi: Setelah data dikirimkan oleh pengguna dan diterima oleh server PHP (atau sebelum dikirim menggunakan validasi HTML/JavaScript).
•Cara Kerja / Fungsi: Menggunakan fungsi pengecekan PHP seperti `empty()`, `isset()`, `filter_var()`, `htmlspecialchars()`, dan `preg_match()`.
*Contoh: Memastikan kolom wajib tidak dibiarkan kosong, mengecek apakah penulisan email sudah memakai tanda `@`, serta mencegah masuknya kode berbahaya (serangan XSS).
*
