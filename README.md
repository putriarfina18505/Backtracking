# Aplikasi Penjadwalan Laboratorium Menggunakan Algoritma Backtracking

## 📌 Deskripsi Aplikasi
Aplikasi ini merupakan aplikasi web berbasis **Python Flask** yang digunakan untuk membantu proses **penjadwalan penggunaan laboratorium** secara otomatis.  
Aplikasi ini dirancang untuk mencocokkan data mata kuliah dengan ruangan laboratorium berdasarkan kapasitas dan kebutuhan mata kuliah menggunakan **algoritma backtracking**.

Data ruangan dan mata kuliah disimpan dalam **database SQLite**, sehingga memudahkan pengelolaan data dan proses penjadwalan secara terstruktur.

---

## ⚙️ Fitur Aplikasi
- Menambahkan data **ruangan laboratorium** beserta kapasitasnya
- Menambahkan data **mata kuliah** (nama mata kuliah, dosen pengampu, jumlah mahasiswa, dan SKS)
- Menampilkan data ruangan dan mata kuliah yang tersimpan
- Menghasilkan **jadwal laboratorium otomatis** menggunakan algoritma backtracking
- Menghapus seluruh data (reset database)

---

## 🛠️ Teknologi yang Digunakan
- **Python**
- **Flask Framework**
- **SQLite Database**
- **HTML (Template Engine Flask)**
- **Algoritma Backtracking**

---

## 🧠 Algoritma yang Digunakan
Aplikasi ini menggunakan **algoritma backtracking** untuk menentukan penjadwalan laboratorium.  
Algoritma ini bekerja dengan cara mencoba berbagai kemungkinan penempatan mata kuliah ke ruangan yang tersedia, kemudian mengevaluasi apakah penempatan tersebut memenuhi batasan kapasitas dan ketentuan lainnya.  
Jika suatu kemungkinan tidak valid, maka sistem akan kembali ke langkah sebelumnya dan mencoba kemungkinan lain.

---

## 🚀 Cara Menjalankan Aplikasi
1. Pastikan Python sudah terinstall
2. Clone repository ini
   ```bash
   git clone <url-repository>
