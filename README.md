# myportofolio_mobile

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


### Pertanyaan Reflektif tugas 7

1. Widget tree adalah struktur/susunan yang menggambarkan hubungan antara semua komponen widget dalam flutter. Dalam widget tree terdapat hubungan induk-anak (parent-child), dimana sebuah widget (induk) dapat memiliki satu atau lebih widget lain (anak). Widget induk mengatur tata letak dan posisi widget anaknya.

2. Widget yang digunakan dalam proyek MyPortofolio Mobile:
    1. MaterialApp: Mengatur konfigurasi utama aplikasi, seperti tema dan halaman utama.
    2. Scaffold: Menyediakan struktur dasar halaman.
    3. AppBar: Menampilkan judul aplikasi pada bagian atas.
    4. Padding: Memberikan jarak di sekitar widget.
    5. Column: Menyusun widget secara horizontal.
    6. Row: Menyusun widget secara vertikal.
    7. Center: Menempatkan widget di tengah.
    8. Text: Menampilkan teks.
    9. GridView.count: Menampilkan item dalam bentuk grid.
    10. Container: Mengatur ukuran, padding, dan tampilan widget.
    11. Material: Memberikan tampilan material pada item.
    12. InkWell: Membuat widget dapat menerima interaksi seperti klik.
    13. Icon: Menampilkan icon.
    14. SnackBar: Menampilkan pesan sementara ketika user klik sebuah item.
    15. InfoCard: Custom widget untuk menampilkan informasi seperti NPM, nama, dan kelas.
    15. ItemCard: Custom widget untuk menampilkan item menu beserta ikon dan warnanya.

3. MaterialApp berfungsi untuk mengatur berbagai konfigurasi utama aplikasi, seperti tema (theme), halaman awal (home), navigasi (route), serta pengaturan tampilan aplikasi secara keseluruhan. Widget ini digunakan sebagai root widget karena menjadi dasar struktur aplikasi dan menyediakan fitur material design bagi widget di bawahnya.

4. StatelessWidget merupakan widget yang tidak memiliki state internal yang berubah. Cocok untuk untuk tampilan yang relatif tetap. Sedangkan StatefulWidget merupakan widget yang memiliki state yang dapat berubah. Cocok untuk tampilan yang dipengaruhi interaksi dari user dan menggunakan setState() guna memperbarui tampilan.

5. BuildContext adalah objek yang menunjukkan posisi sebuah widget dalam widget tree. Fungsinya untuk mengakses informasi dari widget induk seperti tema, navigasi, dan pesan SnackBar. Biasanya digunakan sebagai parameter dalam method build(buildContext context).

6. Hot reload merupakan fitur Flutter yang digunakan untuk memperbarui tampilan aplikasi setelah melakukan perubahan kode tanpa menghapus state yang sedang berjalan atau menjalankan ulang aplikasi dari awal. Sedangkan hot restart menjalankan ulang aplikasi Flutter dari awal sehingga state yang sedang tersimpan akan dihapus. Selain itu, adapun full restart dilakukan dengan menghentikan aplikasi dan menjalankannya kembali melalui proses build baru. Hot reload biasanya digunakan untuk perubahan tampilan, sedangkan hot restart diperlukan ketika perubahan berkaitan dengan inisialisasi aplikasi atau state awal. Full restart diperlukan ketika terdapat perubahan konfigurasi yang tidak dapat diterapkan melalui hot reload maupun hot restart.

### Deklarasi AI tugas 7
Pada pengerjaan tugas 7 ini, saya menggunakan ChatGPT sebagai alat bantu untuk memahami materi lebih lanjut terkait widget dan fitur-fitur mengenai hot reload, hot restart, dan full restart dalam Flutter.

Link percakapan dengan ChatGPT:
https://chatgpt.com/share/6afac9db-3840-83ec-b669-49f3400f6689