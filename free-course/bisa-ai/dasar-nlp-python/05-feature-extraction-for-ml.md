## Quiz for fifth syllabus

#### Q1. Tujuan dari proses ekstrasi fitur adalah

- \[x] Mengubah data ke dalam bentuk matematis
- \[ ] Semua Benar
- \[ ] Membersihkan data
- \[ ] Menghilangkan duplikasi data
- \[ ] Proses untuk membersihkan data teks

#### Q2. Berikut alasan mengapa ekstraksi fitur penting dilakukan, kecuali....

- \[ ] Semua Benar
- \[ ] Merepresentasikan teks agar informasi maksimum dapat ditangkap
- \[ ] Data teks tidak bisa direpresentasikan secara langsung
- \[ ] Komputer hanya mengerti data numerik
- \[x] Menghilangkan duplikasi data

#### Q3. Yang merupakan feature extraction untuk machine learning, kecuali....

- \[ ] N-Gram
- \[ ] Bag of Word
- \[ ] TF-IDF
- \[ ] Semua Benar
- \[x] Word2Vec

#### Q4. Hal yang tidak dapat dilakukan oleh feature extraction for machine learning adalah...

- \[ ] Semua Benar
- \[ ] Merepresentasikan teks ke dalam vektor
- \[ ] Mengubah teks ke dalam vector berdasarkan frekuensi kemunculannya
- \[x] Dapat menangkap makna semantik 
- \[ ] Mengubah data teks ke dalam bentuk matematis

#### Q5. Library yang dapat digunakan untuk mengubah dokumen teks ke dalam bentuk vector adalah...

- \[ ] Semua Benar
- \[ ] Numpy
- \[ ] NLTK
- \[x] CountVectorizer
- \[ ] Vectorizer

#### Q6. Berikut hal yang tidak benar terkait bag of word adalah....

- \[ ] Semua Benar
- \[ ] Memberikan kemungkinan menghilangkan frasa yang jarang muncul tapi penting
- \[ ] Hanya mengandalkan jumlah kata dalam suatu dokumen
- \[x] Dapat membangun ukuran kosakata < fitur maksimal
- \[ ] Representasi data teks menggunakan angka

#### Q7. Teknik membatasi data pada feature extraction agar menghapus data yang sering muncul dan melewati ambang batas karena tidak penting, serta menghapus data yang jarang muncul lebih sedikit dari ambang batas disebut...

- \[ ] Bag of Word
- \[ ] Semua Benar
- \[ ] Max_feature
- \[ ] Count Vectorizer
- \[x] Max_df dan Min_df

#### Q8. Pernyataan yang salah berdasarkan kode program di bawah ini adalah... <br> ```CountVectorizer(analyzer='word', ngram_range=(1,3), max_df = 3, min_df=2)```

- \[ ] N-gram digunakan pada kode tersebut
- \[x] Max_feature pada kode tersebut sama dengan 3
- \[ ] Frekuensi kemunculan kata/frasa kurang dari 2 akan dihapus
- \[ ] Semua Benar
- \[ ] Frekuensi kemunculan kata/frasa lebih dari 3 akan dihapus

#### Q9. Library untuk menerapkan TF-IDF adalah...

- \[x] TdidfVectorizer
- \[ ] TfVectorizer dan IdfVectorizer
- \[ ] Tf-IdfVectorizer
- \[ ] TfIdfFeatureVectorizer
- \[ ] Semua Benar

#### Q10. Berikut pernyataan yang salah terkait TF-IDF...

- \[ ] Semua Benar
- \[ ] TF membertikan lebih banyak bobot untuk istilah yang sangat sering muncul
- \[x] IDF merupakan Identification Document Frequency
- \[ ] TF merupakan Term Frequency
- \[ ] IDF memberikan lebih banyak bobot pada istilah yang lebih bermakna