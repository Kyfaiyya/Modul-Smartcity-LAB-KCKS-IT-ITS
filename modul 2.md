# MODUL 2 — PEMILIHAN TEKNOLOGI SMART CITY

**Mata Kuliah:** Teknologi Smart City (ET234504)  
**Departemen:** Teknologi Informasi, ITS  
**Beban Praktikum:** 1 SKS  
**Semester:** 5

## 1. Pendahuluan

Pemilihan teknologi Smart City dilakukan dengan menerjemahkan isu prioritas menjadi kebutuhan sistem, mengevaluasi alternatif teknologi, dan merancang arsitektur sistem. Setiap keputusan teknologi harus didasarkan pada kebutuhan layanan, spesifikasi teknis, batasan implementasi, dan kriteria evaluasi yang jelas.

Modul ini membahas tiga tahapan utama:

1. Kebutuhan sistem dan survei alternatif teknologi.
2. Pemilihan teknologi menggunakan *Weighted Decision Matrix*.
3. Perancangan arsitektur sistem.

Ketiga tahapan tersebut saling berkaitan. Kebutuhan sistem menjadi dasar evaluasi alternatif, hasil evaluasi menentukan teknologi yang dipilih, dan keputusan tersebut menjadi dasar perancangan arsitektur.

---

# 2. Kebutuhan Sistem dan Survei Alternatif Teknologi

## 2.1 Kebutuhan Sistem

Kebutuhan sistem menjelaskan fungsi dan karakteristik yang harus dipenuhi oleh solusi untuk menjawab isu prioritas. Kebutuhan dirumuskan sebelum pemilihan teknologi agar keputusan tidak didasarkan pada teknologi yang sedang populer, tetapi pada masalah yang harus diselesaikan.

### A. Kebutuhan Fungsional

Kebutuhan fungsional (*functional requirements*) menjelaskan fungsi atau layanan yang harus disediakan sistem.

Contoh:
- Sistem menerima data dari perangkat sensor.
- Sistem menyimpan data hasil pemantauan.
- Sistem menampilkan kondisi objek pada dashboard.
- Sistem memberikan notifikasi ketika kondisi tertentu terpenuhi.

Kebutuhan fungsional harus menjelaskan kemampuan sistem secara spesifik dan dapat diverifikasi.

### B. Kebutuhan Nonfungsional

Kebutuhan nonfungsional (*non-functional requirements*) menjelaskan karakteristik kualitas dan batas operasional sistem.

Aspek yang dapat dipertimbangkan meliputi:

| Aspek | Parameter |
|---|---|
| Kinerja | Waktu respons dan latensi |
| Akurasi | Tingkat kesalahan pengukuran atau prediksi |
| Reliabilitas | Kemampuan sistem beroperasi secara konsisten |
| Ketersediaan | Persentase waktu layanan tersedia |
| Skalabilitas | Kemampuan menangani peningkatan kapasitas |
| Keamanan | Autentikasi, otorisasi, dan perlindungan sistem |
| Privasi | Perlindungan dan pembatasan akses data |
| Energi | Konsumsi daya dan kebutuhan energi |

Kebutuhan nonfungsional harus menggunakan ukuran atau kriteria yang dapat diperiksa apabila menyatakan target kinerja, kapasitas, waktu, atau konsumsi sumber daya.

Contoh: waktu respons dashboard maksimal 3 detik pada kondisi pengujian yang ditentukan. Angka tersebut merupakan ilustrasi target, bukan standar universal.

### Panduan Menulis Kebutuhan Terukur

Kebutuhan yang baik harus terukur dan dapat diverifikasi. Setiap pernyataan kebutuhan sebaiknya mengandung angka, satuan, dan kondisi pengujian yang jelas.

| Kurang tepat | Lebih tepat |
|---|---|
| Sistem harus cepat | Waktu respons dashboard ≤ 3 detik pada 100 pengguna bersamaan |
| Sensor harus akurat | Akurasi pengukuran suhu ± 0,5 °C pada rentang 0–50 °C |
| Sistem harus andal | Ketersediaan layanan ≥ 99 % per bulan |
| Data harus aman | Seluruh transmisi data menggunakan enkripsi TLS 1.2 atau lebih tinggi |

