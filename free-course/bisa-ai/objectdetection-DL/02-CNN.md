## Quiz for second syllabus

#### Q1. Apa yang diberikan oleh flow_from_directory pada ImageGenerator?

- \[ ] Kemampuan untuk menentukan ukuran dari gambar training
- \[ ] Kemampuan untuk mendeteksi label gambar secara otomatis berdasarkan nama direktorinya
- \[ ] Kemampuan untuk melakukan splitting data
- \[ ] Kemampuan untuk membaca gambar untuk training dengan mudah
- \[x] Semuanya benar

#### Q2. Jika gambar berukuran 150x150 dilakukan konvolusi sebesar 3x3, maka hasil konvolusinya memiliki ukuran sebesar

- \[ ] 450x450
- \[ ] 150x150
- \[ ] 153x153
- \[x] 148x148
- \[ ] 145x145

#### Q3. Jika gambar berukuran 150x150 diberikan pooling sebesar 2x2, maka hasil gambarnya memiliki ukuran sebesar

- \[ ] 300x300
- \[x] 75x75
- \[ ] 145x145
- \[ ] 148x148
- \[ ] 149x149

#### Q4. Proses MaxPooling yaitu mengambil nilai ... dari semua piksel dibawah daerah filter

- \[x] Maksimum
- \[ ] Rata-rata
- \[ ] Absolute
- \[ ] Negatif
- \[ ] Minimum

#### Q5. Kita dapat melakukan augmentasi gambar pada Tensorflow dengan

- \[ ] Dengan train_test_split
- \[ ] Dengan API keras.augment
- \[ ] Dengan tf.augment API
- \[ ] Menulis plugin untuk me-extend tf.layers
- \[x] Menggunakan parameter pada ImageDataGenerator

#### Q6. Jika data training kita hanya memiliki gambar manusia dengan wajah ke arah kiri, tetapi kita ingin mengklasifikasikan orang dengan wajah ke arah kanan, bagaimana kita dapat menghindari overfitting?

- \[ ] Menggunakan parameter 'flip'
- \[ ] Menggunakan parameter 'flip' dan set 'horizontal'
- \[ ] Menggunakan parameter 'rescale'
- \[x] Menggunakan parameter 'horizontal_flip'
- \[ ] Menggunakan parameter 'flip_vertical'

#### Q7. Proses AveragePooling yaitu mengambil nilai ... dari semua piksel dibawah daerah filter

- \[ ] Negatif
- \[ ] Minimum
- \[x] Rata-rata
- \[ ] Absolute
- \[ ] Maksimum

#### Q8. Saat membuat CNN, kita harus melakukan .... sebelum masuk ke hidden layers

- \[ ] MaxPooling
- \[ ] Embedding
- \[x] Flatten
- \[ ] Dense
- \[ ] Dropout

#### Q9. CNN terdiri dari 2 proses, yaitu ....

- \[x] Feature learning dan classification
- \[ ] Classification dan detection
- \[ ] Tidak semuanya
- \[ ] Classification dan feature learning
- \[ ] Detection dan classification

#### Q10. Proses training pada model CNN ketika menggunakan augmentasi gambar akan menjadi ...

- \[ ] Lebih cepat
- \[ ] Gagal
- \[ ] Sama saja
- \[x] Lebih lambat
- \[ ] Tidak semuanya
