# VaccineTableOOPJavaDB

Project ini adalah sebuah program Java GUI untuk menampilkan
Nama Vaksin, Harga Vaksin dan Stok Vaksin.

## Kelompok 22
2440030241 - Reynald Slamat Putra
2440062924 - Charles Christopher
2440046984 - Elliot Lie Arifin

Operasi yang bisa dilakukan pada program ini adalah :

### 1. Add Vaccine 
dengan generate random ID, Nama Vaksin, Harga Vaksin dan Stok Vaksinnya. Setelah itu, membuat sebuah objek untuk penjelasan melalui factory yang telah dibuat berdasarkan Harga Vaksin yang diinput pengguna. Lalu menampilkan informasi apakah vaksin tergolong murah atau mahal berdasarkan harganya, jika >50.000 termasuk golongan mahal yang diambil dari hasil pembuatan objek di factory.

###2. Update Vaccine
Hampir mirip dengan Add, dengan mengklik salah satu baris pada Table Vaccine, akan menampilkan informasi dari vaksin tersebut pada sebuah text field yang bisa diubah untuk diupdate. Proses menampilkan vaksin murah atau mahal juga sama dengan fitur Add.

### 3. Delete Vaccine 
Memilih salah satu baris pada table, lalu klik button delete, akan menghapus vaksin itu pada table.

### 4. Menampilkan Vaccine Table
Selalu memunculkan table Vaccine

## Implementasi 2 design pattern:
### Singleton = Koneksi DB pada class database.java
### Factory = Pembuatan object pada class readerFactory.java

### Penggunaan inheritance dan abstract kami terapkan pada class reader.java (interface)
### Penggunaan encapsulation kami terapkan pada ExpensiveReader dan CheapReader

### Pengimplementasian database transaction terjadi pada fitur add, update, dan delete
### dengan menggunakan SELECT, INSERT INTO, SET, dan DELETE di class Vaccine_Table
