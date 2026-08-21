**BAGIAN I MEMAHAMI SISTEM INFORMASI**

**Bab 2**

**Anatomi Sistem Informasi**

# **Peta bab**

**Sub-CPMK yang diampu.** Mampu menjelaskan konsep sistem, data, informasi, komponen sistem informasi, serta peran dan profesi di bidang sistem informasi.

Bab 1 memperkenalkan sistem sebagai cara memandang. Bab ini membedah isinya. Kalau Bab 1 mengajarkan cara menarik batas di sekeliling sesuatu, bab ini mengajarkan apa yang Anda temukan setelah batas itu ditarik.

Setelah membaca bab ini Anda akan mampu:

1.  menyebutkan empat komponen sistem informasi dan menjelaskan peran masing-masing;

2.  menjelaskan mengapa keempat komponen itu berkedudukan setara;

3.  menjelaskan arti sistem sosio-teknis dan akibatnya bagi cara memandang kegagalan;

4.  membongkar sebuah layanan digital yang Anda pakai sehari-hari menjadi empat komponen;

5.  menunjuk komponen yang paling bertanggung jawab atas sebuah kegagalan, disertai alasan.

**Bab prasyarat.** Bab 1 tentang pengertian sistem, batas sistem, dan perbedaan data dengan informasi.

**Kata kunci.** Komponen sistem informasi, manusia, proses, data, teknologi, sistem sosio-teknis, penahan, titik lemah.

**Yang akan Anda hasilkan.** Satu lembar pembongkaran sebuah layanan menjadi empat komponen, disertai penunjukan titik lemahnya dan alasan penunjukan itu.

# **Aplikasinya jalan, pesanannya tidak sampai**

Anda memesan makanan lewat aplikasi pada pukul setengah satu siang. Semuanya berjalan mulus di layar. Pesanan diterima. Pembayaran berhasil. Seorang kurir ditugaskan, namanya muncul lengkap dengan foto dan nomor kendaraan. Titik pada peta bergerak menuju rumah makan, berhenti sebentar, lalu bergerak ke arah kos Anda.

Pukul satu lewat sepuluh, status berubah menjadi “Pesanan selesai”. Peta menghilang. Layar mengucapkan terima kasih dan meminta Anda untuk memberi bintang.

Makanannya tidak pernah sampai.

Anda menghubungi layanan bantuan. Setelah menunggu, jawabannya datang: menurut catatan sistem, pesanan sudah diserahkan pada pukul satu lewat sepuluh.

Berhentilah sejenak dan perhatikan satu hal. Tidak ada satu baris kode pun yang keliru dalam cerita ini. Aplikasi bekerja persis seperti yang dirancang. Pembayaran tercatat dengan benar. Peta menunjukkan lokasi yang benar. Basis data menyimpan apa yang seharusnya disimpan. Setiap bagian teknis berjalan sempurna, dan pesanan Anda tetap hilang.

Kalau seluruh bagian teknisnya benar tetapi hasilnya salah, berarti ada bagian lain dari sistem itu yang belum Anda perhitungkan. Bab ini tentang bagian-bagian tersebut.

# **2.1 Empat komponen**

| *Sebuah sistem informasi tersusun atas empat komponen: manusia, proses, data, dan teknologi. Keempatnya harus ada. Kalau salah satu tidak ada, yang Anda hadapi bukan sistem informasi.* |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

Cara termudah mengenali keempat komponen adalah lewat pertanyaan yang dijawab masing-masing.

<img src="asset/bab-02-gambar-1.png" style="width:4.76042in;height:2.375in" />

**Gambar 2.1 Empat komponen sistem informasi**

**Manusia** menjawab pertanyaan siapa. Siapa yang mengerjakan, siapa yang memakai hasilnya, dan siapa yang menanggung akibat kalau hasilnya keliru. Ketiga peran itu sering dipegang orang yang berbeda, dan perbedaan itulah yang membuat banyak sistem sulit diperbaiki.

