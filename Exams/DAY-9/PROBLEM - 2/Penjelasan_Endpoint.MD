# Penjelasan

1. GET Method

Digunakan untuk melakukan request melalui protokol HTTP GET Request yang apabila status nyaa sukses akan mengembalikan data yang di request, dalam kasus ini adalah String berupa "Hello world".

2. POST Method

Kita menggunakan POST atau HTTP POST Request unttuk membuat resource atau data baru ( umumnya pada database ), POST request memerlukan body atau biasa disebut Request body yang berisikan data baru yang akan ditambahkan atau dibuat. Data tsb harus sesuai dengan bentuk data yang udah didefinisikan pada entitas database, kalau tidak akan terjadi error BAD REQUST dengan status code 400.
untuk return bisa apa saja, namun umumnya akan mereturn data yg ditambhakn jika sukses atau hanya pesan string sukses dan pesan code. Dalam kasus ini kita mereturn String "Hello World".

3. DELETE Method

Delete digunakan untuk menghapus resource atau data, return 200 jika sukskes, dan failed dengan status code 404 jika tidak ditemukan data, oleh karena itu kita membutuhkan "id" dari data yg akan dihapus.



