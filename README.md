# Prediksi_Saham
Selamat datang di repositori Prediksi Saham! Repositori ini merupakan tempat penyimpanan berupa data, dokumen, sumber kode, dan lain-lainya untuk analisis prediksi harga saham Mancheter United (MANU) sekaligus dijadikan sebagai wadah untuk penelitian tugas akhir.

### Latar Belakang
Dewasa ini, trend terhadap saham kian populer dikalangan masyarkat mulai dari iming-iming manis yang menjanjikan untuk cuan sampai pada penipuan yang merugikan bahkan tak jarang adu gengsian agar tidak jadi bahan gosipan. Adanya jaminan kemudahan dalam mengakses pasar saham juga menjadi pemikat agar masyarkat semakin tertarik untuk terjun ke dunia investasi. Lantas, fenomena ini menujukan bahwa pasar saham menjadi daya tarik utama dikalangan masyarakat umum sehingga mencerminkan minat yang meningkat terhadap investasi dan keuangan. 
Penting untuk memahami bahwa investasi saham memerlukan pengetahuan yang cukup, riset yang matang, dan perencanaan yang hati-hati. Hal ini dikarenakan saham bergerak secara non linier dan perubahan harga bisa terjadi begitu cepat yang dipengaruhi oleh banyak faktor seperti kondisi keuangan perusahaan, laju inflasi, tingkat suku bunga, dll. Oleh karena itu, penting untuk mengetahui dan mempelajari perilaku pergerakan harga saham dengan melakukan analisis prediksi harga saham sehingga berguna untuk mengetahui prospek dan alur investasi di masa mendatang. Berdasarkan latar belakang yang telah diuraikan tersebut maka dapat dilakukan penelitian dalam memprediksi harga saham dengan pendekatan menggunakan algoritma Support Vector Machine (SVM) sehingga dapat membantu para investor dalam melihat prospek suatu saham tertentu. Tidak hanya itu, metode algoritma yang digunakan juga diharapkan mampu menjawab permasalahan yang telah diuraikan serta dapat mengetahui tingkat keakuratan dari suatu model algoritma dalam memprediksi harga saham.

### Data
Pada penelitian ini data yang digunakan ialah data pergerakan harian harga saham Manchester United dengan kode saham yang terdaftar pada New York Stock Exchange (NYSC) ialah MANU. Data tersebut diperoleh melalui [yahoo finance](https://finance.yahoo.com/most-active/) dalam rentang waktu 5 tahun terakhir yakni pada 31 Oktober 2018 sampai 30 Oktober 2023 dengan jumlah data 1257. Pada data tersebut mengandung 7 atribut yang dikemas dalam format file csv yakni sebagai berikut:
1.	Date merupakan tanggal transaksi harga saham berlangsung.
2.	Open merupakan harga buka saham pada waktu tertentu dengan tipe data bilangan desimal.
3.	Close merupakan harga tutup saham pada waktu tertentu dengan tipe data bilangan desimal.
4.	High merupakan harga tertinggi saham pada waktu tertentu dengan tipe data bilangan desimal.
5.	Low merupakan harga terendah saham pada waktu tertentu dengan tipe data bilangan desimal.
6.	Adj Close merupakan harga tutup yang disesuaikan pada waktu tertentu dengan tipe data bilangan desimal.
7.	Volume merupakan jumlah saham yang diperdagangkan pada waktu tertentu dengan tipe data bilangan desimal.

### Tahapan Penelitian
1. Pengumpulan data.
2. Preprocessing.
3. Ekstraksi Fitur.
4. Pembagian data berupa data traning dan data testing.
5. Pemodelan.
6. Hasil & evaluasi.

### Sistem Folder
1. Folder Data berisikan file dataset.
2. Folder Documents berisikan file naskah penelitian beserta perhitungannya.
3. Folder Referensi berisikan file rujukan yang digunakan dalam penelitian.
4. Folder Source Code berisikan file code program.

### Run Code
1. Masuk Ke folder Source Code
2. Bukan terminal atau gitbash.
3. Ketik perintah ```source .venv/Scripts/activate``` untuk mengaktifkan & menjalankan venv pada project.
4. Ketik perintah ```pip install -r requirements.txt``` untuk menginstall dependencies.
4. Ketik perintah ```deactivate``` untuk menonatifkan venv pada project.

### Ucapan Terima Kasih
Kami ingin mengucapkan terima kasih kepada semua kontributor yang telah mendukung dan berpartisipasi dalam pengembangan proyek ini. Kontribusi Anda melalui kerja keras, ide kreatif, dan waktu yang Anda luangkan untuk proyek ini telah membantu kami mencapai tujuan kami dalam membuat proyek ini semakin terus berkembang. Kami sangat menghargai dedikasi Anda dalam membuat proyek ini menjadi lebih baik lagi.