**Proses** menjawab pertanyaan bagaimana. Urutan kerja apa yang disepakati, siapa mengerjakan apa lebih dahulu, dan apa yang dilakukan ketika keadaan tidak berjalan seperti biasa. Proses tidak selalu tertulis. Sebagian besar proses hidup sebagai kebiasaan yang tidak pernah dibicarakan.

**Data** menjawab pertanyaan apa yang dicatat. Perhatikan bahwa pertanyaannya bukan apa yang terjadi, melainkan apa yang dicatat. Perbedaan antara keduanya adalah pokok bahasan Bab 8, dan sudah cukup penting untuk disadari sejak sekarang.

**Teknologi** menjawab pertanyaan dengan alat apa. Perangkat lunak, perangkat keras, jaringan, dan segala sesuatu yang dipakai untuk menjalankan tiga komponen sebelumnya. Perhatikan urutannya: teknologi disebut terakhir bukan karena tidak penting, melainkan karena ia melayani ketiga komponen lain, bukan sebaliknya.

Urutan penyebutan dalam buku ini juga bukan urutan kepentingan. Manusia disebut lebih dahulu semata-mata karena komponen itulah yang paling sering dilupakan oleh orang yang berlatar teknik.

# **2.2 Mengapa keempatnya setara**

Pernyataan bahwa keempat komponen setara terdengar seperti basa-basi yang sopan. Ia bukan. Pernyataan itu punya akibat yang dapat diuji.

Sebuah sistem informasi bekerja hanya kalau keempat komponennya sepakat. Data yang benar tidak menolong kalau tidak ada yang membacanya. Proses yang rapi tidak menolong kalau orang yang menjalankannya tidak mengerti mengapa langkah itu ada. Teknologi yang canggih tidak menolong kalau data yang masuk ke dalamnya sudah salah sejak awal. Setiap komponen dapat membatalkan kerja ketiga komponen lainnya.

Bagi mahasiswa Teknik Informatika, komponen teknologi hampir selalu terasa paling penting. Ada dua sebab yang masuk akal. Pertama, itulah yang Anda pelajari selama delapan semester ke depan, sehingga wajar kalau ia terasa paling nyata. Kedua, kegagalan teknologi paling mudah dilihat. Ketika aplikasi berhenti, semua orang tahu ada yang rusak.

Justru karena mudah dilihat, kegagalan teknologi adalah yang paling cepat diperbaiki. Yang mahal bukan kegagalan yang kelihatan, melainkan kegagalan yang tidak ada seorang pun merasa memilikinya. Pesanan yang hilang pada cerita pembuka termasuk jenis yang kedua. Tidak ada pihak yang merasa telah berbuat salah, dan karena itu tidak ada yang merasa perlu memperbaiki apa pun.

# **2.3 Sistem sosio-teknis**

| *Sistem sosio-teknis adalah sistem yang bagian teknisnya dan bagian manusianya tidak dapat dirancang secara terpisah, sebab perubahan pada salah satunya selalu mengubah yang lain.* |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

Istilah ini berasal dari kajian organisasi dan sudah lama dipakai dalam bidang sistem informasi. Isinya sederhana tetapi akibatnya jauh.

Ambil sebuah contoh yang akan Anda temui lagi pada Bab 8. Sebuah organisasi menambahkan satu kolom wajib pada formulir yang harus diisi petugas. Dari sisi teknis, perubahan itu kecil sekali: satu kolom baru pada basis data, satu kotak isian pada layar. Dari sisi manusia, perubahan itu berarti setiap petugas kini harus berhenti sejenak dan memikirkan sesuatu yang sebelumnya tidak perlu dipikirkan, puluhan kali sehari.

Kalau petugas menganggap kolom itu tidak masuk akal, ia akan mengisinya seadanya agar formulir dapat disimpan. Hasilnya adalah kolom yang selalu terisi dan hampir selalu keliru. Perubahan teknis yang kecil menghasilkan kerusakan data yang besar, dan tidak ada pengujian perangkat lunak yang dapat menangkapnya.

