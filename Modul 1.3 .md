# Modul 1.3 Analisis Akar Masalah dan Pemeringkatan Isu

---

## 1. Tujuan Pembelajaran

Setelah mempelajari materi ini, kita diharapkan mampu:
- Membedakan antara gejala, penyebab antara, dan akar masalah.
- Menjelaskan fungsi metode APKL sebagai alat penyaringan isu.
- Menjelaskan fungsi metode USG sebagai alat pemeringkatan isu.
- Menerapkan metode APKL dan USG menggunakan rumus aktif pada spreadsheet.
- Memberikan justifikasi tertulis untuk setiap skor yang diberikan.
- Menyusun Diagram Fishbone dengan kategori yang sesuai untuk konteks Smart City.
- Menerapkan teknik 5 Whys untuk menemukan akar masalah.
- Memahami konsep Iceberg Model untuk menganalisis kedalaman masalah secara sistemik.
- Menghasilkan luaran berupa Diagram Fishbone (PNG) dan lembar kerja skoring (XLSX).

---

## 2. Pendahuluan

Pada Modul 1.2, kita telah mengamati fenomena perkotaan, mengeksplorasi konteksnya, memvalidasi bukti, dan merumuskan pernyataan masalah (*problem statement*).

Dari proses tersebut, biasanya diperoleh beberapa kandidat isu. Masing-masing tampak penting.

Namun, dalam pengelolaan kota yang sesungguhnya, pemerintah kota tidak dapat menyelesaikan semua masalah sekaligus. Selalu ada keterbatasan:
- anggaran daerah (APBD);
- waktu dan tenaga aparatur;
- infrastruktur teknologi;
- serta siklus perencanaan pembangunan (RPJMD/RKPD).

Karena itu, diperlukan cara yang sistematis untuk menentukan:

> *Dari sekian banyak isu, mana yang paling layak dan paling mendesak untuk ditangani terlebih dahulu?*

Tantangan lainnya adalah kecenderungan untuk langsung mengobati gejala yang terlihat di permukaan, tanpa menelusuri penyebab sesungguhnya.

Sebagai contoh, ketika sampah menumpuk di sudut-sudut kota, solusi yang sering muncul adalah menambah truk pengangkut atau membuat aplikasi pelaporan sampah. Namun, jika akar masalahnya terletak pada jadwal pengangkutan yang tidak teratur di tingkat rukun warga, maka solusi tersebut tidak akan menuntaskan persoalan.

Modul 1.3 membantu kita melakukan dua hal:
1. **Memilih satu isu prioritas** dari beberapa kandidat, menggunakan metode APKL dan USG.
2. **Menemukan akar masalah** dari isu prioritas tersebut, menggunakan Diagram Fishbone, teknik 5 Whys, serta Iceberg Model.

---

## 3. Gejala, Penyebab Antara, dan Akar Masalah

Sebelum melakukan analisis, kita perlu memahami bahwa suatu persoalan perkotaan memiliki beberapa lapisan.

![Gejala, Penyebab Antara, dan Akar Masalah](./assets/kausalitas_akar_masalah.jpg)

### 3.1 Gejala

Gejala adalah kondisi permukaan yang langsung terlihat atau dirasakan.

Gejala biasanya menjadi hal yang pertama kali dikeluhkan masyarakat atau diberitakan media.

Contoh:
> Waktu tempuh bus kota pada jam sibuk meningkat menjadi 75 menit.

Gejala menunjukkan ada yang tidak beres. Namun, gejala belum menjelaskan **mengapa** kondisi tersebut terjadi.

Jika kita hanya mengatasi gejala, masalah yang sama akan muncul kembali.

---

### 3.2 Penyebab Antara

Penyebab antara adalah faktor yang secara langsung memicu timbulnya gejala. Faktor ini berada di lapisan tengah rantai sebab-akibat.

Contoh:
> Bus kota terjebak antrean kendaraan pribadi di persimpangan tanpa lajur khusus.

Banyak orang berhenti pada lapisan ini dan langsung merancang solusi. Padahal, masih ada pertanyaan yang lebih dalam: mengapa persimpangan tersebut tidak memiliki lajur khusus?

---

### 3.3 Akar Masalah

Akar masalah adalah penyebab paling mendasar. Jika akar masalah berhasil diatasi, masalah yang sama tidak akan terulang.

Akar masalah perkotaan biasanya berkaitan dengan:
- kelemahan kebijakan atau regulasi daerah;
- ketiadaan prosedur kerja standar (SOP);
- rendahnya kompetensi atau kesadaran aparatur dan masyarakat;
- kegagalan integrasi sistem data dan teknologi;
- atau alokasi anggaran yang tidak tepat sasaran.

Contoh:
> Belum ada regulasi pemberian hak lintas (*right of way*) untuk angkutan umum massal, dan belum ada integrasi lampu lalu lintas adaptif di pusat kendali.

> **Prinsip:**  
> Solusi Smart City yang baik harus diarahkan pada akar masalah, bukan pada gejala.

---

## 4. Mengapa Perlu Penyaringan dan Pemeringkatan?

Dari Modul 1.2, kita telah menghasilkan tiga kandidat isu. Semua isu tersebut mungkin valid dan didukung bukti.

Namun, kota memiliki keterbatasan:

```text
            BANYAK ISU PERKOTAAN
                     │
                     ▼
       ┌───────────────────────────┐
       │ KETERBATASAN SUMBER DAYA  │
       │ - Anggaran (APBD)         │
       │ - Waktu dan Tenaga        │
       │ - Kapasitas Teknologi     │
       │ - Prioritas RKPD/RPJMD   │
       └─────────────┬─────────────┘
                     │
                     ▼
         PENYARINGAN & PEMERINGKATAN
           (Metode APKL & USG)
                     │
                     ▼
            ISU PRIORITAS UTAMA
```

Untuk itu, kita perlu melalui dua tahap:
1. **Penyaringan (APKL)**: Menguji apakah setiap isu layak untuk diangkat.
2. **Pemeringkatan (USG)**: Dari isu yang layak, menentukan mana yang paling mendesak.

---

## 5. Penyaringan Isu dengan Metode APKL

