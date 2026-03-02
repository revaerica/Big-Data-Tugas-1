# Tugas Pertemuan 1: Big Data dalam Industri E-Commerce dan Media Sosial
| **NRP** | **Nama** |
|:---:|:---|
| 5027241007 | Revalina Erica Permatasari |

---

## 1. Identifikasi Sumber Data Big Data

TikTok bukan sekadar aplikasi hiburan. Sejak hadirnya TikTok Shop, platform ini juga menjadi tempat jual beli yang sangat aktif. Nilai total transaksi (GMV) TikTok Shop secara global mencapai USD 33,2 miliar pada tahun 2024, dan Indonesia menjadi pasar terbesar kedua di dunia [1][2]. Semua aktivitas yang terjadi di dalamnya — menonton video, belanja, hingga memasang iklan — menghasilkan data dalam jumlah yang sangat besar setiap harinya.

Berikut adalah lima sumber data Big Data yang dihasilkan oleh TikTok:

**a. Data Interaksi Konten (For You Page / FYP)**
Setiap hal yang dilakukan pengguna saat menonton video tercatat otomatis. Berapa lama video ditonton, apakah ditonton ulang, di detik berapa pengguna berhenti, apakah video di-like, dikomentari, atau di-share — semuanya tersimpan sebagai data. Data teks dari caption, hashtag, dan komentar juga ikut dianalisis untuk memahami isi dan konteks konten tersebut [3].

**b. Data Transaksi TikTok Shop**
Setiap pembelian di TikTok Shop meninggalkan jejak data yang lengkap: produk apa yang dibeli, dari video atau live streaming mana, siapa penjualnya, metode pembayaran apa yang dipakai, di mana lokasi pembeli, dan apakah ada voucher yang digunakan. Yang membuat TikTok unik adalah kemampuannya menghubungkan langsung antara konten yang ditonton dengan keputusan pembelian — sesuatu yang tidak bisa dilakukan platform belanja biasa. Sebanyak enam dari sepuluh orang Indonesia sudah pernah membeli produk lewat live streaming pada tahun 2024 [4].

**c. Data Konten Kreator dan Katalog Produk**
Jutaan video diunggah setiap hari oleh kreator dan penjual. Setiap video mengandung data yang beragam: gambar bergerak, suara, teks yang muncul di layar, serta informasi teknis seperti waktu unggah dan lokasi perangkat. Di sisi lain, setiap produk yang dijual di TikTok Shop juga menghasilkan data berupa foto, deskripsi, harga, jumlah stok, dan ulasan dari pembeli [5].

**d. Data Profil dan Demografi Pengguna**
Setiap akun TikTok menyimpan informasi dasar pengguna, seperti usia, jenis kelamin, kota asal, bahasa yang digunakan, dan jenis perangkat yang dipakai. Data profil ini digabungkan dengan riwayat interaksi untuk membentuk gambaran lengkap tentang siapa pengguna tersebut — proses ini disebut *user profiling*. Hasilnya digunakan untuk menampilkan konten dan iklan yang relevan untuk masing-masing pengguna [6].

**e. Data Iklan dan Kinerja Kampanye (TikTok Ads)**
Penjual dan brand yang memasang iklan di TikTok menghasilkan data kinerja secara real-time, seperti berapa kali iklan dilihat, berapa banyak orang yang mengkliknya, berapa yang akhirnya membeli, dan berapa biaya yang dikeluarkan per hasil. Data ini membantu pengiklan memahami iklan mana yang efektif dan audiens mana yang paling tertarik [6].

---

## 2. Penerapan Konsep 5V

Dalam Big Data, dikenal konsep 5V sebagai cara memahami karakteristik data. Berikut penerapannya pada data TikTok:

| Dimensi | Penerapan pada Data TikTok |
|---|---|
| **Volume** | TikTok memiliki lebih dari 1 miliar pengguna aktif per bulan. Jutaan video diunggah dan miliaran interaksi terjadi setiap harinya, menghasilkan data dalam skala yang sangat besar (disebut petabyte) [1][3]. |
| **Velocity** | Rekomendasi FYP diperbarui secara langsung berdasarkan apa yang baru saja ditonton. Saat live shopping berlangsung, data komentar dan pembelian masuk dalam hitungan milidetik (seperseribu detik) [3]. |
| **Variety** | Ada data berupa video, teks ulasan, angka transaksi, audio, hingga informasi lokasi perangkat. Semuanya bercampur dan harus diolah dengan cara yang berbeda-beda. |
| **Veracity** | Ada akun bot yang menghasilkan like dan view palsu, serta ulasan produk yang tidak jujur. Data semacam ini harus disaring dan dibersihkan terlebih dahulu sebelum digunakan [5]. |
| **Value** | Data yang diolah dengan baik terbukti membuat pengguna lebih lama menggunakan TikTok dan meningkatkan angka penjualan di TikTok Shop. Penelitian menunjukkan bahwa ketika personalisasi dikurangi, pengguna menghabiskan waktu lebih sedikit di aplikasi [5]. |