Dari sini muncul akibat yang perlu Anda bawa sepanjang kuliah: pertanyaan “apakah sistemnya benar” tidak dapat dijawab hanya dengan menguji perangkat lunaknya. Pengujian memeriksa apakah perangkat lunak berperilaku sesuai rancangan. Ia tidak memeriksa apakah rancangan itu sesuai dengan pekerjaan yang sebenarnya dikerjakan orang.

Ada akibat kedua yang lebih pribadi. Kelak, pekerjaan Anda tidak akan dinilai dari apakah kodenya berjalan, melainkan dari apakah pekerjaan orang lain menjadi lebih baik karenanya. Perbedaan antara kedua ukuran itu adalah jarak antara programmer dan orang yang dipercaya merancang sistem.

# **2.4 Empat cara sebuah sistem gagal**

Karena ada empat komponen, ada empat cara pokok sebuah sistem informasi gagal.

<img src="asset/bab-02-gambar-2.png" style="width:4.76042in;height:2.70833in" />

**Gambar 2.2 Empat cara sebuah sistem informasi gagal**

Dalam kenyataan, kegagalan jarang berdiri sendiri. Yang lazim terjadi adalah satu komponen gagal, lalu ketiga komponen lainnya tidak menahannya. Gagasan menahan ini perlu diberi nama sendiri karena akan dipakai berkali-kali.

| *Penahan adalah bagian dari sistem yang mencegah kegagalan satu komponen berubah menjadi kegagalan seluruh sistem.* |
|---------------------------------------------------------------------------------------------------------------------|

Kembali ke pesanan yang hilang. Kegagalan bermula pada komponen manusia: seseorang menandai pesanan sebagai selesai padahal belum menyerahkannya. Kegagalan semacam itu akan selalu ada, sebab manusia tidak dapat dijamin. Pertanyaan yang benar bukan bagaimana mencegahnya, melainkan apa yang menahannya.

Pada layanan tersebut, ternyata tidak ada yang menahan. Proses tidak menuntut bukti apa pun dari pihak penerima. Data hanya mencatat bahwa sebuah tombol ditekan, bukan bahwa sesuatu berpindah tangan. Teknologi bekerja sempurna dan justru itu yang membuat keadaan lebih buruk, sebab catatan yang rapi memberi kesan bahwa semuanya berjalan benar.

Sebagian layanan pesan-antar menambahkan penahan berupa kode empat angka yang harus disebutkan pelanggan sebelum kurir dapat menutup pesanan. Perhatikan apa yang sebenarnya diubah oleh penahan itu. Bukan teknologinya, melainkan prosesnya. Teknologi hanya menjalankan perubahan proses tersebut.

# **2.5 Membongkar sebuah layanan**

Bagian ini memberi cara kerja yang dapat Anda ulang untuk layanan apa pun. Empat langkah, dikerjakan berurutan.

## **Langkah 1 Tetapkan layanan dan batasnya**

Pakai cara menarik batas dari Bab 1. Sebutkan dengan kalimat lengkap apa yang termasuk di dalam dan apa yang berada di luar. Layanan pesan-antar makanan, misalnya, mencakup pemesanan sampai penyerahannya, tetapi tidak mencakup cara rumah makan memasak makanannya.

## **Langkah 2 Daftar manusianya**

Tulis semua orang yang menyentuh layanan itu, dan bedakan tiga peran: **siapa yang memakai**, **siapa yang mengerjakan**, **siapa yang menanggung akibat kalau terjadi kesalahan**. Peran ketiga paling sering terlewat, padahal justru peran itu yang menentukan apakah sebuah masalah akan diperbaiki atau dibiarkan.

## **Langkah 3 Daftar prosesnya**

Tuliskan urutan kerjanya sebagai kalimat, belum berupa gambar. Menggambar proses adalah pekerjaan Bab 7 dan menuntut alat yang belum Anda punya. Untuk sekarang, empat sampai delapan kalimat sudah cukup.

