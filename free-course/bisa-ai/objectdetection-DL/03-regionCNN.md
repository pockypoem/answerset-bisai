## Quiz for third syllabus

#### Q1. Mengapa kita tidak dapat menyelesaikan masalah deteksi objek menggunakan CNN biasa?

- \[x] Karena panjang dari output variabelnya tidak konstan / tidak pasti
- \[ ] Karena panjang dari input variabelnya tidak konstan / tidak pasti
- \[ ] Karena panjang dari output variabel cnnnya konstan / pasti
- \[ ] Tidak semuanya
- \[ ] Karena panjang dari input variabelnya konstan / pasti

#### Q2. Ross Girshick et al. mengusulkan metode yang menggunakan selective search untuk mengestrak .... region dari gambar.

- \[x] 2000
- \[ ] 200
- \[ ] 2
- \[ ] 0
- \[ ] 20

#### Q3. Region proposals adalah ...

- \[ ] 2000 region yang dihapus dari gambar menggunakan algoritma selective search
- \[ ] Tidak semuanya
- \[x] 2000 region yang diekstrak dari gambar menggunakan algoritma selective search
- \[ ] 2000 region yang diekstrak dari gambar menggunakan algoritma CNN
- \[ ] 2000 gambar yang diekstrak dari region menggunakan algoritma CNN

#### Q4. Selective search adalah ...

- \[x] Algoritma serakah yang menggabungkan wilayah tersegmentasi yang lebih kecil untuk menghasilkan region proposals
- \[ ] Tidak semuanya
- \[ ] Algoritma serakah yang mengeliminasi wilayah tersegmentasi yang lebih kecil untuk menghasilkan region proposals
- \[ ] Algoritma serakah yang menggabungkan wilayah tersegmentasi yang lebih besar untuk menghasilkan region proposals
- \[ ] Algoritma serakah yang mengeliminasi wilayah tersegmentasi yang lebih besar untuk menghasilkan region proposals

#### Q5. Algoritma selective search mengambil ... sebagai input dan menghasilkan ... sebagai output

- \[ ] Tidak semuanya
- \[ ] Region proposals dan gambar
- \[ ] Gambar dan region
- \[ ] Region dan gambar
- \[x] Gambar dan region proposals

#### Q6. Algoritma selective search memiliki keunggulan dibandingkan pembuatan proposal acak yaitu ...

- \[ ] Menghasilkan jumlah proposal melebihi 2000 dan memiliki daya ingat yang tinggi
- \[ ] Menghasilkan jumlah proposal melebihi 2000 dan memiliki daya ingat yang rendah
- \[x] Membatasi jumlah proposal hingga kira-kira 2000 dan memiliki daya ingat yang tinggi
- \[ ] Membatasi jumlah proposal hingga kira-kira 2000 dan memiliki daya ingat yang rendah
- \[ ] Tidak semuanya

#### Q7. Berapa fitur dimensi vektor yang dihasilkan dari 2000 region proposals yang dilengkungkan menjadi persegi dan dimasukkan ke dalam CNN?

- \[ ] 2000
- \[ ] 0
- \[ ] 2096
- \[x] 4096
- \[ ] 4000

#### Q8. CNN pada RCNN bertindak sebagai?

- \[ ] Ekstraktor fitur dan lapisan padat keluaran yang terdiri dari gambar
- \[ ] Tidak semuanya
- \[x] Ekstraktor fitur dan lapisan padat keluaran yang terdiri dari fitur yang diekstrasi dari gambar
- \[ ] Ekstraktor fitur dan lapisan padat masukan yang terdiri dari gambar
- \[ ] Ekstraktor fitur dan lapisan padat masukan yang terdiri dari fitur yang diekstrasi dari gambar

#### Q9. SVM pada RCNN digunakan untuk?

- \[ ] Mengklasifikasikan keberadaan keberadaan objek dalam gambar
- \[ ] Mengklasifikasikan objek dalam region proposals kandidat tersebut
- \[ ] Mengklasifikasikan keberadaan region proposals dalam gambar
- \[x] Mengklasifikasikan keberadaan objek dalam region proposals kandidat tersebut
- \[ ] Tidak semuanya

#### Q10. Manakah dibawah ini yang merupakan kelemahan / permasalahan dalam RCNN?

- \[x] Semuanya benar
- \[ ] Tidak dapat diimplementasikan secara live atau real time karena dibutuhkan waktu sekitar 47 detik untuk setiap gambar yang diuji
- \[ ] Membutuhkan waktu untuk mendeteksi gambar
- \[ ] Masih membutuhkan waktu yang banyak untuk melatih jaringan karena harus mengklasifikasikan 2000 region proposals per gambar.
- \[ ] Algoritma selective search adalah algoritma tetap. Oleh karena itu, tidak ada pembelajaran yang terjadi pada tahap itu yang menyebabkan lahirnya calon-calon region proposals yang buruk
