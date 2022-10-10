## Mid Semester Questions and Answers from Database Class

#### Q1. Kunci berikut digunakan untuk menunjukkan keunikan dalam koleksi?

- \[x] \_id
- \[ ] id
- \[ ] id\_
- \[ ] id-

#### Q2. Operator yang akan menampilkan record apabila salah satu kondisi bernilai TRUE adalah ...

- \[ ] AND
- \[x] OR
- \[ ] ORDER
- \[ ] NOT

#### Q3. Perintah mana di Mongodb yang setara dengan SQL select?

- \[ ] none
- \[ ] search()
- \[ ] document
- \[x] find()

#### Q4. Berikut merupakan sintaks pada mongoDB untuk mengubah data yaitu ...

- \[ ] `db.nama_koleksi.update({$set : { data yang di ubah }, {kriteria}} )`
- \[ ] `db.nama_koleksi.updateOne({$set : { data yang di ubah }, {kriteria}} )`
- \[ ] `db.nama_koleksi.updateOne({kriteria}, {$set : { data yang di ubah } } )`
- \[x] `db.nama_koleksi.update({kriteria}, {$set : { data yang di ubah } } )`

#### Q5. Manakah dari operasi berikut yang menambahkan dokumen baru ke koleksi pengguna?

- \[x] insert
- \[ ] drop
- \[ ] add
- \[ ] truncate

#### Q6. Untuk menampilkan data berdasarkan kriteria lebih besar dari atau sama dengan menggunakan sintaks di mongoDB...

- \[ ] $gt
- \[x] $gte
- \[ ] $lt
- \[ ] $lte

#### Q7. Terdapat basis data rumah sakit yang terdiri dari beberapa table. Salah satu table yang sesuai dengan basis data tersebut adalah ….

- \[ ] Buku, anggota, peminjaman, pengembalian
- \[x] Dokter, pasien, obat, pendaftaran dan kasir
- \[ ] Siswa, guru, matapelajaran, nilai dan jadwal
- \[ ] Barang, jual, beli, stok dan supplier

#### Q8. Bagaimana nilai untuk \_id diberikan untuk setiap dokumen?

- \[ ] Value untuk field \_id adalah nilai integer yang sekuensial
- \[x] Secara otomatis di-generate sebagai value dengan tipe ObjectId
- \[ ] Saat sebuah document ditambahkan pada collection sebuah field random untuk dijadikan field \_id
- \[ ] Kita tidak bisa memilih tipe value selain ObjectId saat menambahkan sebuah dokumen selama nilai ini unik untuk dokumen tersebut

#### Q9. perintah dasar SQL yang di gunakan untuk mengembalikan hanya nilai yang berbeda dari dalam sebuah tabel, dengan kata lain semua record duplikat (record dengan nilai yang sama) yang terdapat pada tabel akan di anggap sebagai satu record/nilai adalah ....

- \[ ] SELECT \* FROM ...
- \[ ] SELECT ROUND ...
- \[x] SELECT DISTINCT ...
- \[ ] SELECT \* FROM ... WHERE ...

#### Q10. Manakah berikut ini yang termasuk column-oriented databases?

- \[ ] MySQL
- \[ ] Neo4j
- \[x] Cassandra
- \[ ] MongoDB

#### Q11. misalkan kia ingin menghapus data kelas yang memiliki nama kelasnya adalah RPL. Bagaimana perintah SQL yang harus dilakukan?

- \[x] `DELETE FROM kelas WHERE nama_kelas = "RPL"`
- \[ ] `DELETE * FROM kelas WHERE nama_kelas = "RPL"`
- \[ ] `DELETE FROM "kelas" WHERE "nama_kelas" = "RPL"`
- \[ ] `DELETE FROM nama_kelas WHERE kelas = "RPL"`
- \[ ] `DELETE "RPL" FROM kelas WHERE nama_kelas = "RPL"`

#### Q12. Manakah dari ini yang tidak benar untuk SQL vs NoSQL?

