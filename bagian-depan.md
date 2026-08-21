**DASAR SISTEM INFORMASI**

Untuk Mahasiswa Sarjana Terapan Teknik Informatika

Program Studi Sarjana Terapan Teknik Informatika

Departemen Teknik Informatika dan Komputer

Politeknik Elektronika Negeri Surabaya

*Naskah kerja. Belum untuk diedarkan.*

**Kata pengantar**

Buku ini ditulis untuk mahasiswa semester satu Program Studi Sarjana Terapan Teknik Informatika, dan menyadari sejak awal bahwa mata kuliah Dasar Sistem Informasi menempati kedudukan yang tidak biasa di dalam kurikulum sebuah program studi informatika.

Kedudukan itu perlu dijelaskan, sebab ia menentukan seluruh isi buku ini.

Pedoman kurikulum ilmu komputer yang disusun bersama oleh ACM, IEEE Computer Society, dan AAAI tidak memuat sistem informasi sebagai bidang pengetahuan tersendiri. Sebaliknya, pedoman kurikulum sistem informasi yang disusun ACM bersama AIS ditujukan bagi program studi sistem informasi, bukan bagi program studi informatika. Kedua rujukan itu, kalau dipakai apa adanya, tidak menjelaskan mengapa mata kuliah ini ada di sini.

Jawabannya, menurut penyusun buku ini, terletak pada apa yang tidak diajarkan mata kuliah lain.

Selama delapan semester, mahasiswa program studi ini akan mempelajari pemrograman, basis data, jaringan, rekayasa perangkat lunak, dan kecerdasan artifisial. Yang tidak diajarkan oleh satu pun di antaranya adalah konteks organisasi tempat semua itu dipakai: bagaimana sebuah organisasi bekerja, bagaimana keputusan diambil di dalamnya, informasi apa yang dibutuhkan untuk mengambil keputusan itu, dan mengapa sebuah sistem yang benar secara teknis tetap dapat gagal.

Di situlah mata kuliah ini berada, dan di situlah buku ini menempatkan seluruh isinya.

Karena itu pula buku ini sengaja tidak mengajarkan cara membuat apa pun. Tidak ada satu baris kode program di dalamnya, tidak ada perancangan basis data, dan tidak ada pembahasan perangkat keras. Semuanya diserahkan kepada mata kuliah yang memang bertugas mengajarkannya. Yang dilatih di sini hanya satu keterampilan: melihat sesuatu sebagai sistem informasi, dan mengetahui pertanyaan apa yang harus diajukan sebelum sesuatu dibangun.

Buku ini juga berusaha jujur mengenai batas-batasnya sendiri. Setiap bab menyebutkan apa yang tidak dibahasnya dan di mana pembacanya dapat menemukan hal tersebut. Setiap studi kasus diakhiri dengan kritik terhadap hasilnya sendiri. Kebiasaan ini bukan kerendahan hati yang dibuat-buat, melainkan bagian dari apa yang hendak diajarkan. Seorang perancang sistem yang tidak dapat menyebutkan keterbatasan rancangannya sendiri adalah perancang yang berbahaya.

Penyusun menyadari bahwa buku ini masih akan banyak berubah. Bagian yang paling cepat kedaluwarsa adalah pembahasan mengenai regulasi pelindungan data pada Bab 11 dan pembahasan mengenai tren teknologi pada Bab 12. Keduanya ditandai secara khusus agar mudah diperiksa sebelum tiap cetakan baru.

Masukan dan koreksi sangat diharapkan, terutama dari mahasiswa yang memakainya. Bagian yang terasa membingungkan hampir selalu merupakan kesalahan penyusun, bukan kesalahan pembaca.

Surabaya, 2026

*Penyusun*

**Cara memakai buku ini**

Buku ini tidak dirancang untuk dibaca seperti novel, dan juga tidak dirancang untuk dibaca hanya menjelang ujian. Beberapa keterangan berikut akan menghemat waktu Anda.

**Anatomi setiap bab**

Seluruh bab memakai susunan yang sama. Mengenalinya sekali akan menolong Anda sepanjang semester.

| **Bagian**           | **Gunanya bagi Anda**                                                           |
|----------------------|---------------------------------------------------------------------------------|
| Peta bab             | Mengetahui apa yang akan Anda kuasai dan bab apa yang harus dibaca lebih dahulu |
| Pemantik             | Satu cerita yang memunculkan pertanyaan yang belum dapat Anda jawab             |
| Uraian materi        | Isi pokok bab, biasanya empat sampai tujuh subbab                               |
| Kotak Di Balik Layar | Membuka hal yang tidak terlihat dari luar. Sering menjadi bahan bab berikutnya  |
| Kotak Salah Kaprah   | Tiga anggapan keliru yang lazim, beserta koreksinya                             |
| Studi kasus terpandu | Satu contoh dikerjakan tuntas, termasuk kritik atas hasilnya sendiri            |
| Rangkuman            | Butir-butir untuk memeriksa apakah Anda sudah menangkap yang pokok              |
| Latihan bertingkat   | Tiga tingkat: mengingat, menerapkan, menganalisis                               |
| Rujukan bab          | Bacaan lanjutan khusus untuk bab tersebut                                       |