Metode APKL digunakan untuk menguji kelayakan suatu isu sebelum diprioritaskan. Metode ini banyak digunakan dalam perencanaan kebijakan publik di Indonesia, termasuk dalam pedoman analisis isu dari Lembaga Administrasi Negara (LAN RI).

APKL menguji empat hal:

```text
                        APKL
                          │
       ┌──────────┬───────┴───────┬──────────┐
       ↓          ↓               ↓          ↓
    Aktual    Problematik    Kekhalayakan  Kelayakan
```

### 5.1 Aktual (A)

Apakah isu ini benar-benar sedang terjadi saat ini?

Isu yang aktual didukung oleh data terbaru (1–2 tahun terakhir), menjadi pembicaraan publik, atau tercantum dalam agenda pemerintah kota.

Isu yang sudah lama mereda atau belum terbukti secara empiris memiliki nilai aktualitas rendah.

---

### 5.2 Problematik (P)

Apakah isu ini benar-benar bermasalah dan perlu solusi?

Isu problematik memiliki kesenjangan (*gap*) yang besar antara kondisi nyata dan kondisi yang diharapkan. Isu ini menimbulkan dampak negatif dan mendesak untuk diselesaikan.

---

### 5.3 Kekhalayakan (K)

Apakah isu ini menyangkut kepentingan orang banyak?

Isu dengan kekhalayakan tinggi berdampak pada masyarakat luas, bukan hanya segelintir kelompok tertentu. Contohnya: akses transportasi umum, kualitas air bersih, atau pengelolaan sampah kota.

---

### 5.4 Kelayakan (L)

Apakah isu ini realistis untuk diselesaikan?

Isu yang layak berada dalam batas kewenangan pemerintah kota dan dapat diintervensi melalui inovasi teknologi, perbaikan proses, atau perubahan kebijakan daerah.

Isu yang berada di luar kewenangan kota (misalnya kebijakan moneter nasional) memiliki kelayakan rendah.

---

### 5.5 Rubrik Penilaian APKL

Setiap dimensi dinilai dengan skala 1 sampai 5. Berikut panduan penilaiannya:

#### Aktual (A)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Sedang terjadi saat ini; didukung data terbaru (kurang dari 1 tahun); menjadi sorotan publik dan prioritas pemkot |
| **4** | Terjadi berulang dalam 1–2 tahun terakhir; konsisten diberitakan dan tercantum dalam laporan dinas |
| **3** | Bersifat periodik atau musiman; didukung data 2–3 tahun terakhir |
| **2** | Mulai mereda; jarang tercatat di laporan resmi |
| **1** | Sudah terselesaikan di masa lalu; atau belum terbukti secara empiris |

#### Problematik (P)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Sangat kompleks; menimbulkan kerugian lintas sektor; sangat mendesak ditangani |
| **4** | Kompleks; mengganggu efisiensi layanan publik dan aktivitas ekonomi kota |
| **3** | Berdimensi sedang; dampak negatif terbatas pada sektor tertentu |
| **2** | Sederhana; gangguan bersifat minor dan masih terkendali |
| **1** | Tidak menimbulkan kerugian atau penyimpangan yang berarti |

#### Kekhalayakan (K)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Berdampak pada sebagian besar warga kota atau seluruh kawasan strategis |
| **4** | Berdampak pada banyak warga atau mencakup beberapa kecamatan utama |
| **3** | Berdampak pada sebagian warga atau terkonsentrasi di wilayah tertentu |
| **2** | Berdampak pada kelompok kecil atau wilayah terbatas |
| **1** | Hanya berdampak pada segelintir individu atau organisasi tertentu |

#### Kelayakan (L)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Sepenuhnya dalam wewenang pemkot; solusi teknologi sangat aplikatif dan realistis |
| **4** | Dalam wewenang pemkot; membutuhkan koordinasi moderat antar-dinas |
| **3** | Cukup realistis; namun membutuhkan penyesuaian regulasi atau anggaran yang signifikan |
| **2** | Kurang realistis; kewenangan utama berada di tingkat provinsi atau pusat |
| **1** | Tidak realistis untuk diselesaikan oleh pemkot; di luar kapabilitas yang ada |

---

### 5.6 Formula dan Ambang Batas

Total skor APKL dihitung dengan menjumlahkan keempat nilai:

> **Total Skor APKL = A + P + K + L**

Rentang skor: **4** (terendah) sampai **20** (tertinggi).

Aturan kelolosan:
- **Memenuhi Syarat**: Total skor 12 atau lebih, dan nilai Kelayakan (L) tidak bernilai 1.
- **Tidak Memenuhi Syarat**: Total skor di bawah 12, atau nilai L sama dengan 1. Isu ini tidak dilanjutkan ke tahap USG.

---

## 6. Pemeringkatan Isu dengan Metode USG

Isu-isu yang memenuhi syarat pada tahap APKL selanjutnya diperingkat menggunakan metode USG.

Jika APKL menjawab *"Apakah isu ini layak?"*, maka USG menjawab *"Dari yang layak, mana yang paling mendesak?"*

USG menilai tiga dimensi:

```text
                          USG
                           │
            ┌──────────────┼──────────────┐
            ↓              ↓              ↓
         Urgency      Seriousness       Growth
       (Ketersediaan  (Keparahan      (Kecepatan
          Waktu)        Dampak)       Memburuk)
```

### 6.1 Urgency (U) — Seberapa Mendesak?

Urgency menilai apakah isu ini membutuhkan tindakan segera.

Pertanyaan panduan:
- Apakah isu ini harus ditangani sekarang juga, atau bisa menunggu?
- Apa yang terjadi jika penanganan ditunda satu tahun?

---

### 6.2 Seriousness (S) — Seberapa Parah Dampaknya?

Seriousness menilai seberapa besar kerugian yang ditimbulkan oleh isu ini.

Kerugian dapat berupa:
- ancaman terhadap keselamatan dan kesehatan masyarakat;
- kerugian ekonomi dan perlambatan aktivitas kota;
- kerusakan lingkungan hidup;
- atau penurunan kualitas pelayanan publik.

---

### 6.3 Growth (G) — Seberapa Cepat Memburuk?

Growth menilai apakah isu ini akan semakin parah jika dibiarkan.

