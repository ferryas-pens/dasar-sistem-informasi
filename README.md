# Materi Ajar — Dasar Sistem Informasi (DSI)

Program Studi Sarjana Terapan (D4) Teknik Informatika — Politeknik Elektronika Negeri Surabaya (PENS).
Materi bersumber dari buku ajar **Dasar Sistem Informasi (12 bab)**, dikonversi dari berkas Word asli menjadi satu berkas Markdown per bab. **Isi tiap bab identik dengan naskah asli**; konversi ini hanya memindahkan format (`.docx` → `.md`) dan menautkan gambar ke folder `asset/`.

## Identitas Mata Kuliah

Sumber: `RPS_Dasar_Sistem_Informasi_D4_TI_PENS.docx` (dokumen resmi, bukan asumsi).

| Butir | Nilai |
| --- | --- |
| Nama mata kuliah | Dasar Sistem Informasi |
| Kode MK | TI 26 04 1 1 03 |
| Rumpun MK | Keilmuan Dasar |
| Bobot | 2 sks (T = 2, P = 0) |
| Semester | 1 |
| Mata kuliah prasyarat | Tidak ada |
| Tgl penyusunan RPS | 14 Agustus 2026 |

## Deskripsi Singkat

*(Kutipan verbatim dari RPS.)*

Mata kuliah ini membangun fondasi cara pandang sistem informasi bagi mahasiswa semester 1 Teknik Informatika: bagaimana data menjadi informasi yang bernilai, bagaimana organisasi bekerja melalui proses bisnis, dan mengapa sebuah sistem yang benar secara teknis masih dapat gagal di lapangan. Mata kuliah ini berperan sebagai jembatan antara kompetensi teknis yang akan dipelajari pada semester berikutnya (pemrograman, basis data, jaringan, rekayasa perangkat lunak) dengan konteks organisasi tempat sistem tersebut dipakai, sekaligus menjadi pengganti mata kuliah Konsep Teknologi Informasi sehingga materi etika profesi, tanggung jawab publik, dan tren teknologi terkini diserap ke dalam mata kuliah ini. Pembahasan bersifat konseptual dan berbasis kasus, tanpa menuntut prasyarat teknis. Batas cakupan: komponen perangkat keras dan arsitektur komputer tidak dibahas di sini karena menjadi lingkup mata kuliah Dasar Sistem Komputer; pemodelan perangkat lunak dan notasi UML menjadi lingkup Workshop Pemodelan Perangkat Lunak; implementasi model pengambilan keputusan menjadi lingkup Sistem Pendukung Keputusan.

## Daftar Bab

Judul diambil dari isi berkas hasil konversi. Kolom **Sub-CPMK**, **Minggu**, dan **Level** (Bloom) berasal dari `Blueprint-Buku-Ajar-DSI.md` — pemetaan pra-penulisan; finalkan terhadap RPS bila ada perbedaan. Catatan desain penting dari blueprint: **bab ≠ minggu perkuliahan** (satu bab dapat memakan dua minggu atau dua bab dapat diajarkan sekaligus dalam satu minggu).

| Bab | Judul | Sub-CPMK | Minggu | Level |
| --- | --- | --- | --- | --- |
| **BAGIAN I — MEMAHAMI SISTEM INFORMASI** | | | | |
| 1 | [Sistem, Data, dan Informasi](bab-01.md) | Sub-1 | 1 | K1–K2 |
| 2 | [Anatomi Sistem Informasi](bab-02.md) | Sub-1 | 1–2 | K2 |
| 3 | [Profesi dan Peran di Bidang Teknologi Informasi](bab-03.md) | Sub-1 | 2 | K1–K2 |
| **BAGIAN II — INFORMASI SEBAGAI SESUATU YANG BERNILAI** | | | | |
| 4 | [Kualitas Informasi](bab-04.md) | Sub-2 | 3 | K2 |
| 5 | [Nilai Informasi dan Pengambilan Keputusan](bab-05.md) | Sub-2 | 4 | K2 |
| **BAGIAN III — ORGANISASI DAN PROSES** | | | | |
| 6 | [Organisasi, Struktur, dan Rantai Nilai](bab-06.md) | Sub-3 | 5 | K2 |
| 7 | [Proses Bisnis dan Pemodelan Alur Kerja](bab-07.md) | Sub-3 | 6 | K3 |
| 8 | [Menurunkan Kebutuhan Informasi dari Proses Bisnis](bab-08.md) | Sub-3 | 7 | K3 |
| **BAGIAN IV — RAGAM SISTEM INFORMASI** | | | | |
| 9 | [Ragam Sistem Informasi: TPS, MIS, DSS, dan ESS](bab-09.md) | Sub-4 | 8–9 | K3–K4 |
| 10 | [Enterprise Systems dan Keunggulan Kompetitif](bab-10.md) | Sub-4 | 10 | K3–K4 |
| **BAGIAN V — TANGGUNG JAWAB DAN ARAH KE DEPAN** | | | | |
| 11 | [Keamanan, Privasi, dan Regulasi Pelindungan Data](bab-11.md) | Sub-5 | 11 | K2 |
| 12 | [Etika Profesi, Dampak Sosial, dan Tren Teknologi](bab-12.md) | Sub-5 | 12–13 | K2–K3 |

## Berkas Pendukung

Berkas ini bukan bab, tetapi bagian dari buku ajar yang sama; ikut dikonversi ke Markdown.

| Berkas | Isi |
| --- | --- |
| [bagian-depan.md](bagian-depan.md) | Front matter: halaman judul, identitas prodi, dan bagian pembuka buku. |
| [bagian-belakang.md](bagian-belakang.md) | Back matter: glosarium (dan bagian penutup buku). |
| [bab-08-pemantik.md](bab-08-pemantik.md) | Versi *pemantik* (pembuka berbasis kasus) untuk Bab 8. |
| [panduan-penilaian.md](panduan-penilaian.md) | Lampiran untuk dosen: kunci latihan tingkat B, rubrik latihan tingkat C, laporan pemeriksaan naskah. |
| [berkas-kasus-cadangan.md](berkas-kasus-cadangan.md) | Kasus cadangan (mis. "Unit Layanan Peralatan Laboratorium") sebagai alternatif kasus utama. |

## Cara Pakai dan Catatan Aset

- Seluruh gambar (36 berkas) berada di satu folder `asset/`, dinamai `asset/bab-XX-gambar-N.png` mengikuti urutan kemunculan gambar di tiap bab (mis. `asset/bab-07-gambar-1.png` = Gambar 7.1).
- Berkas `.md` memakai referensi gambar relatif ke `asset/`. **Pertahankan seluruh berkas `.md` dalam satu folder bersama folder `asset/`.** Jika berkas `.md` dipindah keluar dari folder ini, tautan gambar akan putus.
- Untuk pemakaian di LMS/GitHub, unggah folder ini secara utuh (termasuk `asset/`).