**Mengenai latihan**

Latihan tingkat A dapat dijawab langsung dari bacaan. Latihan tingkat B menuntut Anda menerapkannya pada sesuatu yang Anda pilih sendiri. Latihan tingkat C menuntut Anda mengambil sikap dan mempertahankannya.

Latihan tingkat C sering tidak memiliki jawaban tunggal, dan sebagian bahkan sengaja disusun agar jawaban yang berbeda-beda sama-sama dapat diterima. Yang dinilai adalah alasannya, bukan kesimpulannya. Kalau Anda mencari jawaban yang benar untuk soal semacam itu, Anda sedang mencari sesuatu yang memang tidak ada.

Sebagian latihan tingkat C menuntut Anda mengamati organisasi nyata dan mewawancarai orang di dalamnya. Bila Anda benar-benar tidak memperoleh akses, tersedia berkas kasus cadangan yang dapat diminta kepada dosen pengampu. Berkas itu bukan pilihan yang setara, dan alasannya dijelaskan di dalam berkas tersebut.

**Mengenai gambar**

Seluruh gambar dalam buku ini dibuat khusus untuk buku ini dan dicetak hitam putih. Tidak ada satu pun keterangan yang hanya dapat dibedakan lewat warna.

Satu gambar sengaja dibuat memuat kesalahan, yaitu Gambar 7.2. Anda akan diminta menemukannya.

**Mengenai angka**

Seluruh angka yang berkaitan dengan organisasi bayangan dalam buku ini bersifat ilustrasi dan tidak berasal dari organisasi mana pun yang benar-benar ada. Angka yang berasal dari peristiwa nyata disebutkan sumbernya, dan bila angka itu masih berupa klaim yang belum dikonfirmasi, buku ini menyebutnya sebagai klaim.

**Peta buku**

Buku ini terdiri atas dua belas bab yang dikelompokkan ke dalam lima bagian. Tabel berikut menunjukkan hubungan antara bab, minggu perkuliahan, dan capaian pembelajaran yang diampunya.

| **Bab** | **Judul**                                         | **Minggu**   | **Sub-CPMK** |
|---------|---------------------------------------------------|--------------|--------------|
|         | BAGIAN I MELIHAT SISTEM INFORMASI                 |              |              |
| 1       | Sistem, Data, dan Informasi                       | 1            | Sub-CPMK-1   |
| 2       | Anatomi Sistem Informasi                          | 1 sampai 2   | Sub-CPMK-1   |
| 3       | Profesi dan Peran di Bidang Teknologi Informasi   | 2            | Sub-CPMK-1   |
|         | BAGIAN II INFORMASI SEBAGAI SESUATU YANG BERNILAI |              |              |
| 4       | Kualitas Informasi                                | 3            | Sub-CPMK-2   |
| 5       | Nilai Informasi dan Pengambilan Keputusan         | 4            | Sub-CPMK-2   |
|         | BAGIAN III ORGANISASI DAN PROSES                  |              |              |
| 6       | Organisasi, Struktur, dan Rantai Nilai            | 5            | Sub-CPMK-3   |
| 7       | Proses Bisnis dan Pemodelan Alur Kerja            | 6 sampai 7   | Sub-CPMK-3   |
| 8       | Menurunkan Kebutuhan Informasi dari Proses Bisnis | 7            | Sub-CPMK-3   |
|         | BAGIAN IV RAGAM SISTEM INFORMASI                  |              |              |
| 9       | Ragam Sistem Informasi: TPS, MIS, DSS, dan ESS    | 8 sampai 9   | Sub-CPMK-4   |
| 10      | Enterprise Systems dan Keunggulan Kompetitif      | 10           | Sub-CPMK-4   |
|         | BAGIAN V TANGGUNG JAWAB DAN ARAH KE DEPAN         |              |              |
| 11      | Keamanan, Privasi, dan Regulasi Pelindungan Data  | 11           | Sub-CPMK-5   |
| 12      | Etika Profesi, Dampak Sosial, dan Tren Teknologi  | 12 sampai 13 | Sub-CPMK-5   |

Beberapa bab bergantung pada bab lain dan tidak dapat dibaca terpisah. Yang paling erat adalah Bab 7 dan Bab 8: yang kedua memakai hasil pekerjaan yang pertama sebagai bahan mentahnya. Demikian pula Bab 9 dan Bab 10, yang keduanya berpijak pada Bab 8.

**Berkenalan dengan Laundry Nusa**

Mulai Bab 6 sampai Bab 10, buku ini memakai satu organisasi yang sama sebagai bahan pembahasan. Organisasi itu bernama Laundry Nusa.

Laundry Nusa tidak ada. Ia disusun khusus untuk buku ini, dengan struktur, proses, orang, dan persoalan yang menyerupai usaha sejenis yang benar-benar berjalan. Seluruh nama, angka, dan kejadian di dalamnya bersifat ilustrasi. Kesamaan dengan usaha mana pun tidak disengaja.