Pertanyaan panduan:
- Apakah dampak isu ini stabil, atau justru bertambah buruk dari waktu ke waktu?
- Apakah penundaan akan menimbulkan masalah ikutan yang lebih besar?

---

### 6.4 Rubrik Penilaian USG

#### Urgency (U)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Sangat mendesak; penundaan dalam hitungan minggu berakibat fatal bagi layanan kota |
| **4** | Mendesak; perlu penanganan dalam 3–6 bulan ke depan agar tidak meluas |
| **3** | Cukup mendesak; dapat dijadwalkan dalam siklus perencanaan tahunan (RKPD) |
| **2** | Kurang mendesak; penundaan tidak berdampak langsung pada stabilitas kota |
| **1** | Tidak mendesak; dapat ditunda tanpa konsekuensi yang berarti |

#### Seriousness (S)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Dampak sangat berat; berpotensi menimbulkan korban jiwa, kerugian ekonomi masif, atau kerusakan lingkungan permanen |
| **4** | Dampak berat; mengganggu produktivitas kota secara signifikan dan memicu biaya pemulihan tinggi |
| **3** | Dampak sedang; menimbulkan inefisiensi dan keluhan warga yang masih dapat dikelola |
| **2** | Dampak ringan; ketidaknyamanan minor pada kelompok terbatas |
| **1** | Dampak tidak signifikan; tidak menimbulkan kerugian yang nyata |

#### Growth (G)

| Nilai | Keterangan |
| :---: | :--- |
| **5** | Memburuk sangat cepat; eskalasi eksponensial dalam waktu singkat jika dibiarkan |
| **4** | Memburuk cepat; dampak meluas ke sektor lain dalam waktu kurang dari 1 tahun |
| **3** | Memburuk bertahap; seiring pertumbuhan penduduk dan aktivitas kota |
| **2** | Relatif stabil; tidak menunjukkan indikasi penyebaran yang signifikan |
| **1** | Statis; tidak ada risiko peningkatan keparahan di masa mendatang |

---

### 6.5 Formula dan Penentuan Peringkat

Total skor USG dihitung dengan menjumlahkan ketiga nilai:

> **Total Skor USG = U + S + G**

Rentang skor: **3** (terendah) sampai **15** (tertinggi).

Isu dengan total skor USG tertinggi menempati **Peringkat 1** dan ditetapkan sebagai **isu prioritas utama**.

> **Aturan jika skor sama (*tie-breaker*):**  
> Jika dua isu memiliki total skor yang sama, bandingkan secara berurutan:  
> 1. Nilai Urgency (U) tertinggi;  
> 2. Jika U sama, nilai Seriousness (S) tertinggi;  
> 3. Jika S sama, nilai Growth (G) tertinggi.

---

## 7. Perbedaan APKL dan USG

Kedua metode ini memiliki fungsi yang berbeda dan digunakan secara berurutan:

| | APKL | USG |
| :--- | :--- | :--- |
| **Fungsi** | Menapis kelayakan isu | Memperingkat isu berdasarkan kegawatan |
| **Pertanyaan** | *"Apakah isu ini layak diangkat?"* | *"Dari yang layak, mana yang paling mendesak?"* |
| **Posisi** | Tahap pertama (filter) | Tahap kedua (ranking) |
| **Hasil** | Status: Memenuhi Syarat / Gugur | Peringkat: 1, 2, 3, dst. |

APKL tanpa USG hanya menghasilkan daftar isu yang valid. USG tanpa APKL berisiko memeringkat isu yang seharusnya tidak layak diangkat.

Keduanya saling melengkapi.

---

## 8. Diagram Fishbone (Ishikawa)

Setelah menetapkan satu isu prioritas, langkah berikutnya adalah menemukan **mengapa** isu tersebut terjadi.

Diagram Fishbone (juga disebut diagram Ishikawa atau diagram tulang ikan) digunakan untuk memetakan hubungan antara suatu masalah dengan faktor-faktor penyebabnya secara terstruktur.

Diagram ini dikembangkan oleh Kaoru Ishikawa dan banyak digunakan dalam analisis kualitas serta pemecahan masalah.

### 8.1 Struktur Diagram Fishbone

![Struktur Diagram Fishbone](./assets/struktur_diagram_fishbone.png)

Diagram ini terdiri dari:

1. **Kepala Ikan**: Berisi rumusan masalah (*problem statement*) dari isu prioritas.
   - Jangan menuliskan satu kata seperti *"Macet"*.
   - Tuliskan kalimat masalah yang spesifik, misalnya: *"Tingginya waktu tunggu feeder WiraWiri yang mencapai 25–35 menit pada jam sibuk di koridor komuter utama."*
2. **Tulang Belakang**: Garis horizontal utama yang mengarah ke kepala ikan.
3. **Tulang Utama**: Kategori besar faktor penyebab (misalnya People, Process, Technology).
4. **Tulang Cabang dan Ranting**: Penyebab yang lebih spesifik di dalam setiap kategori, diturunkan melalui pertanyaan *"Mengapa?"*.

---

### 8.2 Kategori Penyebab untuk Konteks Smart City

Dalam konteks perkotaan dan Smart City, kita dapat menggunakan 5 sampai 6 kategori berikut:

1. **People (Masyarakat & Aparatur)**  
   Kompetensi petugas, kepatuhan warga terhadap aturan, literasi digital, atau resistensi terhadap perubahan.

2. **Process (Prosedur & Alur Kerja)**  
   SOP yang tidak jelas, birokrasi yang berbelit, koordinasi antar-dinas yang lemah, atau mekanisme pengawasan yang tidak berjalan.

3. **Technology (Sistem & Infrastruktur Digital)**  
   Keandalan perangkat keras, sensor IoT yang tidak berfungsi, server yang sering *down*, atau aplikasi yang tidak terintegrasi satu sama lain.

4. **Data & Resources (Data, Anggaran, & Fasilitas)**  
   Data yang tidak mutakhir, format data antar-dinas yang berbeda, keterbatasan anggaran, atau kekurangan armada dan fasilitas fisik.

5. **Environment (Lingkungan & Geografi)**  
   Topografi wilayah (cekungan, pesisir), cuaca ekstrem, tata guna lahan, atau kepadatan pemukiman.