## **Langkah 4 Daftar data dan teknologinya**

Untuk data, tanyakan apa yang tercatat dan bertahan setelah kejadiannya lewat. Untuk teknologi, sebutkan alatnya menurut fungsi, bukan menurut mereknya. Tulis “layanan peta”, bukan nama produk peta tertentu. Nama produk berubah, fungsi bertahan lebih lama.

Hasil keempat langkah itu untuk layanan pada cerita pembuka tampak seperti berikut.

<img src="asset/bab-02-gambar-3.png" style="width:4.76042in;height:2.67708in" />

**Gambar 2.3 Hasil pembongkaran layanan pesan-antar makanan**

Setelah pembongkaran selesai, barulah titik lemah dapat ditunjuk. Caranya dengan satu pertanyaan yang diajukan kepada setiap komponen: kalau komponen ini gagal, apa yang menahannya? Komponen yang tidak punya penahan adalah titik lemah sistem tersebut.

# **2.6 Yang tidak dibahas di sini**

Beberapa hal yang tampaknya termasuk anatomi sistem informasi sengaja tidak dibahas dalam bab ini.

| **Hal**                                      | **Tempatnya**              | **Alasan**                                                                       |
|----------------------------------------------|----------------------------|----------------------------------------------------------------------------------|
| Perangkat keras dan arsitektur komputer      | Dasar Sistem Komputer      | Di sini teknologi hanya dipandang menurut fungsinya, bukan menurut cara kerjanya |
| Bahasa pemrograman dan cara membuat aplikasi | Konsep Pemrograman         | Bab ini melatih cara memandang, bukan cara membuat                               |
| Perancangan tampilan dan pengalaman pengguna | Desain Pengalaman Pengguna | Menuntut alat yang belum tersedia pada semester ini                              |
| Perancangan basis data                       | Basis Data                 | Di sini data dipandang sebagai apa yang dicatat, bukan bagaimana menyimpannya    |

Pembatasan ini bukan karena hal-hal tersebut kurang penting. Sebagian besar justru akan memakan waktu Anda jauh lebih banyak daripada mata kuliah ini. Pembatasan dilakukan karena bab ini melatih satu keterampilan tunggal, yaitu memandang sesuatu sebagai sistem yang terdiri atas empat komponen, dan keterampilan itu justru menjadi kabur kalau dicampur dengan cara membuat.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Di balik layar: apa yang terjadi ketika tombol “pesanan selesai” ditekan</strong></p>
<p>Dari sisi sistem, peristiwa yang terjadi jauh lebih sedikit daripada yang dibayangkan pelanggan.</p>
<p>Sistem tidak tahu apa pun mengenai makanan. Ia tidak tahu apakah kantong plastik berpindah tangan, apakah pintu kos terbuka, atau apakah ada orang di sana. Yang diketahuinya hanyalah bahwa sebuah tombol ditekan pada waktu tertentu, oleh akun tertentu, dari titik koordinat tertentu.</p>
<p>Ketiga keterangan itu tampak meyakinkan. Waktu dan koordinatnya tepat, akunnya benar, dan memang berada di dekat alamat tujuan. Persoalannya, ketiganya sama sekali tidak membuktikan bahwa makanan tersebut sudah diserahkan. Yang terbukti hanyalah bahwa seseorang berada di dekat alamat itu dan menekan tombol.</p>
<p>Jarak antara “tombol ditekan” dan “makanan diterima” inilah yang harus diisi oleh penahan. Kode empat angka, tanda tangan, atau foto serah terima adalah cara-cara untuk mengisi jarak tersebut. Semuanya menambah pekerjaan bagi kurir, dan itulah sebabnya tidak semua layanan memakainya.</p>
<p>Simpan pengamatan ini. Pada Bab 7 Anda akan menggambar proses semacam ini, dan pada Bab 8 Anda akan menanyakan data apa yang perlu dicatat agar sengketa seperti tadi dapat diselesaikan.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Salah kaprah</strong></p>
<p><strong>“Sistem informasi adalah aplikasi.”</strong> Aplikasi adalah bagian dari komponen teknologi, dan hanya sebagian. Sebuah sistem informasi dapat berjalan tanpa aplikasi sama sekali. Buku tulis, kesepakatan kerja, dan orang yang menjalankannya sudah memenuhi keempat komponen.</p>
<p><strong>“Kalau perangkat lunaknya sudah diuji, sistemnya sudah benar.”</strong> Pengujian memeriksa apakah perangkat lunak berperilaku sesuai rancangan. Ia tidak memeriksa apakah rancangan itu sesuai dengan pekerjaan yang sebenarnya. Dua hal yang berbeda, dan yang kedua tidak dapat diperiksa dari balik meja.</p>
<p><strong>“Manusia adalah komponen yang lemah, jadi sebaiknya dikurangi.”</strong> Manusia memang tidak dapat dijamin. Ia juga satu-satunya komponen yang dapat mengenali keadaan yang tidak pernah diperkirakan perancang. Mengurangi peran manusia tanpa menambah penahan lain memindahkan letak kegagalan, bukan menghilangkannya.</p></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