Alasan memakai satu organisasi yang sama sepanjang lima bab cukup sederhana. Setiap kali sebuah buku berpindah ke contoh baru, pembacanya harus menghabiskan tenaga untuk memahami konteksnya lebih dahulu, dan tenaga itu diambil dari tenaga untuk memahami gagasan yang sedang diajarkan. Dengan satu organisasi yang tetap, tenaga tersebut dapat dihemat sejak bab keenam.

| **Keterangan**      | **Isinya**                                                |
|---------------------|-----------------------------------------------------------|
| Jenis usaha         | Jasa cuci pakaian kiloan                                  |
| Jumlah gerai        | Empat: Keputih, Gebang, Klampis, dan Semolowaru           |
| Pemilik             | Pak Hardi, mendirikan gerai pertama sepuluh tahun lalu    |
| Manajer operasional | Satu orang, membawahi keempat gerai                       |
| Tiap gerai          | Tiga orang: petugas gerai, petugas cuci, petugas setrika  |
| Pencatatan          | Buku tulis pada tiap gerai, belum memakai perangkat lunak |
| Keadaan             | Sedang mempertimbangkan beralih ke pencatatan digital     |

Tiga orang di Gerai Keputih akan Anda temui berkali-kali, dan namanya disingkat sebagaimana lazim dipakai sehari-hari. Sdri. R menjaga meja depan. Mas T mengerjakan pencucian. Mbak S mengerjakan penyetrikaan dan pengemasan.

Persoalan yang dihadapi Laundry Nusa akan muncul bertahap. Pada Bab 6 Anda melihat strukturnya dan menemukan di mana informasi tersendat. Pada Bab 7 Anda menggambar prosesnya. Pada Bab 8 Anda menurunkan kebutuhan informasi darinya. Pada Bab 9 Anda memilih jenis sistem yang sesuai, dan pada Bab 10 Anda menyusun rekomendasi pengadaan.

Sebelum Bab 6, buku ini memakai contoh yang lebih dekat dengan keseharian Anda sendiri, yaitu layanan digital yang Anda pakai dan layanan yang tersedia di kampus. Peralihan dari yang akrab ke yang dapat dibedah tuntas itu disengaja.

**Daftar gambar**

| **No.** | **Judul**                                                             |
|---------|-----------------------------------------------------------------------|
| 1.1     | Unsur sebuah sistem dan batasnya                                      |
| 1.2     | Data, informasi, dan pengetahuan                                      |
| 2.1     | Empat komponen sistem informasi                                       |
| 2.2     | Empat cara sebuah sistem informasi gagal                              |
| 2.3     | Hasil pembongkaran layanan pesan-antar makanan                        |
| 3.1     | Enam peran dan mata kuliah yang menopangnya                           |
| 4.1     | Tujuh dimensi kualitas informasi dan pertanyaan pengujinya            |
| 4.2     | Tiga pertukaran yang paling sering muncul                             |
| 5.1     | Tingkat manajemen dan sifat keputusan pada sebuah kedai kopi kecil    |
| 5.2     | Empat pertanyaan untuk menaksir nilai sebuah informasi                |
| 6.1     | Struktur organisasi Laundry Nusa                                      |
| 6.2     | Rantai nilai Laundry Nusa                                             |
| 6.3     | Tiga perbatasan yang paling rawan di Laundry Nusa                     |
| 7.1     | Lima elemen notasi yang dipakai dalam buku ini                        |
| 7.2     | Proses penerimaan cucian di Gerai Keputih, versi awal                 |
| 7.3     | Proses penerimaan cucian di Gerai Keputih, bagian pertama             |
| 7.4     | Pengerjaan dan pengembalian cucian di Gerai Keputih, bagian kedua     |
| 7.5     | Potongan model perbaikan pada bagian penyetrikaan                     |
| 8.1     | Buku catatan Gerai Keputih dan pertanyaan yang tidak dapat dijawabnya |
| 8.2     | Arah mengalir dan arah mencari                                        |
| 8.3     | Tujuh kolom tabel kebutuhan informasi                                 |
| 8.4     | Tiga keadaan tempat lahir data                                        |
| 9.1     | Empat jenis sistem informasi menurut tingkat keputusan                |
| 9.2     | Aliran antarjenis sistem informasi di Laundry Nusa                    |
| 9.3     | Tangga keputusan untuk memilih jenis sistem                           |
| 10.1    | Tiga arah pandang terhadap satu organisasi                            |
| 10.2    | Perbandingan tiga cara pengadaan                                      |
| 10.3    | Empat sebab lazim kegagalan proyek enterprise system                  |
| 11.1    | Tiga tujuan keamanan informasi                                        |
| 11.2    | Hak subjek data dan kewajiban pengendali data                         |
| 12.1    | Empat pertanyaan untuk menilai klaim teknologi baru                   |
| 12.2    | Siapa memperoleh apa dan siapa menanggung apa                         |