Prinsip penulisan:
- Gunakan angka dan satuan yang spesifik.
- Sertakan kondisi atau konteks pengukuran.
- Pastikan dapat diuji atau diverifikasi.
- Hindari kata subjektif seperti "cepat", "mudah", atau "banyak" tanpa kuantifikasi.

### C. Kebutuhan dan Batasan Sistem

Kebutuhan menjelaskan hal yang harus dipenuhi oleh sistem, sedangkan batasan menjelaskan kondisi yang membatasi perancangannya.

Batasan dapat berupa:
- Anggaran pengadaan dan operasional.
- Cakupan wilayah layanan.
- Ketersediaan jaringan komunikasi.
- Sumber daya listrik.
- Infrastruktur yang sudah tersedia.
- Kemampuan sumber daya manusia.
- Ketersediaan dan aksesibilitas data.
- Regulasi serta persyaratan keamanan dan privasi.

Kebutuhan dan batasan sistem menjadi dasar untuk menentukan alternatif teknologi yang relevan.

## 2.2 Lanskap Teknologi Smart City

Teknologi Smart City terdiri atas beberapa kelompok yang memiliki fungsi berbeda dan saling mendukung dalam suatu sistem.

| Kelompok teknologi | Fungsi | Contoh |
|---|---|---|
| Sensor dan Internet of Things (IoT) | Mengamati kondisi fisik dan menghasilkan data | Sensor jarak, sensor kualitas udara, sensor aliran air |
| Jaringan komunikasi | Menghubungkan perangkat dan mengirimkan data | Wi-Fi, Ethernet, jaringan seluler, LoRaWAN |
| Platform data | Menerima, menyimpan, mengelola, dan menyediakan data | Basis data, API, platform IoT |
| Analitik dan AI | Menganalisis data, mendeteksi pola, dan menghasilkan prediksi | Deteksi anomali, prediksi kebutuhan layanan |
| Aplikasi layanan publik | Menyediakan informasi dan interaksi bagi pengguna | Dashboard, aplikasi warga, aplikasi petugas |

Komponen teknologi harus dipilih berdasarkan fungsi yang dibutuhkan. Teknologi dengan fungsi berbeda tidak dapat dibandingkan secara langsung, kecuali evaluasi dilakukan terhadap kemampuannya dalam memenuhi kebutuhan sistem yang sama.

### Peran Kecerdasan Buatan

Kecerdasan buatan (*Artificial Intelligence/AI*) dapat digunakan untuk klasifikasi, prediksi, deteksi anomali, analisis pola, dan pendukung keputusan.

Penerapan AI perlu mempertimbangkan:
- Tujuan analisis yang ingin dicapai.
- Ketersediaan dan kualitas data.
- Kesesuaian metode dengan karakteristik masalah.
- Kinerja dan keandalan hasil.
- Risiko kesalahan prediksi.
- Kebutuhan komputasi, biaya, dan privasi.

AI tidak selalu diperlukan dalam solusi Smart City. Penggunaannya harus memiliki dasar kebutuhan yang jelas. Apabila solusi dikaitkan dengan tema GEMASTIK 2026, kesesuaiannya harus merujuk pada panduan resmi kompetisi.

## 2.3 Survei Alternatif Teknologi

Survei alternatif teknologi bertujuan mengidentifikasi pilihan yang dapat memenuhi kebutuhan sistem. Alternatif harus memiliki fungsi yang sebanding agar dapat dievaluasi secara adil.

Parameter perbandingan dapat meliputi:

- Spesifikasi teknis.
- Biaya pengadaan dan operasional.
- Konsumsi daya.
- Cakupan atau jangkauan.
- Reliabilitas.
- Kebutuhan infrastruktur.
- Skalabilitas.
- Keamanan dan privasi.
- Keterbatasan teknis.

Informasi harus diperoleh dari sumber yang dapat diverifikasi, seperti dokumentasi resmi produsen, *datasheet*, dokumentasi teknis penyedia layanan, atau standar yang relevan.

Data hasil pengukuran, spesifikasi produsen, estimasi, dan asumsi harus dibedakan. Informasi yang tidak tersedia tidak boleh digantikan dengan angka rekaan.

### Panduan Membaca Spesifikasi Teknologi