# **Studi kasus terpandu: pembayaran dengan kode QR di kantin**

Bagian ini menjalankan keempat langkah pada Subbab 2.5 dari awal sampai akhir, memakai layanan yang hampir pasti Anda pakai setiap minggu.

## **Narasi**

Kantin kampus memasang selembar kertas berisi kode QR di setiap meja penjual. Pembeli memindai kode itu dengan aplikasi pembayaran di teleponnya, mengetik sendiri jumlah yang harus dibayar, menekan tombol bayar, lalu menunjukkan layar bertuliskan “Pembayaran berhasil” kepada penjual. Penjual melihat sekilas, mengangguk, dan pembeli pergi.

Pada jam istirahat, antrean panjang dan penjual melayani beberapa pembeli sekaligus sambil memasak.

## **Langkah 1 Batas**

**Termasuk:** dari pembeli memindai kode sampai penjual menganggap pembayaran diterima. **Tidak termasuk:** penyediaan makanan, dan pemindahan uang dari penyedia layanan pembayaran ke rekening penjual.

## **Langkah 2 Manusia**

| **Peran**         | **Siapa**                                        |
|-------------------|--------------------------------------------------|
| Memakai           | Pembeli                                          |
| Mengerjakan       | Pembeli mengetik jumlah, penjual memeriksa layar |
| Menanggung akibat | Penjual, kalau jumlah yang masuk ternyata kurang |

Perhatikan baris ketiga. Orang yang menanggung akibat kesalahan bukan orang yang melakukan pekerjaan yang paling menentukan. Pembeli yang mengetik jumlah, penjual yang menanggung. Ketidakseimbangan semacam ini adalah petunjuk kuat bahwa ada titik lemah di dekat situ.

## **Langkah 3 Proses**

- Pembeli memindai kode QR pada meja penjual.

- Pembeli mengetik sendiri jumlah yang harus dibayar.

- Pembeli menekan tombol bayar dan memasukkan kata sandinya.

- Pembeli menunjukkan layar yang bertuliskan berhasil kepada penjual.

- Penjual melihat layar itu sekilas dan mempersilakan pembeli pergi.

## **Langkah 4 Data dan teknologi**

**Data:** jumlah pembayaran, waktu pembayaran, nama pengirim, nomor rujukan transaksi. Seluruhnya tercatat pada sistem penyedia layanan pembayaran, dan penjual dapat melihatnya melalui aplikasi di teleponnya sendiri.

**Teknologi:** kode QR tercetak, aplikasi pembayaran pada telepon pembeli, aplikasi pedagang pada telepon penjual, jaringan seluler, sistem penyedia layanan pembayaran.

