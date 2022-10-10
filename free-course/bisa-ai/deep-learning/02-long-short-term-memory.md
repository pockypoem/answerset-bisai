## Quiz for second syllabus

#### Q1. Kepanjangan dari LSTM adalah...

- \[ ] Long-Short Tech Memory
- \[x] Long-Short Term Memory
- \[ ] Long-Short Temporal Memory
- \[ ] Live-Short Term Memory
- \[ ] Long-Short Text Memory

#### Q2. Alasan LSTM diusulkan atau dikembangkan adalah...

- \[ ] Semua salah
- \[ ] Sebagai solusi untuk mengatasi terjadinya vanishing gradient pada RNN saat memproses data sequential yang pendek
- \[x] Sebagai solusi untuk mengatasi terjadinya vanishing gradient pada RNN saat memproses data sequential yang panjang
- \[ ] RNN tidak dapat digunakan untuk memproses data sequential yang pendek
- \[ ] RNN sudah ketinggalan jaman

#### Q3. LSTM merupakan modifikasi dari RNN yang mengandung 3 gate, yaitu...

- \[ ] Input gate, adding gate, output gate
- \[ ] Semua salah
- \[ ] Front gate, middle gate, back gate
- \[ ] Long gate, center gate, short gate
- \[x] Input gate, forget gate, output gate

#### Q4. Proses yang menggunakan gerbang sigmoid yang berfungsi untuk memutuskan informasi apa yang akan dibuang terjadi pada...gate.

- \[x] Forget
- \[ ] Short
- \[ ] Output
- \[ ] Long
- \[ ] Input

#### Q5. Saat proses pada gate yang berfungsi untuk memutuskan informasi yang akan dibuang, jika nilai yang dihasilkan dari gate tersebut adalah 0 , maka itu berarti informasi tersebut...

- \[x] Seluruhnya dibuang
- \[ ] Tidak dibuang
- \[ ] Dibuang sebagian
- \[ ] Tidak dapat diproses oleh gerbang tersebut
- \[ ] Error

#### Q6. Perhatikan gambar berikut ini. Untuk menentukan informasi baru yang akan digunakan pada konteks yang baru, dilibatkan sebuah gerbang dan satu lapisan, yaitu gerbang...dan lapisan...

- \[x] Input, tanh
- \[ ] Input, sigmoid
- \[ ] Output, tanh
- \[ ] Output, sigmoid
- \[ ] Semua salah

#### Q7. Fungsi aktivasi yang digunakan pada input gate adalah...

- \[x] Sigmoid, tanh
- \[ ] Tanh, tanh
- \[ ] Sigmoid
- \[ ] Sigmoid, sigmoid
- \[ ] Tanh

#### Q8. Fungsi aktivasi yang digunakan pada forget gate adalah...

- \[ ] Sigmoid, sigmoid
- \[ ] Tanh
- \[x] Sigmoid
- \[ ] Tanh, tanh
- \[ ] Sigmoid, tanh

#### Q9. Fungsi aktivasi yang digunakan pada output gate adalah...

- \[x] Sigmoid, tanh
- \[ ] Sigmoid
- \[ ] Sigmoid, sigmoid
- \[ ] Tanh, tanh
- \[ ] Tanh

#### Q10. Perhatikan gambar berikut. Proses yang terjadi pada gambar di atas adalah...

- \[ ] Semua salah
- \[x] Memperbaharui konteks lama menjadi konteks baru
- \[ ] Menentukan informasi baru yang akan digunakan pada konteks yang baru
- \[ ] Menentukan informasi mana yang akan dibuang
- \[ ] Menentukan output dari cell tersebut
