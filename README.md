# Deteksi Berita Palsu Menggunakan Naive Bayes

Kita harus berhati-hati dalam menelan sebuah informasi. Kita perlu mengetahui apakah informasi tersebut valid atau tidak. Sebuah informasi yang tidak valid atau berita palsu (HOAX) merupakan salah satu masalah yang saat ini masih eksis. Jika HOAX tersebut tersebar, maka ada banyak pihak yang akan menjadi korban. Sebuah berita palsu dapat dideteksi menggunakan machine learning. Pada projek ini, akan dilakukan deteksi berita palsu menggunakan naive bayes. Tipe naive bayes yang digunakan adalah naive bayes bernoulli karena tipe tersebut cocok untuk klasifikasi biner (0 dan 1).

Data dalam projek tersebut merupakan data teks. Data teks tersebut perlu diolah agar bisa digunakan dalam model naive bayes. Beberapa langkah dalam praproses teks adalah case folding (mengubah huruf besar menjadi huruf kecil serta menghapus karakter selain huruf), tokenizing (membagi setiap kalimat menjadi array kata), menghapus stopwords (kata hubung), dan stemming (mengambil kata dasar dari setiap kata). Setelah itu akan dilakukan ekstraksi fitur menggunakan TFIDF untuk mendapatkan matriks bobot yang akan digunakan dalam model naive bayes.

Model tersebut menghasilkan akurasi 79%, precision 74%, recall 86%, dan f1 score 80% 