## **Menunjuk titik lemah**

Ajukan pertanyaan penahan kepada setiap komponen.

| **Komponen** | **Kalau gagal**                                      | **Apa yang menahannya**                              |
|--------------|------------------------------------------------------|------------------------------------------------------|
| Teknologi    | Jaringan putus, pembayaran tidak terkirim            | Ada. Aplikasi memberi tahu kegagalan secara langsung |
| Data         | Jumlah yang tercatat keliru                          | Ada. Riwayat transaksi tersimpan dan dapat diperiksa |
| Manusia      | Pembeli mengetik jumlah lebih kecil dari seharusnya  | Tidak ada                                            |
| Proses       | Penjual tidak memeriksa apa pun selain layar pembeli | Tidak ada                                            |

Titik lemahnya jelas: dua komponen tanpa penahan, dan keduanya saling menguatkan. Layar yang ditunjukkan pembeli berasal dari telepon pembeli sendiri, sehingga penjual sebenarnya sedang memeriksa keterangan yang diberikan oleh pihak yang paling diuntungkan bila keterangan itu keliru.

Perhatikan juga bahwa data sebenarnya ada. Riwayat transaksi tersimpan lengkap di aplikasi pedagang. Yang tidak ada adalah langkah dalam proses yang meminta penjual membukanya. Ini pola yang akan berulang sepanjang buku: data yang tersedia tetapi tidak dipakai sama saja dengan data yang tidak ada.

## **Usulan perbaikan dan ongkosnya**

Perbaikan yang paling murah bukan perbaikan teknologi. Penjual cukup memeriksa notifikasi masuk pada teleponnya sendiri, bukan layar pembeli. Tidak ada perangkat baru yang harus dibeli dan tidak ada perangkat lunak yang harus dibuat.

Ongkosnya tetap ada dan harus disebutkan. Penjual harus memegang telepon sambil memasak, dan pada jam istirahat itu memperlambat antrean beberapa detik untuk setiap pembeli. Beberapa detik dikalikan seratus pembeli menjadi persoalan nyata bagi penjual, meskipun terdengar kecil bagi perancang.

## **Kritik atas hasil sendiri**

Analisis di atas mengandung sekurang-kurangnya dua kelemahan yang perlu dinyatakan.

1.  Analisis ini mengandaikan pembeli yang berniat curang. Kemungkinan besar sebagian terbesar kesalahan jumlah tidak disengaja, misalnya salah menekan angka atau salah mengingat harga. Kedua sebab itu menuntut penahan yang berbeda, dan untuk membedakannya diperlukan data yang tidak dikumpulkan siapa pun.

2.  Analisis ini tidak menghitung berapa sering kejadian itu sebenarnya terjadi. Tanpa angka, tidak ada dasar untuk menilai apakah perbaikan sepadan dengan ongkosnya. Menyusun angka semacam itu adalah pekerjaan Bab 8.

Menyebutkan kedua kelemahan tersebut bukan merupakan tanda pekerjaan yang lemah. Analisis yang menyembunyikan andaiannya jauh lebih berbahaya daripada analisis yang menyatakannya, sebab orang yang membacanya akan mengira hasilnya lebih pasti daripada yang sebenarnya.

# **Rangkuman**

- Sistem informasi tersusun atas 4 komponen: manusia, proses, data, dan teknologi. Keempatnya harus ada.

- Keempat komponen berkedudukan setara, dalam arti masing-masing dapat membatalkan kerja ketiga lainnya.

- Teknologi terasa paling penting karena kegagalannya paling mudah terlihat. Justru karena itu, ia paling cepat diperbaiki.

- Sistem sosio-teknis adalah sistem yang bagian teknis dan bagian manusianya tidak dapat dirancang terpisah.

- Pertanyaan apakah sistemnya benar tidak dapat dijawab hanya dengan menguji perangkat lunaknya.

- Ada empat cara pokok sebuah sistem gagal, satu untuk tiap komponen. Kegagalan jarang berdiri sendiri.

