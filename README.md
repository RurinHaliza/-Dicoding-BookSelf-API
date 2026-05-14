# Bookshelf API

RESTful API sederhana untuk mengelola data buku yang dibuat sebagai submission kelas Belajar Membuat Aplikasi Back-End untuk Pemula di Dicoding.

Project ini dibangun menggunakan Node.js dan mampu melakukan operasi CRUD (Create, Read, Update, Delete) terhadap data buku melalui endpoint API.

## Features

* Menambahkan buku baru
* Menampilkan seluruh data buku
* Menampilkan detail buku berdasarkan ID
* Mengubah data buku
* Menghapus buku
* Validasi request body
* Menggunakan RESTful API
* Menggunakan unique ID dengan nanoid
* Menggunakan port 9000

## Technologies Used

* Node.js
* Hapi.js
* REST API
* JavaScript
* nanoid

## API Endpoints

### Add Book

```http id="u7g9fq"
POST /books
```

### Get All Books

```http id="9yuh98"
GET /books
```

### Get Book Detail

```http id="4i2mp6"
GET /books/{bookId}
```

### Update Book

```http id="vgtjlwm"
PUT /books/{bookId}
```

### Delete Book

```http id="vz5ucg"
DELETE /books/{bookId}
```

## How to Run the Project

### Menjalankan Secara Lokal

1. Masuk ke folder project

```bash id="g6g8f8"
cd bookshelf-api
```

2. Install dependencies

```bash id="l22rtm"
npm install
```

3. Jalankan server

```bash id="5y25v2"
npm run start
```

4. Server berjalan pada

```bash id="wbsk5d"
http://localhost:9000
```

## Validation Rules

* Nama buku wajib diisi
* `readPage` tidak boleh lebih besar dari `pageCount`

## Testing

Project diuji menggunakan Postman Collection dan Environment yang disediakan oleh Dicoding untuk memastikan seluruh endpoint API berjalan sesuai kriteria submission.

## Learning Outcome

Melalui project ini, saya mempelajari:

* Dasar RESTful API
* Routing menggunakan Hapi.js
* HTTP Method (GET, POST, PUT, DELETE)
* Validasi request
* Pengelolaan data menggunakan JavaScript
* Pengujian API menggunakan Postman
* Struktur dasar backend application dengan Node.js

## Author

Created by Rin during Dicoding Back-End Development Learning Path.
