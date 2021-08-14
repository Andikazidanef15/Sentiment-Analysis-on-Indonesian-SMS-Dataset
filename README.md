# Sentiment-Analysis-on-Indonesian-SMS-Dataset

Sebagian besar dari kita pasti memiliki telepon genggam/HP. Di dalamnya terdapat fitur pesan SMS yang berisi pesan-pesan penting seperti pengumuman terkait COVID-19 yang diumumkan oleh instansi Kementerian Kesehatan, iklan terkait promo dari layanan yang kita gunakan ataupun pesan dari rekan kita apabila ia tidak menggunakan WhatsApp. Namun, seiring waktu pesan spam yang masuk di SMS kita semakin banyak, pesan-pesan hadiah menggiurkan seperti jackpot Rp 100 juta, mobil gratis dan lain-lain tentu menarik perhatian pengguna dan apabila tidak cermat maka ada kemungkinan pengguna tersebut ditipu. Untungnya, dengan algoritma yang tersedia di HP kita, kemungkinan untuk mendapatkan pesan spam bisa diminimalisir. Lalu, bagaimana algoritma itu dapat memprediksi mana yang termasuk pesan spam dan mana yang tidak? Algoritma tersebut tentunya menggunakan ilmu analisis sentimen.

Analisis sentimen adalah analisis yang dilakukan untuk menentukan sentimen yang terkandung dalam suatu teks. Biasanya untuk menentukan sentimen dari suatu teks diperlukan ilmu Natural Language Processing (NLP) untuk mengubah teks menjadi bentuk yang lebih sederhana dan dapat dipahami oleh algoritma machine learning sehingga dapat menentukan prediksi sentimen yang terkandung dalam teks tersebut.

Dalam kesempatan kali ini, aku menggunakan dataset berisi SMS spam berbahasa Indonesia yang diperoleh dari link 
https://github.com/kmkurn/id-nlp-resource

Di github tersebut juga tersedia beberapa dataset yang dapat kalian gunakan untuk text mining dan tugas NLP lainnya.

Penjelasan label:

* 0 : SMS Normal (pesan antar rekan/keluarga)
* 1 : Pesan Spam
* 2 : Promo/Iklan