Spesifikasi teknologi diperoleh dari *datasheet*, dokumentasi resmi produsen, atau dokumentasi penyedia layanan. Berikut aspek yang perlu diperhatikan saat membaca spesifikasi:

1. **Identifikasi parameter utama:** Temukan parameter yang relevan dengan kebutuhan sistem, seperti jangkauan, konsumsi daya, kecepatan data, atau harga.
2. **Perhatikan kondisi pengujian:** Spesifikasi sering berlaku pada kondisi tertentu (suhu, jarak, beban). Pastikan kondisi tersebut sesuai dengan lingkungan operasional yang dirancang.
3. **Bedakan nilai tipikal dan nilai maksimum:** Nilai tipikal (*typical*) menunjukkan performa umum, sedangkan nilai maksimum (*maximum*) menunjukkan batas kemampuan perangkat.
4. **Periksa satuan dan skala:** Pastikan satuan seragam saat membandingkan alternatif (misalnya mW vs W, m vs km).
5. **Catat sumber dan tanggal:** Dokumentasikan URL atau nama dokumen beserta tanggal akses untuk keperluan verifikasi.

Contoh: jika *datasheet* sensor menyatakan jangkauan 10 km pada kondisi *line-of-sight*, nilai tersebut mungkin tidak berlaku di lingkungan perkotaan dengan banyak penghalang.

Hasil survei menjadi dasar evaluasi alternatif menggunakan *Weighted Decision Matrix*.

---

# 3. Pemilihan Teknologi dengan Weighted Decision Matrix

## 3.1 Konsep Weighted Decision Matrix

*Weighted Decision Matrix* (WDM) adalah metode pengambilan keputusan multikriteria yang menggabungkan bobot kepentingan setiap kriteria dan skor masing-masing alternatif.

Metode ini digunakan ketika pemilihan teknologi melibatkan beberapa pertimbangan yang dapat saling bertentangan, seperti biaya, cakupan, konsumsi daya, reliabilitas, skalabilitas, dan privasi.

WDM menghasilkan skor komparatif berdasarkan kriteria dan bobot yang ditetapkan. Hasilnya bukan jaminan bahwa alternatif dengan skor tertinggi selalu menjadi pilihan terbaik. Kualitas keputusan tetap bergantung pada validitas data, definisi kriteria, dan kesesuaian alternatif terhadap kebutuhan wajib.

## 3.2 Penetapan Kriteria dan Pembobotan

Kriteria diturunkan dari kebutuhan dan batasan sistem. Setiap kriteria harus memiliki definisi operasional agar alternatif dapat dinilai secara konsisten.

Contoh kriteria:

| Kriteria | Pertimbangan |
|---|---|
| Biaya | Kesesuaian biaya dengan anggaran |
| Cakupan | Kemampuan menjangkau wilayah layanan |
| Daya | Konsumsi energi dalam kondisi operasional |
| Reliabilitas | Kemampuan beroperasi sesuai kebutuhan |
| Skalabilitas | Kemampuan menangani peningkatan kapasitas |
| Privasi | Kesesuaian pengelolaan data dengan persyaratan perlindungan |

Bobot menunjukkan tingkat kepentingan relatif setiap kriteria. Seluruh bobot harus dinormalisasi sehingga jumlahnya sama dengan 1.

$$
\sum_{i=1}^{n} w_i = 1
$$

dengan $w_i$ sebagai bobot kriteria ke-$i$.

### Pembobotan Berpasangan

Pembobotan berpasangan dilakukan dengan membandingkan tingkat kepentingan dua kriteria pada satu waktu. Salah satu pendekatan yang dapat digunakan adalah skala Saaty dalam *Analytic Hierarchy Process* (AHP).

| Nilai | Makna |
|---:|---|
| 1 | Sama penting |
| 3 | Sedikit lebih penting |
| 5 | Lebih penting |
| 7 | Sangat lebih penting |
| 9 | Mutlak lebih penting |
| 2, 4, 6, 8 | Nilai antara |

Nilai kebalikan digunakan ketika kriteria pada kolom lebih penting daripada kriteria pada baris.

Salah satu pendekatan untuk mengestimasi bobot adalah normalisasi kolom matriks perbandingan, kemudian menghitung rata-rata setiap baris hasil normalisasi.

