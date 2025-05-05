# 📦 SQL Dasar: Latihan Query dengan MariaDB/MySQL

Proyek ini berisi latihan dasar penggunaan SQL menggunakan MariaDB/MySQL. Latihan difokuskan pada pembuatan database dan tabel, penggunaan perintah `SELECT`, `INSERT`, `WHERE`, `UPDATE`, `DELETE`, serta ekspor data.

---

## 📁 Struktur Database

### Database: `tugas_day11`

#### Tabel `produk`
| Kolom        | Tipe Data      |
|--------------|----------------|
| id           | INT (PRIMARY)  |
| nama_produk  | VARCHAR(50)    |
| harga        | FLOAT          |
| stok         | INT            |

#### Tabel `pelanggan`
| Kolom   | Tipe Data     |
|---------|---------------|
| id      | INT (PRIMARY) |
| nama    | VARCHAR(20)   |
| alamat  | VARCHAR(100)  |
| telepon | VARCHAR(15)   |

---

## ✅ Tugas

### Tugas 1: Perintah SELECT

- Membuat tabel `produk`
- Menambahkan 5 data produk
- Menampilkan semua data dari `produk`
- Menampilkan `nama_produk` dan `harga` dengan stok > 10

### Tugas 2: Perintah INSERT

- Membuat tabel `pelanggan`
- Menambahkan 3 data pelanggan
- Menampilkan seluruh data pelanggan

### Tugas 3: Perintah WHERE

- Menampilkan produk dengan harga < 100.000
- Menampilkan produk dengan nama diawali huruf "A"
- Menampilkan pelanggan yang alamatnya mengandung kata "Jakarta"

### Tugas 4: SELECT + INSERT + WHERE

- Menambahkan 1 produk baru
- Menampilkan semua produk dengan harga > 200.000

---



---
