# Gambar
Tanpa gambar, sebuah website tentu tidak akan menarik bukan? Ada beberapa alasan mengapa website perlu gambar. Contohnya kita perlu menampilkan logo perusahaan, ilustrasi, diagram struktur atau data, dan sebagainya. 

Pada HTML untuk menampilkan sebuah gambar kita bisa menggunakan tag <img>. Berbeda dengan elemen lain, elemen <img> tidak menuliskan konten di antara tag pembuka dan tag penutup. Namun, untuk menetapkan gambar yang ditampilkan kita gunakan sebuah atribut. 

# Jenis format gambar
Berikut adalah jenis format gambar yang umum digunakan pada pembuatan website
![Alt text](image.png)

![Alt text](image-1.png)

# Mengatur Ukuran pada Gambar
Untuk mengatur ukuran gambar yang ditampilkan, kita juga tentunya menggunakan sebuah atribut. Untuk menentukan lebar gambar, kita gunakan atribut width, dan untuk menentukan tinggi tentu gunakan atribut height.

![Alt text](image-2.png)

Ketika menggunakan atribut ini, disarankan hanya gunakan salah satunya. Terkecuali kita menentukan nilai lebar dan tingginya sesuai dengan rasio dari ukuran gambar aslinya. 

Contohnya, jika kita tetap memaksa untuk menentukan ukuran panjang dan lebar sebuah gambar tanpa menyesuaikan rasionya, gambar yang ditampilkan tidak akan proporsional.

<!-- Jangan lakukan hal ini! -->
<img src="https://raw.githubusercontent.com/dicodingacademy/BelajarDasarPemrogramanWeb/099-shared-files/dicoding-logo.png" alt="Logo Dicoding" width="500px" height="200px">

Hasilnya berikut.

![Alt text](image-3.png)

Dengan menetapkan hanya satu atribut ukurannya, maka ukuran lainnya akan mengikuti sesuai dengan rasio gambar aslinya. Contohnya, kita bisa menetapkan ukuran gambar berdasarkan nilai lebarnya saja.

<!-- Menetapkan ukuran gambar berdasarkan lebar -->
<img src="https://raw.githubusercontent.com/dicodingacademy/BelajarDasarPemrogramanWeb/099-shared-files/dicoding-logo.png" alt="Logo Dicoding" width="500px">

![Alt text](image-4.png)



Opsi lainnya, kita juga bisa tetapkan ukuran gambar berdasarkan tingginya. Dengan begitu nilai lebar akan menyesuaikan nilainya berdasarkan rasio gambar aslinya

<!-- Menetapkan ukuran gambar berdasarkan tinggi -->
<img src="https://raw.githubusercontent.com/dicodingacademy/BelajarDasarPemrogramanWeb/099-shared-files/dicoding-logo.png" alt="Logo Dicoding" height="100px">

![Alt text](image-5.png)
