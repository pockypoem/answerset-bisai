## Quiz for fourth syllabus

#### Q1. Berikut pernyataan yang salah mengenai preprocessing text adalah 

- \[ ] Semua Benar
- \[ ] Menghilangkan data yang duplikat
- \[x] Mengubah data teks menjadi data angka
- \[ ] Menghilangkan data yang tidak konsisten
- \[ ] Proses untuk membersihkan data teks

#### Q2. Proses menghilangkan karakter yang ilegal pada dokumen disebut...

- \[ ] Stemming
- \[x] Filtering
- \[ ] Case folding
- \[ ] Semua Benar
- \[ ] Tokenization

#### Q3. Proses menyeragamkan huruf dengan mengubah huruf ke dalam bentuk kecil semua atau besar disebut

- \[x] Case folding
- \[ ] Tokenization
- \[ ] Semua Benar
- \[ ] Stemming
- \[ ] Filtering

#### Q4. Langkah untuk memecah dokumen teks menjadi kata per kata disebut ....

- \[ ] Filtering
- \[ ] Semua Benar
- \[x] Tokenization
- \[ ] Case folding
- \[ ] Stemming

#### Q5. Cara untuk mengubah sebuah kata ke dalam bentuk kata dasar dinamakan

- \[ ] Semua Benar
- \[ ] Tokenization
- \[ ] Case folding
- \[x] Stemming
- \[ ] Filtering

#### Q6. Berikut merupakan pernyataan yang benar mengenai padding, kecuali...

- \[ ] Padding memproses agar tiap dokumen memiliki panjang yang sama
- \[ ] Data inputan machine learning tidak melalui proses padding
- \[ ] Semua Benar
- \[ ] Menambah kata "" jika dokumen kurang panjang
- \[x] Data inputan machine learning harus melalui proses padding

#### Q7. Kode program untuk melakukan proses case folding adalah

- \[ ] Semua Benar
- \[x] casefolding.lower()
- \[ ] str.lower()
- \[ ] lower.str()
- \[ ] casefolding.head()

#### Q8. Dibawah ini merupakan contoh dataset untuk soal nomor 8, 9, dan 10: <br> 0 alam yang indah <br> 1 tempat terindah nomor 1, sangat direkomendasikan!!! <br> Dataset diatas kemudian dilakukan proses filtering dan dilanjutkan proses tokenization, maka proses tersebut akan menghasilkan data seperti....

- \[ ] Semua Benar
- \[ ] 0 'alam','indah','sekali' <br> 1 'tempat','indah','nomor','sangat','rekomendasi
- \[x] 0 'alam','yang','indah' <br> 1 'tempat','terindah','nomor','sangat','direkomendasikan'
- \[ ] 0 'alam','yang','indah', '!' <br> 1 'tempat','indah','nomor', '1','sangat','rekomendasi', '!!!'
- \[ ] 0 alam yang indah <br> 1 tempat terindah nomor sangat direkomendasikan

#### Q9. Setelah diproses seperti soal nomor 8, kemudian dilakukan proses stemming. Sehingga proses stemming menghasilkan data...

- \[ ] 0 alam yang indah <br> 1 tempat terindah nomor sangat direkomendasikan
- \[ ] 0 'alam','yang','indah' <br> 1 'tempat','terindah','nomor','sangat','direkomendasikan'
- \[ ] 0 'alam','yang','indah', '!' <br> 1 'tempat','indah','nomor', '1','sangat','rekomendasi', '!!!'
- \[ ] Semua Benar
- \[x] 0 'alam', 'indah', 'sekali' <br> 1 'tempat', 'indah', 'nomor', 'sangat', 'rekomendasi'

#### Q10. Setelah diproses seperti soal nomor 9, kemudian dilakukan proses padding. Sehingga proses padidng menghasilkan data...

- \[ ] Semua Benar
- \[ ] 0 alam yang indah <br> 1 tempat terindah nomor sangat direkomendasikan
- \[ ] 0 'alam', 'indah', 'sekali', '' <br> 1 'tempat', 'indah', 'nomor', 'sangat', 'rekomendasi'
- \[ ] 0 'alam','yang', 'indah','!', '','' <br> 1 'tempat', 'terindah', 'nomor', '1', 'sangat', 'direkomendasikan', '!!!'
- \[x] 0 'alam', 'indah', 'sekali', '','' <br> 1 'tempat', 'indah', 'nomor', 'sangat', 'rekomendasi'