$$
n_{ij} = \frac{a_{ij}}{\displaystyle\sum_{k=1}^{n} a_{kj}}
$$

$$
w_i = \frac{1}{n}\sum_{j=1}^{n} n_{ij}
$$

dengan:

- $a_{ij}$: nilai perbandingan kriteria ke-$i$ terhadap kriteria ke-$j$.
- $n_{ij}$: nilai hasil normalisasi pada baris ke-$i$ dan kolom ke-$j$.
- $w_i$: bobot kriteria ke-$i$.
- $n$: jumlah kriteria.

Pendekatan tersebut merupakan estimasi bobot. Jika menggunakan AHP secara lengkap, konsistensi matriks perlu diperiksa sesuai prosedur AHP.
## 3.3 Penilaian Alternatif

Setiap alternatif diberi skor berdasarkan kinerjanya terhadap masing-masing kriteria. Skala penilaian harus didefinisikan secara konsisten.

Contoh skala 1–5:

| Skor | Interpretasi |
|---:|---|
| 1 | Sangat tidak memenuhi |
| 2 | Kurang memenuhi |
| 3 | Cukup memenuhi |
| 4 | Memenuhi dengan baik |
| 5 | Sangat memenuhi |

Arah preferensi harus diperhatikan. Untuk kriteria biaya dan konsumsi daya, skor tinggi menunjukkan kondisi yang lebih menguntungkan, yaitu biaya atau konsumsi daya yang lebih rendah. Untuk kriteria seperti reliabilitas, skor tinggi menunjukkan performa yang lebih baik.

Skor harus didasarkan pada spesifikasi, bukti teknis, atau asumsi yang dinyatakan secara jelas. Kriteria yang memiliki batas minimum wajib tidak boleh dianggap terpenuhi hanya karena alternatif memperoleh skor total tinggi.

## 3.4 Perhitungan Skor Tertimbang

Skor total setiap alternatif dihitung dengan mengalikan bobot kriteria dengan skor alternatif pada kriteria tersebut, kemudian menjumlahkan seluruh hasilnya.

$$
S_j = \sum_{i=1}^{n} w_i r_{ij}
$$

dengan:

- $S_j$: skor total alternatif ke-$j$.
- $w_i$: bobot kriteria ke-$i$.
- $r_{ij}$: skor alternatif ke-$j$ pada kriteria ke-$i$.
- $n$: jumlah kriteria.

Alternatif dengan skor tertinggi menjadi kandidat utama apabila memenuhi kebutuhan wajib dan batasan sistem.

### Contoh Perhitungan

Angka berikut bersifat ilustratif.

| Kriteria | Bobot | Alternatif A | Alternatif B | Alternatif C |
|---|---:|---:|---:|---:|
| Biaya | 0,40 | 5 | 3 | 2 |
| Daya | 0,20 | 4 | 3 | 5 |
| Reliabilitas | 0,25 | 3 | 5 | 4 |
| Skalabilitas | 0,15 | 3 | 4 | 5 |

**Skor Alternatif A:**

$$
\begin{aligned}
S_A &= (0{,}40 \times 5) + (0{,}20 \times 4) \\
&\quad + (0{,}25 \times 3) + (0{,}15 \times 3) \\
&= 4{,}00
\end{aligned}
$$

**Skor Alternatif B:**

$$
\begin{aligned}
S_B &= (0{,}40 \times 3) + (0{,}20 \times 3) \\
&\quad + (0{,}25 \times 5) + (0{,}15 \times 4) \\
&= 3{,}65
\end{aligned}
$$

**Skor Alternatif C:**

$$
\begin{aligned}
S_C &= (0{,}40 \times 2) + (0{,}20 \times 5) \\
&\quad + (0{,}25 \times 4) + (0{,}15 \times 5) \\
&= 3{,}45
\end{aligned}
$$

Pada contoh ini, Alternatif A memiliki skor tertinggi. Keputusan akhir tetap harus mempertimbangkan kebutuhan wajib, keterbatasan teknis, dan stabilitas hasil penilaian.
## 3.5 Analisis Kompromi