---

## 3. Potensi Value dari Data TikTok

Data yang terkumpul dari TikTok dapat dimanfaatkan untuk berbagai keperluan yang menghasilkan nilai nyata:

- **Rekomendasi konten yang sangat personal:** TikTok tidak hanya menampilkan video dari akun yang diikuti, melainkan menebak video apa yang kemungkinan besar disukai berdasarkan kebiasaan menonton pengguna. Sistem ini disebut *interest graph* dan terbukti jauh lebih akurat dibanding platform lain [3][5].

- **Strategi penjualan berbasis data:** Penjual di TikTok Shop dapat melihat secara detail konten mana yang mendorong pembeli untuk bertransaksi, sehingga mereka bisa membuat konten yang lebih tepat sasaran dan mengalokasikan anggaran promosi dengan lebih efisien [4].

- **Peluang lebih merata bagi UMKM:** Di TikTok, konten dari penjual kecil pun bisa menjangkau jutaan orang jika relevan bagi pengguna, karena sistem distribusi tidak bergantung pada jumlah pengikut. Ini memberi kesempatan yang sama bagi usaha kecil untuk bersaing [4].

- **Membaca tren lebih cepat:** Karena data mengalir secara terus-menerus, tren yang sedang naik bisa terdeteksi lebih awal — bahkan sebelum menjadi viral secara resmi. Ini sangat berguna bagi penjual yang ingin merespons tren lebih cepat dari kompetitor [3].

---

## 4. Tantangan Pengelolaan Data

Mengelola data sebesar ini bukan tanpa masalah. Ada beberapa tantangan utama yang perlu dihadapi:

- **Privasi pengguna dan aturan hukum:** TikTok mengumpulkan sangat banyak data pribadi, termasuk informasi dari konten video yang diunggah. Di Indonesia, hal ini diatur ketat oleh UU Perlindungan Data Pribadi (UU PDP) No. 27 Tahun 2022. Jika dilanggar, platform bisa terkena sanksi hukum dan kehilangan kepercayaan penggunanya.

- **Kualitas data yang tidak selalu bersih:** Keberadaan bot, akun palsu, dan aktivitas yang tidak nyata (seperti membeli jumlah views atau likes) membuat sebagian data tidak mencerminkan kondisi sesungguhnya. Data yang kotor ini bisa membuat sistem rekomendasi memberikan hasil yang tidak akurat [5].

- **Cara kerja algoritma yang tidak transparan:** Tidak ada yang tahu persis bagaimana algoritma FYP memutuskan konten mana yang ditampilkan atau tidak. Hal ini menyulitkan kreator dalam memahami kenapa konten mereka bisa atau tidak bisa menjangkau banyak orang, dan menimbulkan pertanyaan soal keadilan sistem [5].

- **Kebutuhan infrastruktur yang sangat besar:** Untuk melayani miliaran pengguna dengan rekomendasi yang diperbarui setiap saat, TikTok membutuhkan sistem komputer dalam skala raksasa. Biaya pengoperasiannya sangat tinggi dan terus bertambah seiring dengan munculnya fitur-fitur baru seperti TikTok LIVE dan TikTok Shop.

---

## Kesimpulan

TikTok merupakan contoh nyata bagaimana Big Data bekerja dalam industri media sosial dan e-commerce sehari-hari. Lima sumber data yang diidentifikasi — interaksi konten, transaksi TikTok Shop, konten kreator, profil pengguna, dan data iklan — semuanya memenuhi karakteristik 5V dan menyimpan potensi nilai yang besar. Namun, tantangan terkait privasi, kualitas data, transparansi algoritma, dan kebutuhan infrastruktur harus dikelola dengan serius agar pemanfaatan data ini dapat memberi manfaat yang bertanggung jawab bagi semua pihak.

---

## Daftar Referensi

[1] Shewale, R. (2026, Januari 21). *TikTok Shop statistics (2026): Global GMV*. Resourcera.

[2] Iswenda, B. A. (2025, Januari 15). *Indonesia jadi negara dengan GMV TikTok Shop terbesar ke-2 di dunia*. GoodStats.

[3] Zhou, R. (2024). Understanding the impact of TikTok's recommendation algorithm on user engagement. *International Journal of Computer Science and Information Technology, 3*(2), 201–208.

[4] Meliana, P. (2025). *Inside Indonesia's US$22 billion social commerce future: Live shopping, influencer trust, and TikTok Shop*. ContentGrip.

[5] Dekker, C. A., Baumgartner, S. E., & Sumter, S. R. (2025). For you vs. for everyone: The effectiveness of algorithmic personalization in driving social media engagement. *Telematics and Informatics, 101*, Article 102300.

[6] Gerbaudo, P. (2024). TikTok and the algorithmic transformation of social media publics: From social networks to social interest clusters. *New Media & Society*.

[7] Pravitasari, C., & Sutarsih, T. (2025). *Statistik e-commerce 2024* (Vol. 7). Badan Pusat Statistik.