- Penahan adalah bagian sistem yang mencegah kegagalan satu komponen berubah menjadi kegagalan seluruh sistem.

- Titik lemah sebuah sistem adalah komponen yang kegagalannya tidak ditahan oleh apa pun.

- Data yang tersedia tetapi tidak dipakai sama saja dengan data yang tidak ada.

# **Latihan**

Setiap soal ditandai dengan Sub-CPMK yang diukur.

## **Tingkat A Memastikan Anda ingat**

1.  Sebutkan empat komponen sistem informasi beserta pertanyaan yang dijawab oleh masing-masing komponen. \[Sub-CPMK-1\]

2.  Jelaskan apa yang dimaksud dengan sistem sosio-teknis, dengan kalimat Anda sendiri. \[Sub-CPMK-1\]

3.  Apa yang dimaksud dengan penahan, dan bagaimana cara menemukan titik lemah sebuah sistem? \[Sub-CPMK-1\]

4.  Mengapa buku ini menyatakan bahwa data yang tersedia tetapi tidak digunakan sama saja dengan data yang tidak ada? \[Sub-CPMK-1\]

5.  Sebutkan tiga hal yang tampaknya termasuk dalam anatomi sistem informasi tetapi sengaja tidak dibahas dalam bab ini, beserta alasannya. \[Sub-CPMK-1\]

## **Tingkat B Menerapkan**

1.  Bongkar layanan pembayaran uang kuliah di kampus Anda menjadi 4 komponen, menggunakan 4 langkah pada Subbab 2.5. \[Sub-CPMK-1\]

2.  Untuk setiap komponen pada jawaban nomor 1, tuliskan satu cara komponen tersebut dapat gagal. Kalau Anda tidak dapat memikirkan satu pun, katakan demikian dan jelaskan alasannya. \[Sub-CPMK-1\]

3.  Perhatikan Gambar 2.3. Tambahkan satu butir pada setiap kotak yang menurut Anda terlewat, dan jelaskan mengapa butir itu perlu ada. \[Sub-CPMK-1\]

## **Tingkat C Menganalisis dan menilai**

1.  Pilih satu layanan digital yang Anda gunakan setidaknya 3 kali dalam seminggu. Bongkar menjadi 4 komponen, lalu ajukan pertanyaan penahan kepada masing-masing komponen. Tunjukkan satu titik lemah dan pertahankan penunjukan Anda. Kalau menurut Anda layanan itu tidak punya titik lemah, katakan demikian dan siapkan alasannya, sebab pernyataan seperti itu jarang benar. \[Sub-CPMK-1\]

2.  Seorang perancang mengusulkan agar kurir hanya dapat menutup pesanan setelah pelanggan menyebutkan kode empat digit. Seorang kurir menolak usulan itu dengan alasan bahwa sebagian pelanggan tidak membuka pintu, sebagian meminta pesanan ditinggal di depan, dan sebagian lainnya tidak mengangkat telepon. Nilailah kedua pendirian tersebut. Komponen mana yang diuntungkan oleh usulan itu, dan komponen mana yang dibebani? Ambil sikap dan pertahankan. \[Sub-CPMK-1\]

# **Rujukan bab**

Rujukan berikut khusus untuk bab ini. Daftar pustaka gabungan ada di bagian akhir buku.

1.  Alter, S. (2013). “Work System Theory: Overview of Core Concepts, Extensions, and Challenges for the Future.” Journal of the Association for Information Systems, 14(2). Sumber utama bagi cara pandang sosio-teknis yang dipakai dalam bab ini.

2.  Laudon, K. C. dan Laudon, J. P. Management Information Systems: Managing the Digital Firm. Pearson, edisi terbaru. Bagian mengenai dimensi organisasi, manajemen, dan teknologi dalam sistem informasi.

3.  Bourgeois, D. Information Systems for Business and Beyond. Buku teks terbuka. Bab mengenai komponen sistem informasi.
