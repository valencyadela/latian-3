# Deskripsi Program Validasi Input Pendaftaran Online

Program ini dirancang untuk memastikan bahwa data yang dimasukkan pada pendaftaran online memenuhi kriteria yang telah ditentukan. Validasi input sangat penting untuk menjaga kualitas dan akurasi data, serta untuk menghindari kesalahan yang dapat mengganggu proses pendaftaran. Dengan adanya validasi, pengguna akan mendapatkan umpan balik langsung mengenai kesalahan yang mungkin mereka buat saat mengisi formulir.

Terdapat tiga jenis data utama yang perlu divalidasi: nama lengkap, nomor telepon, dan email. Nama lengkap harus terdiri hanya dari huruf, yang menjamin bahwa tidak ada karakter khusus atau angka yang disertakan. Untuk melakukan validasi ini, program menggunakan metode `isalpha()`, yang secara efektif memeriksa setiap karakter dalam input nama.

Selanjutnya, nomor telepon harus berisi hanya angka, tanpa karakter tambahan seperti spasi atau tanda baca. Validasi ini dilakukan dengan menggunakan metode `isdigit()`, yang memastikan bahwa seluruh input adalah digit. Ini penting untuk memastikan bahwa nomor telepon yang dikumpulkan dapat digunakan untuk komunikasi lebih lanjut tanpa adanya kesalahan.

Email juga memiliki kriteria khusus. Program memeriksa bahwa input email mengandung karakter `@` dan setidaknya satu karakter `.` setelahnya. Ini dilakukan untuk memastikan bahwa format email yang dimasukkan valid dan dapat digunakan untuk keperluan komunikasi. Validasi ini membantu mengurangi kemungkinan kesalahan dalam penulisan alamat email yang dapat mengakibatkan kegagalan pengiriman informasi penting.

Akhirnya, jika semua input telah divalidasi dengan sukses, program akan menampilkan pesan yang menyatakan bahwa data pendaftaran valid. Jika ada kesalahan pada salah satu input, program akan memberikan pesan error yang sesuai, sehingga pengguna dapat segera memperbaiki kesalahan tersebut. Dengan cara ini, program tidak hanya meningkatkan akurasi data, tetapi juga memberikan pengalaman yang lebih baik bagi pengguna.

## kode program pyhton :

![perintah valen](https://github.com/user-attachments/assets/b2005d9b-352c-452f-a985-ae48599a26f5)

## hasil akhir program (tampilan) : 

![output valencia](https://github.com/user-attachments/assets/54a04e5d-162e-4d15-a23c-726cbc3efd24)
