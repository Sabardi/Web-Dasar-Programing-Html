# Generic Element
Setelah mengenal beberapa elemen yang ada, bagaimana jika tidak ada elemen yang mampu menggambarkan konten kita? Dalam dunia nyata, jenis informasi sangat beragam dan mungkin tidak semua semantik elemen yang kita ketahui dapat menggambarkan jenis informasinya. Untungnya, HTML menyediakan dua tipe elemen umum (generic element) yang bisa kita kustomisasi untuk menggambarkan konten kita dengan tepat. 

Ada dua generic element yang dapat kita manfaatkan. 

* Div
Pertama, elemen <div>, elemen ini merupakan sebuah wadah (container) yang bersifat umum untuk menampung beberapa konten. Elemen ini tidak akan memberikan efek apa pun pada konten atau layout sebelum menerapkan sebuah style menggunakan CSS.
Elemen <div> tidak merepresentasikan apa pun sebagai sebuah wadah yang murni. Elemen ini lebih sering digunakan untuk mengelompokkan sebuah konten sehingga dapat memudahkan styling dengan menggunakan atribut class atau id.

kode nya [Title](div.html)


* Span
elemen <span>, elemen ini memberikan manfaat yang sama seperti <div>, bedanya elemen ini digunakan sebagai phrase elements dan tidak terdapat line breaks ketika menggunakannya. Sederhananya, <span> merupakan sebuah <div> yang digunakan dalam sebuah baris teks yang dapat diwadahi oleh paragraf, list, heading, atau lainnya.

Mari kita ambil contoh. Tidak ada elemen pada inline element yang memiliki arti untuk menampung sebuah informasi telepon. Oleh karena itu, tiap item pada nomor telepon bisa ditampung dalam elemen <span> dan diklasifikasikan (menggunakan atribut class) dengan nilai “phone”.

kode nya [Title](Span.html)

