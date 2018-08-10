# Belajar tentang A/B Testing
Pada tulisan ini anda akan mengetahui bagaimana melakukan sebuah eksperimen untuk memberikan nilai optimisasi dari 2 elemen/fitur sehingga kita dapat menentukan yang terbaik, eksperimen ini disebut dengan A/B Testing, A/B Testing dapat dilakukan pada bidang bisnis, teknologi, retail, dan lain - lain. Pada penjelasan ini kita diharapkan mampu mendesign atau merumuskan masalah dan membuat sebuah metrik penilaian terhadap eksperimen. Tujuan besar untuk melakukan A/B Testing adalah untuk menebak atau mengetahui perubahan yang terjadi terhadap ekseperimen yang kita lakukan untuk mengoptimalkan keputusan bisnis dari suatu pernyataan "kami pikir" menjadi "kami tahu".\
**1. Pengertian A/B Testing**\
<a href="https://ibb.co/cucV6K"><img src="https://preview.ibb.co/nvUcmK/gambar.jpg" alt="gambar" border="0"></a>

A/B Testing adalah suatu metode yang digunakan untuk menguji 
suatu performa, misalkan sebuah website atau campaign dengan 
cara membandingkan suatu responn dari masing - masing variasi. Pada intinya dalam memahami pengertian dasar dari A/B Testing seperti anda memiliki dua versi dari suatu elemen (A / B) yang ingin anda uji dan anda juga sudah mendefinisikan suatu metrik(ukuran penilaian) dari kedua elemen tersebut. Variasi desain 
ini nantinya akan digunakan  untuk melihat apakah setiap perubahan desain memang membawa peningkatan (atau pengurangan) terhadap conversion rate (seperti perubahan jumlah signup, pembelian, dll). Tidak semua eksperimen dapat diterapkan A/B Testing, terdapat beberapa faktor yang menyebabkan A/B Testing tidak dapat dilakukan, diantaranya : dalam melakukan A/B Testing sebaiknya orang yang akan memberikan penilaian sudah memiliki pengalaman atau sebelumnya pernah menggunakan fitur / produk yang akan kita lakukan eksperimen A/B Testing tersebut, karena bagi orang yang belum pernah menggunakannya akan memberikan penilaian yang kurang tepat terhadap perubahan yang kita lakukan sehingga akan memberikan keputusannya tidak kuat atau lemah.
<a href="https://ibb.co/d1s8RK"><img src="https://preview.ibb.co/bLZcLe/D2.jpg" alt="D2" border="0"></a>

**2. Fungsi A/B Testing**\
a. Web development : untuk menguji suatu fitur pada website yang
akan dibuat untuk mendapatkan respon dari pengguna dengan
dibandingkan dengan fitur yang telah ada sebelumnya.\
b. Marketing : untuk menguji layanan service pada customer untuk
mendapatkan respon atau penilaian customer terhadap produk dengan
dibandingkan dengan layanan service yang telah ada pada produk 
yang sama. 

**3. Cara Kerja A/B Testing pada fungsi Web development**\
Secara umum, berikut ini adalah siklus dari A/B testing pada
fungsi Web development :

* Memutuskan apa yang ingin kamu ubah

* Menggunakan tool A/B testing otomatis untuk melakukan implementasi perubahan secara visual.

* Menggunakan perubahan tersebut selama rentang waktu tertentu agar kita mendapatkan sejumlah angka pengunjung sebagai sampel.

* Tool A/B testing akan menyajikan dua variasi halaman web kepada pengunjung yang berkunjung pada rentang waktu yang sama (tool ini tidak menguji variasi secara bergantian.)

* Ketika data yang dikumpulkan telah dirasa cukup, tool A/B testing akan melaporkan apakah terdapat perubahan yang signifikan dari conversion rate di tiap halaman web. Apabila terdapat perubahan, giliranmu memutuskan untuk mengubah kode atau desain original dari sebuah halaman web menjadi yang kode dan desain yang telah melalui A/B testing atau tidak.