6. **Policy & Governance (Regulasi & Kebijakan) — opsional**  
   Peraturan daerah yang tumpang tindih, ketidakjelasan wewenang, atau lemahnya penegakan sanksi.

> **Catatan — Lensa Triple Transition:**  
> Dalam mengisi kategori Fishbone, kita juga dapat mempertimbangkan kerangka *Triple Transition* (Green, Digital, Inclusive) yang diperkenalkan oleh Prof. Rizal Sebastian pada CITIES International Conference 2025 di Surabaya. Kerangka ini membantu memastikan bahwa analisis penyebab mencakup tiga dimensi transisi kota cerdas secara seimbang:
>
> | Transisi | Pertanyaan Panduan untuk Fishbone |
> | :--- | :--- |
> | **Green** | Apakah penyebab ini berkaitan dengan keberlanjutan lingkungan, emisi karbon, atau ketahanan iklim? |
> | **Digital** | Apakah penyebab ini berkaitan dengan keterhubungan sistem, adaptasi terhadap kebutuhan pengguna, atau optimasi otomatis? |
> | **Inclusive** | Apakah penyebab ini memperburuk ketimpangan sosial, mengabaikan kelompok rentan, atau menghambat partisipasi warga? |

---

### 8.3 Perbedaan Issue Tree dan Fishbone

Kedua metode ini terkadang membingungkan atau keliru disamakan. Berikut perbedaannya:

| | Issue Tree (Modul 1.2) | Fishbone (Modul 1.3) |
| :--- | :--- | :--- |
| **Pertanyaan** | *"Dimensi mana yang perlu dipersempit?"* | *"Apa yang menyebabkan masalah ini terjadi?"* |
| **Fungsi** | Mempersempit ruang lingkup isu | Menelusuri penyebab dari isu yang sudah dipilih |
| **Isi cabang** | Aspek masalah (misal: tarif, rute, jadwal) | Faktor penyebab (misal: SOP tidak ada, server mati) |
| **Prinsip** | MECE (*Mutually Exclusive, Collectively Exhaustive*) | Cause & Effect dan teknik 5 Whys |

Singkatnya:
> Issue Tree memecah *"apa"* masalahnya. Fishbone menelusuri *"mengapa"* masalah itu terjadi.

---

## 9. Teknik 5 Whys

Teknik 5 Whys dilakukan dengan mengajukan pertanyaan *"Mengapa?"* secara berulang pada setiap cabang Fishbone, biasanya 3 sampai 5 kali, sampai ditemukan faktor paling mendasar yang berada dalam kendali sistem.

```text
MASALAH
    │
    ▼  Mengapa?
PENYEBAB TINGKAT 1 (kondisi di lapangan)
    │
    ▼  Mengapa?
PENYEBAB TINGKAT 2 (mekanisme operasional)
    │
    ▼  Mengapa?
PENYEBAB TINGKAT 3 (prosedur / kapasitas kerja)
    │
    ▼  Mengapa?
PENYEBAB TINGKAT 4 (kebijakan / sistem)
    │
    ▼  Mengapa?
AKAR MASALAH (root cause)
```

### 9.1 Contoh Penerapan

Misalkan isu prioritasnya adalah:  
*"Genangan air lambat surut di kawasan permukiman X setelah hujan deras."*

Berikut penurunan pada kategori **Process**:

| Tingkat | Pertanyaan | Jawaban |
| :--- | :--- | :--- |
| **Why 1** | Mengapa jalan tergenang? | Saluran drainase sekunder meluap karena pendangkalan sedimen |
| **Why 2** | Mengapa sedimen sangat tebal? | Pengerukan belum dilakukan sebelum musim hujan |
| **Why 3** | Mengapa pengerukan belum dilakukan? | Jadwal pengerukan tidak disusun berdasarkan data kondisi saluran |
| **Why 4** | Mengapa tidak ada jadwal berbasis data? | Pemeriksaan saluran masih dilakukan secara manual dan insidental |
| **Why 5** | **Mengapa pemeriksaan masih manual?** | **Belum ada sistem inventarisasi dan pemantauan aset drainase yang memicu jadwal pemeliharaan otomatis** |

Jawaban pada Why 5 adalah **akar masalah**.

> **Penting:**  
> Setiap jawaban "Mengapa" harus berdasarkan fakta atau data yang dapat diverifikasi, bukan spekulasi.

---

## 10. Analisis Berlapis dengan Iceberg Model

Selain Fishbone dan 5 Whys, kita dapat menggunakan **Iceberg Model** sebagai alat bantu untuk melihat isu secara lebih sistemik sebelum memetakan penyebab.

Iceberg Model dikembangkan dalam tradisi *systems thinking* dan banyak digunakan dalam analisis kebijakan publik. Model ini membagi sebuah persoalan ke dalam empat lapisan:

```text
┌─────────────────────────────────────────────────┐
│  ░░░░░░░░░░ PERMUKAAN AIR ░░░░░░░░░░░░░░░░░░░░ │
│                                                 │
│  1. EVENT (Peristiwa)                           │
│     Apa yang terjadi? Fakta yang tampak.         │
│                                                 │
│  ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─  │
│                                                 │
│  2. PATTERN (Pola)                              │
│     Apakah kejadian ini berulang atau tren?     │
│                                                 │
│  3. STRUCTURE (Struktur)                        │
│     Sistem, regulasi, kewenangan, atau          │
│     koordinasi apa yang membentuk pola ini?     │
│                                                 │
│  4. MENTAL MODEL (Model Mental)                 │
│     Asumsi, cara pandang, atau kebiasaan        │
│     berpikir apa yang melanggengkan struktur?   │
│                                                 │
└─────────────────────────────────────────────────┘
```

### 10.1 Penjelasan Setiap Lapisan

| Lapisan | Pertanyaan Kunci | Contoh (Isu Banjir Kota) |
| :--- | :--- | :--- |
| **Event** | Apa yang terjadi? | Genangan air merendam jalan utama setelah hujan deras |
| **Pattern** | Apakah ini berulang? | Banjir terjadi setiap musim hujan di titik yang sama selama 3 tahun terakhir |
| **Structure** | Sistem apa yang membentuk pola ini? | Tidak ada SOP pengerukan berkala; anggaran pemeliharaan drainase tidak mencukupi |
| **Mental Model** | Asumsi apa yang melanggengkan? | "Banjir adalah bencana alam yang wajar" — sehingga penanganan bersifat reaktif, bukan preventif |

