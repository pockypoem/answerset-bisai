## Quiz Questions and Answers from Database Class

#### Q1. Kumpulan data yang saling berhubungan dan tersimpan secara sistematis disebut ...

- \[x] Database
- \[ ] Sistem Informasi
- \[ ] ERD
- \[ ] Information

#### Q2. Data yang telah diolah dan digunakan untuk pengambilan keputusan disebut ...

- \[ ] Primary Key
- \[ ] Indeks
- \[ ] Data
- \[x] Informasi

#### Q3. Beberapa Manfaat Basis Data secara umum yaitu ...

- \[ ] Kecepatan, sharability, keakuratan, keamanan, redudansi
- \[ ] Kecepatan, berulang, keakuratan, keamanan, ketersediaan
- \[x] Kecepatan, sharability, keakuratan, keamanan, ketersediaan
- \[ ] Kecepatan, sharability, keakuratan, duplikasi, ketersediaan

#### Q4. Model untuk menjelaskan hubungan antar data dalam basis data berdasarkan objek-objek dasar data yang mempunyai hubungan antar relasi yang memodelkan struktur data dan hubungan antar data, untuk menggambarkannya digunakan beberapa notasi dan symbol disebut ...

- \[ ] Semantic Model
- \[ ] Hirarki Model
- \[ ] Network Model
- \[x] Entity Relationship Model

#### Q5. Data merupakan sesuatu yang menyangkut barang, kejadian, aktivitas, dan transaksi yang telah tercatat, diklasifikasikan, dan disimpan namun belum memiliki makna. Diantara berikut ini yang merupakan contoh data antara lain ...

- \[x] Nilai mahasiswa
- \[ ] Daftar mahasiswa peraih cumlaude
- \[ ] Status klasemen liga inggris
- \[ ] Perkiraan cuaca Jakarta

#### Q6. Berikut ini merupakan komponen ERD adalah ...

- \[ ] Semantic, Network, Relasi, Kardinalitas
- \[ ] Entity, Database, Field, Record
- \[x] Entity, Atribut, Relasi, Kardinalitas
- \[ ] Field, Record, Entity, Table

#### Q7. Berikut ini yang BUKAN merupakan jenis model data antara lain ...

- \[ ] Model Data Berbasis Fisik
- \[ ] Model Data Berbasis Objek
- \[ ] Model Data Berbasis Record
- \[x] Model Data Berbasis Transaksi

#### Q8. Jumlah maksimum entitas yang dapat berelasi dengan entitas pada himpunan entitas yang lain disebut ...

- \[ ] Variablititas
- \[ ] Modalitas
- \[x] Kardinalitas
- \[ ] Unary

#### Q9. Notasi grafis dalam pemodelan data konseptual yang mendeskripsikan hubungan antara penyimpanan serta digunakan untuk memodelkan struktur data dan hubungan antar data disebut ...

- \[ ] Hirarki Model
- \[ ] Network Model
- \[x] Entity Relationship Diagram
- \[ ] Entity Relationship Data

#### Q10. Pengertian Entity adalah ...

- \[ ] Deskripsi karakter entity atau relationship
- \[ ] Notasi grafis dalam pemodelan data konseptual yang mendeskripsikan hubungan antara penyimpanan serta digunakan untuk memodelkan struktur data dan hubungan antar data
- \[ ] Hubungan diantara sejumlah entitas yang berasal dari himpunan entitas yang berbeda.
- \[x] Suatu objek yang dapat dibedakan atau dapat diidentifikasikan secara unik dengan objek lainnya, dimana semua informasi yang berkaitan dengannya dikumpulkan

#### Q11. Setiap entitas pada himpunan entitas A berhubungan dengan paling banyak satu entitas pada himpunan entitas B, dan begitupun sebaliknya setiap entitas pada himpunan entitas B berhubungan dengan paling banyak satu entitas pada himpunan entitas A disebut kardinalitas jenis ...

- \[ ] Many to One
- \[x] One to One
- \[ ] One to Many
- \[ ] Many to Many

#### Q12. Setiap entitas pada himpunan entitas A berhubungan dengan paling banyak satu entitas pada himpunan entitas B, dan tidak sebaliknya dimana setiap entitas pada himpunan entitas B dapat berhubungan dengan banyak entitas pada himpunan entitas A disebut kardinalitas jenis ...

- \[ ] Many to Many
- \[ ] One to One
- \[ ] One to Many
- \[x] Many to One