* Ulangi seluruh langkah di atas hingga kamu atau perusahaanmu bangk rut — atau diakuisisi.
Terdapat tiga tool A/B testing yang umum digunakan: Optimizely, VWO, dan Google Optimize. Tool yang terakhir ini gratis, memiliki fitur penuh, dan terintegrasi dengan Google Analytics. Saya merekomendasikan tool ini.
<a href="https://ibb.co/em01fe"><img src="https://preview.ibb.co/hbkCmK/D1.png" alt="D1" border="0"></a>

**4. Langkah - Langkah dan Penjelasan A/B Testing :**\
**Step 1 : Menentukan dan memilih karakteristik metrik untuk melakukan uji kenormalan dan evaluasi**\
Karakteristik metrik yang kita digunakan untuk uji kenormalan ini disebut invariant metrik. Invariant metrik yang kita gunakan ini tidak terpengaruh terhadap percobaan yang kita lakukan, sedangkan metrik evaluasi yang kita pilih digunakan untuk mengukur variasi mana yang lebih baik.\
**Stetp 2 : Pilih tingkat signifikansi, Uji statistik dan tingkat signifikansi praktis**\
Biasanya tingkat signifikansi yang digunakan adalah 0,05. Tingkat signifikansi praktis bervariasi bergantung pada masing-masing tes, ini akan memberikan kita tentang seberapa banyak perubahan yang dideteksi oleh pengujian yang membuat kita benar-benar ingin meluncurkan perubahan atau mungkin tidak ingin meluncurkan perubahan bahkan jika pengujian itu signifikan secara statistik karena kita perlu mempertimbangkan dampak perubahan bisnis, apakah bermanfaat untuk diluncurkan mengingat biaya rekayasa, dukungan pelanggan atau masalah penjualan, dan biaya peluang.\
**Step 3 : Menghitung ukuran sampel yang kita butuhkan**\
Perlu untuk mempertimbangkan dalam pemilihan metrik pemilihan populasi ke dalam eksperimen yang kita lakukan karena semuanya memengaruhi variabilitas metrik, kemudian putuskan ukuran sampel eksperimen yang akan kita butuhkan.\
**Step 4 : Bagi ukuran sampel menjadi sampel/grup Kontrol dan sampel/grup eksperimen**\
Ukuran sampel yang telah kita tentukan akan dibagi menjadi kelompok kontrol dan kelompok eksperimen kemudian lakukan eksperimen A/B Testing pada kelompok eksperimen terhadap fitur/produk A dan fitur/produk B.\
**Step 5 : Menganalisis hasil dan menarik kesimpulan**\
Berikut ini beberapa hal yang perlu dilakukan dalam mengakhirin langkah A/B Testing :
* *Periksa hasil Uji kenormalan*
* *Analisis hasil eksperimen*
* *Menarik kesimpulan*

**5. Melakukan simulasi membuat metrik perhitungan dalam A/B Testing**\
Dalam memahami lebih lanjut mengenai metrik - metrik dalam melakukan A/B Testing, kita akan membuat simulasi melakukan A/B Testing serta membuat metrik - metriknya juga, berikut simulasinya :
Eksperimen : Kita akan melakukan eksperimen terkait **"Siswa yang mengambil course di Udacity akan mendapatkan pekerjaan"**
Ada beberapa metrik yang akan dilakukan eksperimen dengan A/B Testing terhadap beberapa langka - langkah dari mulai calon siswa melakukan sign up ke webiste udacity, melakukan registrasi, memilih course yang akan diambil sampai membayar dan mengikuti course higga selesai hingga mereka mendapatkan pekerjaan sesuai dengan course yang mereka ambil. Berikut ini gambaran metrik yang dapat dibuat
<a href="https://ibb.co/gkTx6U"><img src="https://preview.ibb.co/dwim0p/metrik.jpg" alt="metrik" border="0"></a>
dengan goals atau tujuan dari semua proses tersebut dengan A/B Testing adalah untuk **"mendapatkan tampilan dan layanan terbaik yang dapat diberikan oleh website Udacity"**.