### 10.2 Hubungan Iceberg Model dengan Fishbone dan 5 Whys

Ketiga metode ini saling melengkapi:

```text
  ICEBERG MODEL              FISHBONE                    5 WHYS
  ─────────────              ────────                    ──────
  Melihat lapisan            Memetakan penyebab          Menggali kedalaman
  masalah secara             ke dalam kategori           setiap cabang hingga
  vertikal (Event →          (People, Process,           akar masalah
  Pattern → Structure        Technology, dst.)
  → Mental Model)

  "Seberapa dalam            "Dari mana saja             "Mengapa itu
   masalah ini?"              penyebabnya?"               terjadi?"
```

Kita dapat menggunakan Iceberg Model sebagai langkah awal untuk memahami kedalaman isu, lalu menggunakan Fishbone untuk memetakan penyebab secara terstruktur, dan 5 Whys untuk menurunkan setiap cabang hingga akar masalah.

> **Tips Praktis:**  
> Isi tabel Iceberg terlebih dahulu sebelum menggambar Fishbone. Lapisan *Structure* dan *Mental Model* dari Iceberg sering kali menjadi akar masalah yang ditempatkan di ujung cabang Fishbone.

---

## 11. Alur Kerja Modul 1 Secara Keseluruhan

Berikut adalah hubungan antar-modul dari Modul 1.1 hingga 1.3:

```text
┌─────────────────────────────────────────────────────────────┐
│ MODUL 1.1 — Landasan Konseptual & Data Kota                 │
│ - Memahami 6 pilar Smart City                               │
│ - Mengumpulkan data sekunder (BPS, Satu Data, RKPD)         │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ MODUL 1.2 — Identifikasi dan Formulasi Isu                  │
│ - Observe → Explore (5W1H) → Issue Tree                     │
│ - Validasi bukti (Claim – Evidence – Source)                │
│ - Menghasilkan 3 kandidat isu                               │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ MODUL 1.3 — Penyaringan (APKL) & Pemeringkatan (USG)          │
│ - Menguji kelayakan isu                                     │
│ - Menentukan 1 isu prioritas utama                          │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ MODUL 1.3 — Analisis Akar Masalah (Iceberg, Fishbone, 5Whys)│
│ - Memahami kedalaman isu secara sistemik                    │
│ - Memetakan faktor penyebab & menemukan akar masalah        │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ MODUL BERIKUTNYA — Perancangan Solusi Smart City            │
│ - Merancang solusi yang menyelesaikan akar masalah          │
└─────────────────────────────────────────────────────────────┘
```

---

## 12. Contoh Terapan: Kota Surabaya

Berikut adalah contoh lengkap penerapan APKL, USG, dan Fishbone menggunakan kasus Kota Surabaya.

### 12.1 Tiga Kandidat Isu dari Modul 1.2

1. **Isu A — Smart Environment**  
   Penumpukan sampah di TPS wilayah Surabaya Timur pada akhir pekan.  
   Bukti: Data DLH menunjukkan volume sampah melonjak 28% di akhir pekan, keterlambatan pengangkutan mencapai 6 jam.

2. **Isu B — Smart Living (Mobilitas)**  
   Tingginya waktu tunggu armada feeder WiraWiri yang mencapai 25–35 menit pada jam sibuk.  
   Bukti: Standar Dishub menetapkan waktu tunggu maksimal 12 menit; survei mencatat penumpukan penumpang di 4 halte utama.

3. **Isu C — Smart Governance (Ekonomi)**  
   Rendahnya adopsi portal perizinan digital oleh pedagang mikro informal.  
   Bukti: Baru 18% pedagang mikro yang memperbarui NIB melalui layanan mandiri.

---

### 12.2 Tabel Penyaringan APKL

| No | Isu | A | P | K | L | Total | Status |
| :-: | :--- | :-: | :-: | :-: | :-: | :-: | :--- |
| 1 | **Isu A** — Penumpukan sampah TPS Surabaya Timur | 4 | 4 | 4 | 4 | **16** | Memenuhi Syarat |
| 2 | **Isu B** — Waktu tunggu feeder WiraWiri jam sibuk | 5 | 4 | 5 | 4 | **18** | Memenuhi Syarat |
| 3 | **Isu C** — Rendahnya adopsi perizinan digital UMKM | 3 | 3 | 3 | 4 | **13** | Memenuhi Syarat |

Justifikasi singkat:
- **Isu B** mendapat skor tertinggi karena transportasi umum terintegrasi merupakan program prioritas pemkot (A=5) dan menyangkut mobilitas ratusan ribu komuter harian (K=5).
- Ketiga isu memperoleh total skor di atas 12 dan tidak memiliki nilai L=1, sehingga ketiganya **memenuhi syarat** untuk masuk ke tahap USG.

---

### 12.3 Tabel Pemeringkatan USG

| No | Isu | U | S | G | Total | Peringkat |
| :-: | :--- | :-: | :-: | :-: | :-: | :--- |
| 1 | **Isu A** — Penumpukan sampah TPS Surabaya Timur | 4 | 4 | 4 | **12** | Peringkat 2 |
| 2 | **Isu B** — Waktu tunggu feeder WiraWiri jam sibuk | 5 | 5 | 4 | **14** | **Peringkat 1** |
| 3 | **Isu C** — Rendahnya adopsi perizinan digital UMKM | 3 | 3 | 3 | **9** | Peringkat 3 |

Justifikasi:
- **U=5** pada Isu B: Rute ekspansi feeder sedang dibuka tahun ini. Jika waktu tunggu tetap buruk, warga akan kembali menggunakan kendaraan pribadi dan program transportasi umum kehilangan kepercayaan publik.
- **S=5** pada Isu B: Keterlambatan memicu penumpukan penumpang dan memperparah kemacetan jalan arteri pada jam kerja.
- **G=4** pada Isu B: Dampak ketidakpercayaan warga berpotensi meluas ke rute koridor lain dalam 6–12 bulan.

**Keputusan: Isu B ditetapkan sebagai isu prioritas utama (Peringkat 1).**

---