Analisis kompromi (*trade-off analysis*) digunakan untuk memahami pertukaran antara kelebihan dan kekurangan alternatif.

Contohnya:
- Biaya lebih rendah dapat disertai keterbatasan fitur.
- Cakupan lebih luas dapat membutuhkan konsumsi energi lebih tinggi.
- Reliabilitas lebih tinggi dapat meningkatkan biaya pengadaan.
- Skalabilitas yang baik dapat membutuhkan infrastruktur lebih kompleks.
- Pengumpulan data yang lebih banyak dapat meningkatkan risiko privasi.

Analisis ini menjelaskan alasan di balik hasil perhitungan. Alternatif tidak cukup dipilih hanya berdasarkan skor total tanpa memeriksa konsekuensi teknisnya.

## 3.6 Uji Sensitivitas

Uji sensitivitas digunakan untuk menilai pengaruh perubahan bobot terhadap hasil keputusan.

Pengujian dilakukan dengan mengubah bobot berdasarkan skenario yang masuk akal, menormalisasi ulang bobot, lalu menghitung kembali skor alternatif.

Jika alternatif terpilih tetap unggul pada beberapa skenario yang relevan, keputusan relatif stabil terhadap perubahan bobot. Jika peringkat berubah, kelompok perlu mengidentifikasi kriteria yang menyebabkan perubahan tersebut.

Uji sensitivitas tidak digunakan untuk memaksakan alternatif tertentu menjadi pemenang. Tujuannya adalah memahami kondisi yang dapat mengubah keputusan dan keterbatasan hasil evaluasi.

---

# 4. Perancangan Arsitektur Sistem

## 4.1 Konsep Arsitektur Sistem

Arsitektur sistem menggambarkan komponen utama, fungsi setiap komponen, hubungan antarkomponen, serta aliran data dalam solusi Smart City.

Arsitektur harus mencerminkan keputusan teknologi yang telah ditetapkan dan menunjukkan bagaimana komponen bekerja sama untuk memenuhi kebutuhan sistem.

Modul ini menggunakan arsitektur empat lapis: perangkat, jaringan, platform, dan aplikasi.

## 4.2 Lapisan Arsitektur

### A. Lapisan Perangkat

Lapisan perangkat mencakup komponen yang mengamati kondisi fisik, menghasilkan data, atau menjalankan aksi.

Contoh:
- Sensor.
- Perangkat IoT.
- Mikrokontroler.
- Gateway perangkat.
- Aktuator.

Pemilihan perangkat harus mempertimbangkan fungsi, spesifikasi, konsumsi daya, lingkungan operasional, dan kebutuhan komunikasi.

### B. Lapisan Jaringan

Lapisan jaringan menghubungkan perangkat dengan platform atau komponen lain.

Contoh:
- Wi-Fi.
- Ethernet.
- Jaringan seluler.
- LoRaWAN.

Pemilihan jaringan mempertimbangkan jangkauan, bandwidth, latensi, konsumsi energi, biaya, ketersediaan infrastruktur, dan keamanan komunikasi.

Protokol komunikasi harus dibedakan dari teknologi jaringan. MQTT, misalnya, merupakan protokol pertukaran pesan, sedangkan Wi-Fi merupakan teknologi jaringan nirkabel.

### C. Lapisan Platform

Lapisan platform menerima, mengelola, memproses, dan menyimpan data sebelum digunakan oleh aplikasi atau komponen lain.

Contoh:
- Layanan penerimaan data.
- Broker pesan.
- API.
- Basis data.
- Mesin pemrosesan data.
- Modul analitik atau AI.

Komponen yang digunakan harus sesuai dengan kebutuhan sistem. Platform tidak harus mencakup seluruh jenis komponen tersebut apabila fungsi yang dibutuhkan dapat dipenuhi dengan arsitektur yang lebih sederhana.

### D. Lapisan Aplikasi

Lapisan aplikasi menyediakan fungsi yang digunakan oleh warga, petugas, operator, atau pengambil keputusan.

Contoh:
- Dashboard pemantauan.
- Aplikasi pelaporan warga.
- Aplikasi petugas lapangan.
- Sistem notifikasi.
- Laporan analitik.

Aplikasi harus mendukung kebutuhan pengguna dan menampilkan informasi yang relevan dengan keputusan atau tindakan yang perlu dilakukan.

