
# 📚 Bookshelf API

Submission Bookshelf API - Kelas Belajar Membuat Aplikasi Back-End untuk Pemula

## 🚀 Deskripsi Kelas

Belajar Membuat Aplikasi Back-End untuk Pemula <br>
Disusun oleh: Dicoding Indonesia <br>
Level: Pemula

<div align="center">
  <img src="https://user-images.githubusercontent.com/95717485/225231893-e59de44d-0d3e-4e79-971b-a4d494565a74.png" alt="Dicoding AWS">
</div>

<br>

Kelas ini ditujukan untuk individu yang ingin melangkah menjadi seorang Back-End Developer dengan standar kompetensi internasional milik AWS. Di akhir kelas, siswa dapat membuat RESTful API sederhana secara mandiri untuk mendukung fungsionalitas suatu aplikasi.

---

## 🛠️ Cara Menggunakan Aplikasi

### 1. **Persiapan Lingkungan**
Pastikan Anda sudah memiliki:
- **Node.js** (versi terbaru): [Download di sini](https://nodejs.org)
- **Postman** (opsional, untuk menguji API): [Download di sini](https://www.postman.com/downloads)

### 2. **Clone Repository**
Clone repository ini ke komputer Anda dengan perintah:
```bash
https://github.com/ihsanuradib/Project-Dicoding-Bookshelf-API.git
```
Lalu pindah ke direktori proyek:
```bash
cd Bookshelf-API
```

### 3. **Instalasi Dependensi**
Jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:
```bash
npm install
```

### 4. **Menjalankan Server**
Jalankan aplikasi menggunakan perintah:
```bash
npm start
```
Server akan berjalan di alamat default: `http://localhost:5000`.

### 5. **Mengonsumsi API**
Gunakan alat seperti Postman atau curl untuk mengakses endpoint berikut:
- **POST `/books`**: Menambahkan buku baru.
- **GET `/books`**: Mengambil daftar semua buku.
- **GET `/books/{id}`**: Mengambil detail buku berdasarkan ID.
- **PUT `/books/{id}`**: Memperbarui informasi buku berdasarkan ID.
- **DELETE `/books/{id}`**: Menghapus buku berdasarkan ID.

### 6. **Contoh Permintaan (Request)**
**Menambahkan Buku Baru**
- Endpoint: `POST /books`
- Body (JSON):
  ```json
  {
    "name": "Belajar Node.js",
    "year": 2024,
    "author": "John Doe",
    "summary": "Panduan belajar Node.js untuk pemula",
    "publisher": "Dicoding Publisher",
    "pageCount": 300,
    "readPage": 50,
    "reading": true
  }
  ```

**Mendapatkan Daftar Buku**
- Endpoint: `GET /books`
- Response (contoh):
  ```json
  {
    "status": "success",
    "data": {
      "books": [
        {
          "id": "Qbax5Oy7L8WKf74l",
          "name": "Belajar Node.js",
          "publisher": "Dicoding Publisher"
        }
      ]
    }
  }
  ```

---

## 🧪 Pengujian API
1. Gunakan **Postman** atau **tool lainnya** untuk mengirim request ke endpoint yang disediakan.
2. Pastikan semua operasi (Create, Read, Update, Delete) berjalan dengan benar sesuai kriteria.

---

## 📄 Evaluasi Pembelajaran
Proyek ini adalah bagian dari evaluasi akhir kelas "Belajar Membuat Aplikasi Back-End untuk Pemula" oleh Dicoding Indonesia. Proyek ini mencakup pembuatan RESTful API dengan fungsionalitas CRUD.

[^1]: [Show Credential](https://www.dicoding.com/certificates/QLZ9Q2MM2Z5D)