### 12.4 Diagram Fishbone untuk Isu Prioritas

Rumusan masalah pada kepala ikan:  
*"Tingginya waktu tunggu armada feeder WiraWiri Surabaya (25–35 menit) pada jam sibuk di koridor komuter utama."*

```text
       PEOPLE                              PROCESS                        TECHNOLOGY
          \                                   \                               \
           \── Pengemudi terjebak              \── Jadwal keberangkatan        \── GPS tracker armada
            \  kemacetan arteri                 \  masih bersifat kaku          \  mengalami keterlambatan
             \                                   \                               \
              \── Mengapa? Tidak ada              \── Mengapa? Tidak ada          \── Mengapa? Pembaruan
               \  panduan rute alternatif          \  info lalu lintas             \  lokasi hanya tiap 3 mnt
                \                                   \  secara real-time             \
                 \── AKAR: Belum ada                 \── AKAR: Belum ada SOP        \── AKAR: Keterbatasan
                     pelatihan navigasi                  dispatch adaptif/              paket data IoT dan
                     dinamis berbasis data                dinamis                       spesifikasi modul
                      \                                   \                               \
───────────────────────┴───────────────────────────────────┴───────────────────────────────┴──────► [ KEPALA IKAN ]
                      /                                   /                                        HEADWAY WIRAWIRI
                     /── Tidak ada data jumlah           /── Jalan menyempit akibat                25-35 MENIT
                    /   penumpang di tiap halte          /   parkir liar di badan jalan
                   /                                   /
                  /── Mengapa? Halte belum ada         /── Mengapa? Pengawasan
                 /   sensor penghitung penumpang      /   petugas masih sporadis
                /                                   /
               /── AKAR: Data halte belum           /── AKAR: Lemahnya sistem
                   terintegrasi dengan                   tilang elektronik di
                   server pusat kendali                  koridor penyangga
                  /                                   /
       DATA & RESOURCES                     ENVIRONMENT & POLICY
```

---

## 13. Contoh Terapan: Kota Surakarta (Iceberg Model + 5 Whys)

Berikut contoh penerapan Iceberg Model dan 5 Whys pada kasus nyata di Kota Surakarta, diambil dari Modul Penyusunan Policy Brief (CivicLab Academy × ITS × Taktis Consulting, 2026).

### 13.1 Masalah Awal

Warga di sekitar TPA Putri Cempo, Surakarta, terganggu oleh bau sampah yang pekat.

### 13.2 Analisis Iceberg Model

| Lapisan | Temuan |
| :--- | :--- |
| **Event** | Bau sampah menyengat tercium warga di sekitar TPA |
| **Pattern** | Bau muncul berulang, terutama saat aktivitas pemilahan sampah aktif |
| **Structure** | Kinerja pengolahan hulu (TPS 3R) belum optimal; beban timbunan di blok TPA sudah sangat tinggi |
| **Mental Model** | Menganggap bau TPA sebagai risiko yang harus diterima warga tanpa perlu intervensi tata ruang dan kebijakan operasional |

### 13.3 Analisis 5 Whys

| Tingkat | Pertanyaan | Jawaban |
| :--- | :--- | :--- |
| **Why 1** | Mengapa bau sangat mengganggu? | Terbawa embusan angin langsung ke arah permukiman dan area ladang |
| **Why 2** | Mengapa bau semakin pekat di luar area TPA? | Intensitas bau melonjak saat sampah sedang aktif dipilah |
| **Why 3** | Mengapa penanganan timbunan belum meredam dampak? | Beban timbunan di blok-blok TPA sudah sangat tinggi (mencapai blok D) |
| **Why 4** | Mengapa beban TPA terus meluber? | Kinerja pengolahan dari hulu (TPS 3R) belum optimal mengurangi volume sampah masuk |
| **Why 5** | **Mengapa belum teratasi komprehensif?** | **Belum terintegrasinya data spasial aktivitas warga (peternakan/permukiman) dalam dokumen kebijakan pengelolaan sampah** |

### 13.4 Isu Strategis yang Dirumuskan

> *"Optimalisasi Kebijakan Pengelolaan Sampah Berbasis Mitigasi Dampak Spasial di TPA Putri Cempo Surakarta (Timeframe RPJMD 2025–2029)."*

Perhatikan bahwa akar masalah yang ditemukan bersifat **struktural dan sistemik** — bukan sekadar masalah teknis operasional, melainkan menyangkut integrasi data dalam dokumen kebijakan.

---

## 14. Contoh Identifikasi Permasalahan Kota Metropolitan: Jakarta

Sebagai referensi tambahan, berikut ringkasan permasalahan Kota Jakarta berdasarkan dimensi Smart City, diambil dari dokumen *Potret Kota Jakarta Menuju Kota Cerdas Berskala Global* (Pemprov DKI Jakarta, 2024).

Tabel ini menunjukkan bagaimana sebuah kota besar mengidentifikasi isu per pilar Smart City secara sistematis — langkah awal sebelum penyaringan dan pemeringkatan dilakukan.

| Dimensi | Permasalahan Utama | Data Pendukung |
| :--- | :--- | :--- |
| **Smart Environment** | Kualitas lingkungan menurun dan emisi karbon tetap tinggi | Kenaikan temperatur 1,1°C selama 47 tahun; cuaca ekstrem naik 15–26% |
| **Smart Economy** | Ketimpangan sosial meningkat | Rasio Gini naik dari 0,32 (2007) menjadi 0,431 (2023) |
| **Smart People** | Kualitas SDM belum kompetitif secara global | Global Talent Index: Jakarta 30,1 vs Singapura 77,1 vs London 60,9 |
| **Smart Mobility** | Pergerakan manusia dan barang lambat | Rata-rata tempuh 18,75 km dalam 51 menit (Tokyo: 29,52 km dalam 38 menit) |
| **Smart Living** | Kualitas hidup tertinggal di kancah global | Rasio rumah layak huni turun dari 99,36% (2018) menjadi 38,8% (2023) |
| **Smart Branding** | *City branding* belum optimal | Wisatawan mancanegara: Jakarta 1,96 juta vs Singapura 13,6 juta |
| **Smart Government** | Transformasi digital pelayanan publik masih berjalan | Target percepatan SPBE dan ekosistem kota cerdas |