#### Q13. Setiap entitas pada himpunan entitas A dapat berhubungan dengan banyak entitas pada himpunan entitas B, dan tidak sebaliknya dimana setiap entitas pada himpunan entitas B berhubungan dengan paling banyak satu entitas pada himpunan entitas A disebut kardinalitas jenis ...

- \[x] One to Many
- \[ ] Many to Many
- \[ ] Many to One
- \[ ] One to One

#### Q14. Setiap entitas pada himpunan entitas A dapat berhubungan dengan banyak entitas pada himpunan entitas B, dan sebaliknya dimana setiap entitas pada himpunan entitas B dapat berhubungan dengan banyak entitas pada himpunan entitas A disebut kardinalitas jenis ...

- \[ ] One to One
- \[x] Many to Many
- \[ ] One to Many
- \[ ] Many to One

#### Q15. Suatu cara untuk menjelaskan bagaimana pemakai dapat melihat data secara logic disebut ...

- \[ ] Sistem Basis Data
- \[ ] Basis Data
- \[ ] DBMS
- \[x] Model Data

#### Q16. Berikut ini adalah Syntax yang benar mendefinisikan primary key untuk Field 1 ...

- \[x] `CREATE TABLE namatabel (Field1 TipeData1, Field2 TipeData2, PRIMARY KEY(Field1));`
- \[ ] `CREATE TABLE namatabel ADD CONSTRAINT namaconstraint PRIMARY KEY (namakolom);`
- \[ ] `ALTER TABLE namatabel(Field1 TipeData1 NOT NULL PRIMARY KEY, Field2 TipeData2);`
- \[ ] `CREATE TABLE namatabel(Field1 TipeData1 NOT NULL PRIMARY_KEY, Field2 TipeData2);`

#### Q17. Berikut ini perintah untuk membuat Database yang benar yaitu

- \[ ] `CREATE DATABASE DB AKADEMIK;`
- \[x] `CREATE DATABASE db_akademik;`
- \[ ] `CREATE DB_AKADEMIK;`
- \[ ] `CREATE db akademik;`

#### Q18. Berikut syarat untuk membuat tabel kecuali...

- \[ ] Field1 dan TipeData1 merupakan nama kolom pertama dan tipe data untuk kolom pertama
- \[x] Nama tabel case sensitive
- \[ ] Jika ingin membuat tabel dengan kolom lebih dari satu, maka setelah pendefinisan tipe data sebelumnya diberikan tanda koma (,)
- \[ ] Nama tabel tidak boleh mengandung spasi

#### Q19. Cara menghapus primary key jika primary key dibuat dengan menggunakan alter table yaitu ...

- \[x] `ALTER TABLE namatabel DROP PRIMARY KEY;`
- \[ ] `DROP TABLE namatabel ADD CONSTRAINT namaconstraint PRIMARY KEY (namakolom);`
- \[ ] `ALTER TABLE namatabel DROP CONSTRAINT namaconstraint;`
- \[ ] `ALTER TABLE namatabel (Field1 TipeData1 NOT NULL DROP PRIMARY KEY, Field2 TipeData2);`

#### Q20. Fungsi dari NOT NULL yaitu ...

- \[x] Memastikan bahwa nilai pada kolom tersebut tidak boleh kosong
- \[ ] Tidak mengizinkan nilai angka 0 pada kolom tersebut
- \[ ] Tidak mengizinkan spasi kosong pada kolom tersebut
- \[ ] Memastikan bahwa nilai pada kolom tersebut boleh kosong

#### Q21. Keyword perintah ALTER untuk menghapus kolom adalah ...

- \[ ] DELETE
- \[ ] CHANGE
- \[ ] REMOVE
- \[x] DROP

#### Q22. Perintah SHOW TABLES; digunakan untuk ...

- \[ ] Menampilkan Atribut Tabel
- \[ ] Menampilkan daftar nama database yang ada pada mysql
- \[x] Menampilkan daftar nama tabel yang ada pada database yang sedang aktif
- \[ ] Membuat Database

#### Q23. Syntax tambahan untuk menampilkan daftar nama database yang ada pada mysql yaitu ...

- \[ ] USE DATABASES;
- \[ ] SHOW TABLES;
- \[ ] DROP DATABASES;
- \[x] SHOW DATABASES;

#### Q24. Untuk mengaktifkan salah satu database sebagai database aktif yang akan digunakan sintaks sql ...

- \[ ] SHOW
- \[x] USE
- \[ ] CREATE
- \[ ] INSERT

#### Q25. Yang termasuk dalam kelompok DDL adalah (kecuali)...

- \[ ] DROP
- \[x] DELETE
- \[ ] CREATE
- \[ ] ALTER