- \[ ] NoSQL adalah perangkat lunak yang lebih baru sehingga lebih kompatibel dengan program modern
- \[ ] SQL membutuhkan skema sedangkan NoSQL tidak
- \[x] Basis data relasional menggunakan data terstruktur dokumen sedangkan NoSQL menggunakan tabel
- \[ ] Basis data NoSQL lebih mudah diskalakan daripada basis data relasional

#### Q13. Untuk menghapus suatu database, sintaks umumnya adalah sbb ..

- \[ ] RENAME DATABASE [IF EXISTS] nama_database;
- \[ ] REMOVE DATABASE [IF EXISTS] nama_database;
- \[x] DROP DATABASE [IF EXISTS] nama_database;
- \[ ] DELETE DATABASE [IF EXISTS] nama_database;

#### Q14. Perintah untuk menampilkan dokument pada NoSQL pada database dengan nama "sewa", collection dengan nama "mobil" yaitu ...

- \[ ] use.mobil
- \[ ] db.sewa.find()
- \[ ] show.collections
- \[x] db.mobil.find()

#### Q15. MongoDB adalah database nosql berbasis \***\*\_\*\*** yang menyediakan kinerja tinggi, ketersediaan tinggi, dan skalabilitas yang mudah.

- \[x] document
- \[ ] all
- \[ ] graph
- \[ ] key value

#### Q16. Untuk membuka database mahasiswa, berikut ini querynya ...

- \[ ] DROP mahasiswa;
- \[ ] CREATE mahasiswa;
- \[ ] OPEN mahasiswa;
- \[x] USE mahasiswa;

#### Q17. Untuk keluar dari MySQL di commandline dapat menggunakan perintah ...

- \[x] \q
- \[ ] bye
- \[ ] stop
- \[ ] \c
- \[ ] esc

#### Q18. Salah satu ketentuan memberi perintah pada MySQL yaitu

- \[x] Setiap perintah harus selalu diakhiri dengan tanda titik koma misalnya quit;
- \[ ] Perintah-perintah dalam lingkungan MySQL menerapkan aturan case sensitive.
- \[ ] Setiap perintah akan disimpan dalam buffer untuk menyimpan histori perintah-perintah yang pernah diberikan.
- \[ ] Perintah berupa perintah khusus MySQL saja.

#### Q19. Manakah dari berikut ini yang bukan database NoSQL?

- \[ ] couchDB
- \[ ] Cassandra
- \[x] SQL Server
- \[ ] MongoDB

#### Q20. Jenis Perintah SQL adalah ...

- \[x] DDL dan DML
- \[ ] MLM dan DDL
- \[ ] DLL dan MLM
- \[ ] DML dan DLL

#### Q21. perintah menampilkan daftar database di mongoDB adalah...

- \[ ] show db
- \[ ] display dbs
- \[ ] show data
- \[x] show dbs

#### Q22. Sintak insert untuk menambahkan data pada tabel yang memiliki kolom NIS, nama dan umur, berikut ini yang salah (terjadi error) adalah ...

- \[ ] INSERT INTO siswa (NIS, nama, umur) VALUES ("123","Rio","16")
- \[ ] INSERT INTO siswa (NIS, nama, umur, alamat) VALUES ("123","Rio","16","Gianyar")
- \[ ] INSERT INTO siswa (umur,nama,NIS) VALUES ("16","Rio","123")
- \[x] INSERT INTO siswa VALUES ("123","Rio","16")

#### Q23. Rilis awal MongoDB ada di tahun?

- \[ ] 2011
- \[ ] 2005
- \[x] 2009
- \[ ] 2000

#### Q24. Perangkat lunak bebas yang ditulis dalam bahasa pemrograman PHP yang digunakan untuk menangani administrasi MySQL melalui World Wide Web disebut...

- \[ ] Command Line
- \[ ] Perl
- \[ ] Control Panel
- \[x] Phpmyadmin
- \[ ] Xampp

#### Q26. Sintak SQL untuk menampilkan nama siswa pada tabel siswa yang berada di kelas RPL adalah ...