> **Catatan:**  
> Tabel di atas menunjukkan tahap awal identifikasi isu. Setelah isu-isu ini dikumpulkan, langkah selanjutnya adalah kita melakukan penyaringan (APKL) dan pemeringkatan (USG) untuk menentukan mana yang menjadi prioritas — persis seperti yang kita praktikkan di Modul 1.3.

---

## 15. Panduan Praktikum

### 15.1 Langkah Kerja

1. **Ambil 3 kandidat isu** dari penugasan Modul 1.2.
2. **Buat lembar kerja spreadsheet** (Excel atau Google Sheets) dengan dua tabel:
   - Tabel Penyaringan APKL
   - Tabel Pemeringkatan USG
3. **Isi skor 1–5** untuk setiap kriteria. Tuliskan justifikasi di kolom atau baris terpisah.
4. **Gunakan rumus aktif** untuk menghitung total skor dan ranking. Jangan mengetik angka secara manual.
5. **Buat Diagram Fishbone** untuk isu yang menempati Peringkat 1. Gunakan minimal 4–5 kategori dan turunkan setiap cabang dengan teknik 5 Whys.
6. **Ekspor** Fishbone ke format PNG dan simpan spreadsheet dalam format XLSX.

---

### 15.2 Contoh Tata Letak Spreadsheet

```text
TABEL PENYARINGAN APKL
┌────┬──────┬─────────────────────────┬───┬───┬───┬───┬────────────┬──────────────────┐
│ No │ Kode │   Rumusan Isu           │ A │ P │ K │ L │ Total Skor │ Status           │
├────┼──────┼─────────────────────────┼───┼───┼───┼───┼────────────┼──────────────────┤
│  1 │ ISU1 │ [Teks rumusan...]       │ 4 │ 4 │ 4 │ 4 │  =SUM()    │ =IF(Total>=12..) │
└────┴──────┴─────────────────────────┴───┴───┴───┴───┴────────────┴──────────────────┘

TABEL PEMERINGKATAN USG
┌────┬──────┬─────────────────────────┬───┬───┬───┬────────────┬──────────────────┐
│ No │ Kode │   Rumusan Isu           │ U │ S │ G │ Total Skor │ Peringkat (Rank) │
├────┼──────┼─────────────────────────┼───┼───┼───┼────────────┼──────────────────┤
│  1 │ ISU1 │ [Teks rumusan...]       │ 5 │ 5 │ 4 │  =SUM()    │ =RANK.EQ(...)    │
└────┴──────┴─────────────────────────┴───┴───┴───┴────────────┴──────────────────┘
```

---

### 15.3 Formula yang Wajib Digunakan

**Seluruh total skor dan ranking harus menggunakan rumus aktif. Dilarang mengetik angka manual.**

1. **Total skor APKL** (misal baris 4, kolom D sampai G):
   ```
   =SUM(D4:G4)
   ```
2. **Total skor USG** (misal baris 4, kolom D sampai F):
   ```
   =SUM(D4:F4)
   ```
3. **Ranking otomatis** (misal total skor USG di kolom G, baris 4–6):
   ```
   =RANK.EQ(G4, $G$4:$G$6, 0)
   ```
   Fungsi ini membandingkan nilai pada sel G4 terhadap seluruh total skor di G4:G6. Angka `0` berarti urutan menurun, sehingga skor tertinggi mendapat Rank 1.

4. **Status kelolosan APKL** (opsional):
   ```
   =IF(H4>=12, "Memenuhi Syarat", "Gugur")
   ```

---

### 15.4 Pembuatan Diagram Fishbone

Diagram Fishbone dapat dibuat menggunakan:
- **Draw.io / Diagrams.net** (disarankan, gratis)
- **Miro**
- **Canva**
- **FigJam / Figma**

Ketentuan:
- Kepala ikan harus berisi rumusan masalah yang spesifik.
- Minimal 4 sampai 5 kategori tulang utama.
- Setiap cabang diturunkan menggunakan teknik 5 Whys.
- Teks harus terbaca jelas, tidak terpotong.
- Ekspor dalam format **PNG** dengan resolusi minimal 1920 × 1080 piksel.

---

## 16. Luaran dan Ketentuan Pengumpulan

Kita perlu mengunggah dua berkas:

1. **Diagram Fishbone**
   - Format: `.png`
   - Nama file: `T1.3_Fishbone_[NRP]_[Nama].png`
   - Contoh: `T1.3_Fishbone_5026221001_AhmadFauzi.png`

2. **Lembar Kerja Skoring**
   - Format: `.xlsx` (berisi rumus aktif)
   - Nama file: `T1.4_Skoring_[NRP]_[Nama].xlsx`
   - Contoh: `T1.4_Skoring_5026221001_AhmadFauzi.xlsx`

---

## 17. Rubrik Penilaian

### 17.1 T1.3 — Diagram Fishbone (20 Poin)

| Kriteria | Sangat Baik (85–100%) | Cukup (65–84%) | Kurang (0–64%) | Bobot |
| :--- | :--- | :--- | :--- | :---: |
| **Kepala Ikan & Kategori** | Rumusan masalah spesifik dan berkonteks; 4–5 kategori relevan | Rumusan cukup jelas tapi agak umum; kategori ada yang tumpang tindih | Rumusan hanya kata umum ("Macet"); kurang dari 3 kategori | **5** |
| **Kedalaman 5 Whys** | Cabang diturunkan 3–5 lapis hingga akar masalah sistemik yang jelas | Cabang 2 lapis; masih mencampur gejala dengan akar masalah | Cabang 1 lapis saja; tidak tampak penerapan 5 Whys | **8** |
| **Validitas Bukti** | Seluruh penyebab konsisten dengan data dari Modul 1.1 dan 1.2 | Sebagian masuk akal, tapi beberapa cabang bersifat asumsi | Didominasi asumsi tanpa dasar data | **4** |
| **Kualitas Visual** | Rapi, proporsional, teks tajam, PNG resolusi tinggi | Cukup rapi, teks terbaca, resolusi standar | Berantakan, tulisan buram, format tidak sesuai | **3** |

---

### 17.2 T1.4 — Skoring APKL & USG (25 Poin)

