## Quiz for third syllabus

#### Q1. Berikut yang berfungsi untuk mengolah data dalam database MySQL adalah?

- \[ ] DDL
- \[ ] GDP
- \[ ] GPL
- \[ ] MIT
- \[x] DML

#### Q2. Query yang digunakan untuk mengambil semua row dari table siswa adalah?

- \[ ] SELECT \* FROM TABLE : siswa
- \[ ] SELECT \* FROM TABLE (siswa)
- \[x] SELECT \* FROM siswa
- \[ ] FROM TABLE siswa SELECT \*
- \[ ] SELECT \* FROM TABLE siswa

#### Q3. Diberi permisalan, terdapat 3 field dalam table siswa yaitu: nisn, nama, dan umur. Query yang digunakan untuk mengambil data field nim dan nama adalah?

- \[ ] SELECT \* WHERE nisn = '11101' FROM TABLE siswa
- \[x] SELECT \* FROM siswa WHERE nisn = "11101"
- \[ ] SELECT \* FROM TABLE siswa WHERE nisn = "11101"
- \[ ] SELECT \* FROM TABLE siswa WHERE FIELD nisn = "11101"
- \[ ] SELECT \* WHERE nisn = "11101" FROM siswa

#### Q4. Diberi permisalan, terdapat 3 field dalam table siswa yaitu: nisn, nama, dan umur. Query yang digunakan untuk memasukkan data nisn: 11101, nama: Ilham, dan umur: 20 kedalam tabel siswa adalah?

- \[x] INSERT INTO siswa(nisn, nama, umur) VALUES ("11101", "Ilham", "20")
- \[ ] INSERT INTO TABLE siswa (nisn, nama, umur) DATA ("11101", "Ilham", "20")
- \[ ] INSERT INTO siswa (nisn, nama, umur) DATA ("11101", "Ilham", "20")
- \[ ] INSERT DATA ("11101", "Ilham", "20") INTO TABLE siswa (nisn, nama, umur)
- \[ ] INSERT INTO TABLE siswa (nisn, nama, umur) VALUES ("11101", "Ilham", "20")

#### Q5. Diberi permisalan, terdapat 3 field dalam table siswa yaitu: nisn, nama, dan umur. Query yang digunakan untuk memasukkan data nisn: 11101, nama: Ilham, dan umur: 20 kedalam tabel siswa adalah?

- \[x] INSERT INTO siswa(nisn, nama, umur) VALUES ("11101", "Ilham", "20")
- \[ ] INSERT INTO TABLE siswa (nisn, nama, umur) DATA ("11101", "Ilham", "20")
- \[ ] INSERT INTO siswa (nisn, nama, umur) DATA ("11101", "Ilham", "20")
- \[ ] INSERT DATA ("11101", "Ilham", "20") INTO TABLE siswa (nisn, nama, umur)
- \[ ] INSERT INTO TABLE siswa (nisn, nama, umur) VALUES ("11101", "Ilham", "20")

#### Q6. Diberi permisalan, terdapat 4 field dalam table guru yaitu: nip, nama, alamat dan no_telepon. Query yang digunakan untuk memasukkan data nip: 22201, nama: Bayu, alamat: Bandung, dan no telepon: 08123456787 ke dalam tabel guru adalah?

- \[ ] INSERT INTO TABLE guru(nip, nama, alamat, no_telepon) VALUES ("22201", "Bayu", "Bandung", "081234546787")
- \[ ] INSERT INTO guru (nip, nama, alamat, no_telepon) VALUES ("22201", "Bayu", "Bandung", "08123456787")
- \[ ] INSERT INTO guru (nip, nama, alamat, no_telepon) DATA ("22201", "Bayu", "Bandung", "08123456787")
- \[x] INSERT INTO guru (nip, nama, alamat, no_telepon) VALUES ("22201", "Bayu", "Bandung", "08123456787")
- \[ ] INSERT INTO TABLE guru(nip, nama, alamat, no_telepon) VALUES ("22201", "Bayu", "Bandung", "081234546787")

#### Q7. Diberi permisalan, terdapat 4 field dalam table guru yaitu: nip, nama, alamat dan no_telepon. Query yang digunakan untuk mengubah nama menjadi Bambang, alamat menjadi Jakarta, dan no_telepon menjadi 081298786754 dengan nip 22201 adalah?

- \[ ] UPDATE TABLE guru CHANGE nama="Bambang", alamat="jakarta", no_telepon="081298786754" WHERE nip="22201"
- \[ ] UPDATE guru CHANGE nama="Bambang", alamat="jakarta", no_telepon="081298786754" WHERE nip="22201"
- \[x] UPDATE guru SET nama="Bambang", alamat="jakarta", no_telepon="081298786754" WHERE nip="22201"
- \[ ] UPDATE TABLE guru SET nama="Bambang", alamat="jakarta", no_telepon="081298786754" WHERE nip="22201"
- \[ ] UPDATE guru WHERE nip="22201" SET nama="Bambang", alamat="jakarta", no_telepon="081298786754"

#### Q8. Diberi permisalan, terdapat 4 field dalam table guru yaitu: nip, nama, alamat dan no_telepon. Query yang digunakan untuk mengambil data guru yang no teleponnnya null adalah?

- \[x] SELECT \* FROM guru WHERE no_telepon IS NULL
- \[ ] SELECT \* FROM TABLE guru WHERE no_telepon IS NULL
- \[ ] SELECT \* FROM guru WHERE no_telepon IS EMPTY
- \[ ] SELECT \* FROM guru WHERE no_telepon = NULL
- \[ ] SELECT \* FROM TABLE guru WHERE no_telepon = NULL

#### Q9. Diberi permisalan, terdapat 4 field dalam table guru yaitu: nip, nama, alamat dan no_telepon. Query yang digunakan untuk mengambil semua data guru dengan mengurutkan berdasarkan NIP secara ascending adalah?

- \[ ] SELECT nip = ASCENDING FROM guru
- \[x] SELECT \* FROM guru ORDER BY nip ASC
- \[ ] SELECT \* FROM guru SORT nip ASCENDING
- \[ ] SELECT \* FROM guru ORDER BY nip ASCENDING
- \[ ] SELECT \* FROM guru SORT nip ASC

#### Q10. Diberi permisalan, terdapat 4 field dalam table guru yaitu: nip, nama, alamat dan no_telepon. Query yang digunakan untuk menghapus data guru dengan nim=22201 adalah?

- \[ ] DELETE FROM TABLE guru WHERE nip = 22201
- \[ ] DROP FROM guru WHERE nip = 22201
- \[ ] DROP FROM TABLE guru WHERE nip = 22201
- \[x] DELETE FROM guru WHERE nip = 22201
- \[ ] DISCARD FROM guru WHERE nip = 22201
