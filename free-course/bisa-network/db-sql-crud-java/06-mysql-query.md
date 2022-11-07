## Quiz for sixth syllabus

#### Q1. Misalkan terdapat 2 tabel yaitu siswa dan wali_siswa, dan tabel tersebut memiliki relasi pada field nisn. Query yang digunakan untuk mengambil seluruh data pada tabel siswa dan data yang memiliki kesesuaian pada tabel wali_siswa adalah?

- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa OUTER JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa FULL JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa INNER JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa RIGHT JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[x] SELECT siswa.\*,wali_siswa.\* FROM siswa LEFT JOIN wali_siswa ON siswa_nisn = wali_siswa.nisn

#### Q2. Misalkan terdapat 2 tabel yaitu siswa dan wali_siswa, dan tabel tersebut memiliki relasi pada field nisn. Query yang digunakan untuk mengambil data yang memiliki kesesuaian pada 2 tabel tersebut adalah?

- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa LEFT JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[x] SELECT siswa.\*, wali_siswa.\* FROM siswa INNER JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa OUTER JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa FULL JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn
- \[ ] SELECT siswa.\*, wali_siswa.\* FROM siswa RIGHT JOIN wali_siswa ON siswa.nisn = wali_siswa.nisn

#### Q3. Misalkan ada table siswa dengan 4 field yaitu nisn, nama, umur, dan alamat. Query yang digunakan untuk mengambil 5 data adalah?

- \[ ] SELECT \* FROM siswa OFFSET = 5
- \[x] SELECT \* FROM siswa LIMIT 5
- \[ ] SELECT \* FROM siswa LIMIT = 5
- \[ ] SELECT \* FROM siswa OFFSET(5)
- \[ ] SELECT \* FROM siswa OFFSET 5

#### Q4. Pada MySQL, yang digunakan untuk memberikan batasan jumlah data yang diambil adalah?

- \[ ] RESTRICT
- \[ ] BORDER
- \[ ] BOUNDARY
- \[ ] OFFSET
- \[x] LIMIT

#### Q5. Misalkan ada table siswa dengan 4 field yaitu nisn, nama, umur, dan alamat. Query yang digunakan untuk mengambil data dan diurutkan berdasarkan field umur secara ascending adalah?

- \[ ] SELECT \* FROM siswa SORT BY umur ASCENDING
- \[ ] SELECT \* FROM siswa SORTING umur ASCENDING
- \[ ] SELECT \* FROM siswa SORT BY umur ASC
- \[x] SELECT \* FROM siswa ORDER BY umur ASC
- \[ ] SELECT \* FROM siswa ORDER BY umur ASCENDING

#### Q6. Pada MySQL, keyword yang digunakan untuk mengurutkan data secara ascending adalah?

- \[ ] DESCENDING
- \[ ] ASCENDING
- \[x] ASC
- \[ ] DOWN
- \[ ] DESC

#### Q7. Pada MySQL yang digunakan untuk mengurutkan data adalah?

- \[x] ORDER BY
- \[ ] SORT BY
- \[ ] ORDER
- \[ ] SORTING
- \[ ] SORT

#### Q8. Misalkan ada table siswa dengan 4 field yaitu nisn, nama, umur, dan alamat. Query yang digunakan untuk mengambil data yang terdapat kata "Bambang" adalah?

- \[ ] SELECT \* FROM siswa FILTER nama = LIKE "%Bambang%"
- \[ ] SELECT \* FROM siswa FILTER nama = "%Bambang%"
- \[ ] SELECT \* FROM siswa FILTER nama LIKE = "%Bambang%"
- \[ ] SELECT \* FROM siswa WHERE nama = "Bambang"
- \[x] SELECT \* FROM siswa WHERE nama LIKE "%Bambang%"

#### Q9. Misalkan ada table siswa dengan 4 field yaitu nisn, nama, umur, dan alamat. Query yang digunakan untuk mengambil data dengan nisn=1001 adalah?

- \[ ] SELECT \* FROM siswa PASS nisn = "0001"
- \[x] SELECT \* FROM siswa WHERE nisn = "0001"
- \[ ] SELECT \* FROM siswa ONLY nisn = "0001"
- \[ ] SELECT \* FROM siswa SCREEN nisn = "0001"
- \[ ] SELECT \* FROM siswa FILTER nisn = "0001"

#### Q10. Pada MySQL yang digunakan untuk filter data/record adalah?

- \[ ] SCREEN
- \[ ] PASS
- \[ ] FILTER
- \[ ] ONLY
- \[x] WHERE