| Kriteria | Sangat Baik (85–100%) | Cukup (65–84%) | Kurang (0–64%) | Bobot |
| :--- | :--- | :--- | :--- | :---: |
| **Justifikasi APKL** | Setiap skor A, P, K, L disertai narasi berbasis data yang jelas dan mengacu rubrik | Narasi ada tapi bersifat umum, minim rujukan data | Tidak ada narasi, atau narasi disalin-tempel antar-isu | **7** |
| **Justifikasi USG** | Narasi U, S, G logis dan membedakan derajat kegawatan antar-isu | Narasi ada tapi argumen U dan S masih tumpang tindih | Tidak ada argumentasi logis atau deskripsi kosong | **7** |
| **Rumus Spreadsheet** | Seluruh total dan ranking menggunakan rumus aktif (`SUM`, `RANK.EQ`) | Rumus penjumlahan aktif, tapi ranking diketik manual | Seluruh angka diketik manual tanpa rumus | **6** |
| **Konsistensi & Format** | Isu Peringkat 1 konsisten menjadi subjek Fishbone; spreadsheet rapi | Isu konsisten, tapi tata letak kurang rapi | Isu Fishbone berbeda dari hasil ranking; format tidak sesuai | **5** |

---

## 18. Kesalahan Umum

Berikut kesalahan yang sering terjadi dan harus dihindari:

### Kesalahan 1 — Skor tanpa justifikasi
Memberikan nilai tanpa menuliskan alasan. Setiap skor harus disertai kalimat penjelasan mengapa nilai tersebut diberikan.

---

### Kesalahan 2 — Angka manual di spreadsheet
Menghitung total skor di luar spreadsheet lalu mengetiknya secara manual. Penilai akan memeriksa apakah sel-sel tersebut berisi rumus aktif.

---

### Kesalahan 3 — Fishbone berisi "ketiadaan solusi"
Menuliskan cabang seperti *"Belum ada aplikasi X"* atau *"Tidak tersedianya sensor Y"*. Fishbone mencari **penyebab masalah**, bukan mendaftar teknologi yang belum ada.

---

### Kesalahan 4 — Berhenti di gejala
Menuliskan penyebab yang sekadar mengulang gejala luar, misalnya *"Karena jalanan padat"*. Pertanyaan berikutnya yang harus diajukan adalah: *"Mengapa jalanan padat?"*

---

### Kesalahan 5 — Kategori tumpang tindih
Memasukkan faktor prosedur kerja ke kategori People, atau memasukkan faktor kebijakan ke kategori Environment. Setiap cabang harus ditempatkan pada kategori yang paling tepat.

---

### Kesalahan 6 — Isu baru tanpa bukti
Memunculkan isu baru di Modul 1.3 yang tidak pernah diobservasi atau divalidasi pada Modul 1.1 dan 1.2.

---

### Kesalahan 7 — Menyamakan Urgency dan Seriousness
Suatu masalah bisa sangat serius dampaknya, tetapi tidak mendesak jika tenggat penanganannya masih panjang. Urgency adalah soal **waktu**, Seriousness adalah soal **dampak**.

---

### Kesalahan 8 — Mengabaikan konteks kota
Menyusun penyebab secara teoretis umum tanpa memperhatikan kondisi nyata, geografi, dan kebijakan dari kota yang menjadi objek studi.

---

## 19. Ringkasan

| Tahap | Metode | Pertanyaan | Hasil |
| :--- | :--- | :--- | :--- |
| **Penyaringan** | APKL | *"Apakah isu ini layak diangkat?"* | Status kelayakan setiap isu |
| **Pemeringkatan** | USG | *"Mana yang paling mendesak?"* | Isu Peringkat 1 (prioritas utama) |
| **Pemahaman Sistemik** | Iceberg Model | *"Seberapa dalam masalah ini?"* | Kedalaman masalah (Event hingga Mental Model) |
| **Analisis Sebab** | Fishbone | *"Faktor apa yang menyebabkan masalah ini?"* | Peta penyebab berdasarkan kategori |
| **Penelusuran** | 5 Whys | *"Mengapa itu terjadi?"* | Akar masalah yang siap diintervensi |

> **Inti Modul 1.3:**  
> Menemukan akar masalah dan menetapkan satu isu prioritas secara terukur, agar solusi Smart City yang dirancang pada tahap selanjutnya benar-benar menyelesaikan sumber persoalan, bukan sekadar mengobati gejala.

---

## Daftar Pustaka

1. Andersen, B., & Fagerhaug, T. (2006). *Root Cause Analysis: Simplified Tools and Techniques* (2nd ed.). ASQ Quality Press.
2. CivicLab Academy, Taktis Consulting, & Institut Teknologi Sepuluh Nopember. (2026). *Modul Penyusunan Policy Brief: Dari Isu Strategis Menuju Rekomendasi Kebijakan*.
3. International Telecommunication Union. (2022). *Recommendation ITU-T Y.4903: Key performance indicators for smart sustainable cities to assess the achievement of the Sustainable Development Goals*. ITU.
4. Ishikawa, K. (1982). *Guide to Quality Control*. Asian Productivity Organization.
5. Ishikawa, K. (1986). *What is Total Quality Control? The Japanese Way*. Prentice-Hall.
6. Kementerian Komunikasi dan Digital Republik Indonesia. (2023). *Panduan Implementasi dan Masterplan Smart City Daerah*. Kemkomdigi RI.
7. Kepner, C. H., & Tregoe, B. B. (1997). *The New Rational Manager: An Updated Edition for a New World*. Princeton Research Press.
8. Lembaga Administrasi Negara Republik Indonesia (LAN RI). (2021). *Modul Pelatihan Kepemimpinan: Analisis Isu Kontemporer dan Teknik Analisis Kebijakan Publik*. Pusdiklat LAN RI.
9. Pemerintah Provinsi Daerah Khusus Jakarta. (2024). *Potret Kota Jakarta Menuju Kota Cerdas Berskala Global* (Buku 1). Jakarta Smart City.
10. Sebastian, R. (2025). *Creating smart, sustainable and inclusive cities* [Keynote speech]. CITIES International Conference, Surabaya.
11. UN-Habitat. (2024). *International Guidelines on People-Centred Smart Cities*. United Nations Human Settlements Programme.