## 4.3 Aliran Data dan Hubungan Antarkomponen

Arsitektur harus memperlihatkan hubungan antarlapisan secara jelas.

Pada sistem pemantauan berbasis IoT, aliran data umumnya mengikuti urutan berikut:

1. Perangkat mengukur kondisi objek.
2. Data dikirimkan melalui jaringan komunikasi.
3. Platform menerima dan memproses data.
4. Data disimpan atau dianalisis sesuai kebutuhan.
5. Aplikasi menyajikan informasi kepada pengguna.
6. Pengguna mengambil tindakan berdasarkan informasi tersebut.

Sistem tertentu dapat memiliki komunikasi dua arah, misalnya aplikasi mengirimkan perintah kontrol kepada perangkat. Arah komunikasi tersebut harus sesuai dengan fungsi sistem dan ditunjukkan dalam diagram.

## 4.4 Notasi Diagram dan Penamaan Komponen

Diagram arsitektur harus menggunakan notasi yang konsisten dan menunjukkan fungsi serta hubungan antarkomponen.

Prinsip penyusunan diagram:

- Kelompokkan komponen berdasarkan lapisan arsitektur.
- Gunakan nama yang konsisten dengan keputusan teknologi.
- Tunjukkan arah aliran data atau perintah menggunakan panah.
- Beri label pada aliran yang memiliki fungsi berbeda.
- Hindari komponen yang tidak memiliki fungsi jelas.
- Gunakan legenda apabila terdapat simbol atau warna khusus.
- Pastikan hubungan antarkomponen dapat dipahami tanpa penjelasan lisan tambahan.

Diagram bukan sekadar visualisasi daftar teknologi. Diagram harus menjelaskan bagaimana sistem bekerja sebagai satu kesatuan.

## 4.5 Kesiapan Implementasi

Kelayakan rancangan dipengaruhi oleh kesiapan kondisi implementasi. Empat aspek yang perlu diperiksa adalah infrastruktur, stakeholder, sumber daya manusia, dan data.

| Aspek | Hal yang dinilai |
|---|---|
| Infrastruktur | Ketersediaan jaringan, listrik, perangkat pendukung, dan layanan platform |
| Stakeholder | Peran, tanggung jawab, koordinasi, dan keterlibatan pihak terkait |
| Sumber daya manusia | Kemampuan mengoperasikan, memelihara, dan mengelola sistem |
| Data | Ketersediaan, kualitas, format, akses, dan perlindungan data |

Penilaian kesiapan harus didasarkan pada kondisi yang diketahui. Asumsi desain tidak boleh dinyatakan sebagai fakta lapangan tanpa verifikasi.

Jika terdapat kebutuhan yang belum terpenuhi, kebutuhan tersebut harus diperlakukan sebagai prasyarat atau hambatan implementasi. Status kesiapan yang belum diketahui juga tidak dapat langsung dianggap siap.

Arsitektur yang baik tidak hanya menunjukkan bahwa teknologi dapat dihubungkan, tetapi juga memperlihatkan apakah sistem dapat dioperasikan dalam kondisi yang relevan dengan kebutuhan layanan.

---

## Ringkasan

Pemilihan teknologi Smart City dilakukan melalui tiga tahapan yang saling berkaitan:

1. **Kebutuhan sistem dan survei alternatif:** merumuskan kebutuhan fungsional dan nonfungsional, menetapkan batasan, serta membandingkan alternatif berdasarkan spesifikasi yang dapat diverifikasi.
2. **Weighted Decision Matrix:** menetapkan kriteria dan bobot, memberikan skor, menghitung nilai tertimbang, menganalisis kompromi, dan menguji sensitivitas keputusan.
3. **Perancangan arsitektur sistem:** menyusun hubungan antara lapisan perangkat, jaringan, platform, dan aplikasi serta menilai kesiapan implementasi.

Keputusan teknologi harus dapat ditelusuri dari kebutuhan sistem hingga rancangan arsitektur. Skor tertinggi tidak otomatis menjadi keputusan akhir apabila alternatif gagal memenuhi kebutuhan wajib atau menghadapi hambatan implementasi yang belum terselesaikan.