- \[ ] SELECT "nama_siswa" FROM "siswa" WHERE "kelas" = "RPL"
- \[x] SELECT nama_siswa FROM siswa WHERE kelas = "RPL"
- \[ ] SELECT \* FROM nama_siswa WHERE kelas = "RPL"
- \[ ] SELECT \* FROM nama_siswa WHERE siswa = "RPL"

#### Q27. Berikut merupakan perangkat lunak database relasi (Relational Database Management System atau RDBMS) kecuali ..

- \[x] MONGODB
- \[ ] Postgresql
- \[ ] MS SQL
- \[ ] ORACLE
- \[ ] MYSQL

#### Q28. Sebuah metode di mongoDB yang digunakan untuk menampilkan data seperti find tetapi kita dapat menampilkan dari beberapa koleksi untuk jika tabelnya sudah berrelasi, disebut ...

- \[ ] Lookup
- \[x] Match
- \[ ] Set
- \[ ] LocalField

#### Q29. Misalkan kita ingin mengubah data siswa pada kolom nama menjadi Anita Mariani dalam tabel siswa yang nisnya 200. Bagaimana perintah SQL yang harus dilakukan?

- \[x] UPDATE mahasiswa SET nama = "Anita Mariani" WHERE nis = "200"
- \[ ] UPDATE "mahasiswa" SET "nama" = "Anita Mariani" WHERE "nis" = "200"
- \[ ] UPDATE nama mahasiswa SET "Anita Mariani" WHERE nis = "200"
- \[ ] UPDATE nama mahasiswa SET = "Anita Mariani" WHERE nis = "200"

#### Q30. Untuk menambahkan data langsung banyak pada mongoDB kita dapat menggunakan cara...

- \[ ] db.nama_koleksi.insertAll()
- \[ ] db.nama_koleksi.insertOne()
- \[ ] db.nama_koleksi.saveMany()
- \[x] db.nama_koleksi.insertMany()

#### Q31. Jika kita melakukan penambahan dokumen pada mongoDB untuk key value berikut "Nama : Fatih, Alamat : Malang". maka perintah yang benar adalah...

- \[ ] db.siswa.saveOne({nama:"Fatih",alamat:"Malang"})
- \[ ] db.siswa.insert{"nama":"Fatih","alamat":"Malang"}
- \[ ] db.siswa.insert({"nama":Fatih,"alamat":Malang});
- \[x] db.siswa.insertOne({"nama":"Fatih","alamat":"Malang"})

#### Q32. Sebutkan perbedaan mendasar antara Database SQL dan NoSQL dari pernyataan berikut ini.. (1) SQL memiliki Relational, (2) NoSQL memiliki record dan field, (3) NoSQL bentuk data dokumen yang terdiri dari Key dan Value, (4) SQL memiliki record dan field, (5) SQL bentuk data bisa dalam bentuk Grafik. Pilih jawaban yang benar..

- \[ ] 1, 2 dan 3
- \[ ] 2, 3 dan 4
- \[ ] 1, 3 dan 5
- \[x] 1, 3 dan 4

#### Q33. Manakah dari berikut ini yang setara di MongoDB dari pernyataan SQL select\* from employee order by salary desc;?

- \[ ] db.employee.find.sort({“salary”:1}]
- \[ ] db.employee.sort({“salary”:1}]
- \[ ] db.employee.sort ({“salary”:-1}]
- \[x] db.employee.find.sort ({“salary”:-1}

#### Q34. Setiap field dalam table harus diikuti tipe data. Tipe data yang sesuai pada field nilai adalah ….

- \[x] Integer
- \[ ] Date
- \[ ] Char
- \[ ] Varchar

#### Q35. Tunjukkan pernyataan yang benar.

- \[ ] MongoDB lebih menyukai format XML daripada JSON
- \[ ] MongoDB adalah penyimpanan database berorientasi kolom
- \[x] MongoDB diklasifikasikan sebagai database NoSQL
- \[ ] Semua benar

#### Q36. Apa kegunaan dari SQL?

- \[ ] Menyimpan data di database
- \[ ] Mengambil data di database
- \[x] Semua jawaban benar
- \[ ] Manipulasi data di database
