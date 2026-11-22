# PRODUCT REQUIREMENTS DOCUMENT (PRD)

## Fitur: Ulasan Relevan – Tokopedia

- **Versi:** 1.0
- **Platform:** Tokopedia
- **Jenis Produk:** Fitur pendukung evaluasi ulasan produk
- **Status:** Draft

---

## 1. Product Overview

### 1.1 Background

Tokopedia menyediakan fitur ulasan produk yang memungkinkan pengguna melihat pengalaman pembeli lain sebelum melakukan pembelian. Namun, banyaknya ulasan dapat menyulitkan pengguna dalam menemukan informasi yang benar-benar relevan dengan kebutuhan mereka.

Pengguna perlu membaca dan membandingkan sejumlah ulasan untuk mengetahui kualitas produk, fungsi, kesesuaian produk dengan deskripsi penjual, serta kekurangan yang mungkin ditemukan setelah pembelian. Informasi penting juga dapat tersebar di antara ulasan singkat atau ulasan yang lebih banyak membahas proses pengiriman.

Selain itu, pengguna membutuhkan ulasan yang disertai foto agar dapat membandingkan kondisi produk yang diterima pembeli dengan gambar dan deskripsi dari penjual.

Kondisi tersebut membuat proses evaluasi produk membutuhkan waktu lebih lama dan dapat menimbulkan keraguan sebelum pengguna mengambil keputusan pembelian. Oleh karena itu, diperlukan fitur yang membantu pengguna menemukan dan memahami informasi penting dari ulasan secara lebih cepat dan terstruktur.

### 1.2 Product Vision

Membantu pengguna Tokopedia menemukan dan memahami ulasan produk yang paling relevan secara cepat dan terstruktur, sehingga pengguna dapat mengevaluasi produk dengan lebih mudah dan yakin sebelum melakukan pembelian.

### 1.3 Target User

Target pengguna fitur ini adalah pengguna Tokopedia yang membaca ulasan produk sebelum melakukan pembelian, khususnya pengguna yang:

- Ingin mengetahui kualitas dan fungsi produk berdasarkan pengalaman pembeli lain.
- Membutuhkan informasi mengenai kelebihan dan kekurangan produk.
- Ingin mengetahui kesesuaian kondisi produk dengan foto dan deskripsi penjual.
- Membutuhkan ulasan yang disertai foto sebagai bahan pertimbangan.
- Mengalami kesulitan menemukan informasi penting di antara banyaknya ulasan.

---

## 2. User Problem

### 2.1 Daftar Permasalahan Pengguna

| ID | Permasalahan | Dampak terhadap Pengguna |
|---|---|---|
| P-01 | Pengguna kesulitan menemukan ulasan berdasarkan aspek produk tertentu. | Pengguna harus membaca banyak ulasan untuk mendapatkan informasi yang dibutuhkan. |
| P-02 | Informasi mengenai kelebihan dan kekurangan produk tersebar di berbagai ulasan. | Pengguna membutuhkan waktu lebih lama untuk mengevaluasi produk. |
| P-03 | Pengguna kesulitan mengetahui apakah keluhan tertentu sering dialami pembeli lain atau hanya terjadi pada satu pembeli. | Pengguna mengalami keraguan dalam menilai risiko produk. |
| P-04 | Pengguna kesulitan menemukan ulasan yang disertai foto. | Pengguna membutuhkan usaha tambahan untuk membandingkan kondisi produk dengan deskripsi penjual. |

### 2.2 Problem Statement

Pengguna Tokopedia membutuhkan cara yang lebih mudah untuk menemukan dan memahami informasi penting dari ulasan produk karena banyaknya ulasan membuat informasi mengenai kualitas, fungsi, kekurangan, keluhan, dan kesesuaian produk sulit ditemukan. Akibatnya, proses evaluasi produk menjadi lebih lama dan keputusan pembelian dapat disertai keraguan.

---

## 3. User Persona

- **Nama:** Muhammad Alfarizi Hardiansyah
- **Usia:** 21 tahun
- **Pekerjaan:** Mahasiswa
- **Platform:** Tokopedia

> **Catatan:** Persona ini merupakan persona representatif yang disusun berdasarkan rangkuman pola kebutuhan pengguna pada tahap penelitian, bukan identitas satu responden tertentu.

### 3.1 Karakteristik

- Membaca ulasan sebelum membeli produk.
- Membandingkan rating dan pengalaman pembeli lain.
- Lebih tertarik pada ulasan yang menjelaskan pengalaman penggunaan secara terperinci.
- Memperhatikan ulasan yang disertai foto.
- Mempertimbangkan kekurangan produk sebelum melakukan pembelian.

### 3.2 Goals

- Menemukan informasi kualitas dan fungsi produk dengan cepat.
- Mengetahui kelebihan dan kekurangan produk.
- Memastikan kesesuaian produk dengan foto dan deskripsi penjual.
- Mengambil keputusan pembelian dengan lebih yakin tanpa harus membaca seluruh ulasan.

### 3.3 Pain Points

- Kesulitan menemukan ulasan yang sesuai dengan kebutuhan.
- Informasi penting tersebar di antara banyak ulasan.
- Membutuhkan waktu untuk membandingkan pengalaman pembeli.
- Sulit mengetahui apakah suatu keluhan merupakan masalah yang sering terjadi.
- Kesulitan menemukan ulasan yang memiliki foto.

---

## 4. Product Goals & Success Metrics

### 4.1 Product Goals

1. Mempermudah pengguna menemukan ulasan berdasarkan aspek produk yang ingin dievaluasi.
2. Membantu pengguna memahami kelebihan, kekurangan, dan keluhan yang sering muncul.
3. Mempermudah pengguna menemukan ulasan yang disertai foto.
4. Mengurangi usaha dan waktu yang diperlukan pengguna untuk mengevaluasi produk sebelum membeli.

### 4.2 Success Metrics

| ID | Indikator Keberhasilan | Target Awal |
|---|---|---|
| SM-01 | Keberhasilan pengguna menemukan ulasan berdasarkan aspek tertentu. | Minimal 80% pengguna uji berhasil menyelesaikan tugas. |
| SM-02 | Keberhasilan pengguna menemukan ulasan dengan foto. | Minimal 80% pengguna uji berhasil menemukan ulasan dengan foto. |
| SM-03 | Keberhasilan pengguna mengidentifikasi kelebihan dan kekurangan produk melalui ringkasan. | Minimal 80% pengguna uji dapat menyebutkan informasi utama dengan benar. |
| SM-04 | Tingkat kemudahan penggunaan fitur. | Skor System Usability Scale (SUS) minimal 70. |

> **Catatan:** Seluruh target merupakan hipotesis awal untuk pengujian prototipe, bukan hasil pengukuran atau klaim keberhasilan fitur yang sudah diterapkan. Target dapat disesuaikan setelah pengujian terhadap pengguna dilakukan.

---

## 5. Functional Requirements

| ID | Nama Fitur | Deskripsi dan Perilaku yang Diharapkan | Prioritas |
|---|---|---|---|
| FR-01 | Filter Aspek Ulasan | Sistem menyediakan pilihan filter aspek produk, seperti kualitas, fungsi, kesesuaian dengan deskripsi, dan pengiriman. Pengguna dapat memilih aspek yang ingin dilihat. | Must Have |
| FR-02 | Pengelompokan Ulasan | Sistem menampilkan ulasan berdasarkan aspek yang dipilih agar informasi lebih terstruktur dan mudah dibaca. | Must Have |
| FR-03 | Ringkasan Kelebihan dan Kekurangan | Sistem menampilkan rangkuman informasi positif dan negatif dari ulasan yang tersedia. | Must Have |
| FR-04 | Identifikasi Keluhan Umum | Sistem menampilkan keluhan yang sering muncul berdasarkan kumpulan ulasan yang tersedia agar pengguna dapat mengetahui masalah yang berulang. | Should Have |
| FR-05 | Filter Ulasan dengan Foto | Sistem menyediakan pilihan untuk menampilkan ulasan yang memiliki foto. Ketika filter diaktifkan, hanya ulasan dengan foto yang ditampilkan. | Must Have |

### 5.1 Detail Perilaku Fitur

#### FR-01 – Filter Aspek Ulasan

- Pilihan aspek ditampilkan pada bagian ulasan produk.
- Aspek yang tersedia meliputi kualitas, fungsi, kesesuaian dengan deskripsi, dan pengiriman.
- Pengguna dapat memilih aspek untuk mempersempit ulasan yang ditampilkan.
- Pengguna dapat menghapus pilihan filter untuk kembali melihat seluruh ulasan.

#### FR-02 – Pengelompokan Ulasan

- Ulasan ditampilkan berdasarkan kategori aspek yang dipilih.
- Setiap ulasan tetap menampilkan informasi dasar, seperti rating, nama pengguna, tanggal, isi ulasan, dan foto apabila tersedia.
- Pengguna dapat berpindah kategori aspek dengan mudah.

#### FR-03 – Ringkasan Kelebihan dan Kekurangan

- Sistem menampilkan ringkasan kelebihan dan kekurangan berdasarkan isi ulasan yang tersedia.
- Informasi ditampilkan secara singkat dan mudah dipahami.
- Ringkasan tidak boleh menyampaikan informasi yang tidak didukung oleh ulasan sumber.

#### FR-04 – Identifikasi Keluhan Umum

- Sistem mengidentifikasi topik keluhan yang muncul berulang dalam ulasan.
- Setiap keluhan ditampilkan dalam bentuk ringkasan singkat.
- Informasi jumlah atau frekuensi keluhan dapat ditampilkan apabila data pendukung tersedia.

#### FR-05 – Filter Ulasan dengan Foto

- Sistem menyediakan tombol atau pilihan filter khusus untuk ulasan dengan foto.
- Ketika filter aktif, sistem hanya menampilkan ulasan yang memiliki foto.
- Ketika filter dinonaktifkan, sistem kembali menampilkan ulasan sesuai filter lainnya.

---

## 6. Non-Functional Requirements

| ID | Kategori | Kebutuhan |
|---|---|---|
| NFR-01 | Performance | Perubahan filter dan kategori ulasan harus ditampilkan dengan waktu respons yang wajar serta tidak mengganggu aktivitas pengguna. |
| NFR-02 | Usability | Fitur harus mudah dipahami oleh pengguna tanpa memerlukan panduan penggunaan yang rumit. |
| NFR-03 | Responsive Design | Tampilan fitur harus menyesuaikan ukuran layar perangkat desktop maupun perangkat mobile. |
| NFR-04 | Reliability | Informasi ulasan dan ringkasan yang ditampilkan harus sesuai dengan data ulasan yang tersedia. |
| NFR-05 | Security & Privacy | Sistem harus menjaga informasi pengguna dan tidak menampilkan data pribadi yang tidak diperlukan. |
| NFR-06 | Accessibility | Teks, tombol, filter, dan elemen interaksi harus memiliki keterbacaan dan kemudahan akses yang baik. |

---

## 7. Business Rules

| ID | Aturan Bisnis |
|---|---|
| BR-01 | Filter aspek hanya menampilkan ulasan yang relevan dengan aspek yang dipilih berdasarkan hasil kategorisasi ulasan. |
| BR-02 | Pengguna dapat memilih dan mengganti kategori aspek ulasan. |
| BR-03 | Filter ulasan dengan foto hanya menampilkan ulasan yang memiliki foto. |
| BR-04 | Jika tidak terdapat ulasan yang sesuai dengan filter, sistem menampilkan informasi bahwa ulasan tidak ditemukan. |
| BR-05 | Ringkasan kelebihan dan kekurangan harus disusun berdasarkan isi ulasan yang tersedia. |
| BR-06 | Keluhan umum hanya ditampilkan apabila terdapat data ulasan yang cukup untuk mendukung identifikasi pola keluhan. |
| BR-07 | Filter aspek dan filter foto dapat digunakan secara bersamaan. |
| BR-08 | Ulasan asli tetap dapat diakses pengguna agar pengguna dapat memeriksa konteks informasi yang digunakan dalam ringkasan. |

---

## 8. User Stories

| ID | User Story | Prioritas |
|---|---|---|
| US-01 | Sebagai pengguna Tokopedia, saya ingin memfilter ulasan berdasarkan aspek produk agar dapat menemukan informasi yang sesuai dengan kebutuhan saya dengan lebih cepat. | Must Have |
| US-02 | Sebagai pengguna Tokopedia, saya ingin melihat ulasan yang dikelompokkan berdasarkan kategori agar dapat membaca informasi produk secara lebih terstruktur. | Must Have |
| US-03 | Sebagai pengguna Tokopedia, saya ingin melihat ringkasan kelebihan produk agar dapat mengetahui hal-hal positif dari pengalaman pembeli lain. | Must Have |
| US-04 | Sebagai pengguna Tokopedia, saya ingin melihat ringkasan kekurangan produk agar dapat mengetahui hal-hal yang perlu dipertimbangkan sebelum membeli. | Must Have |
| US-05 | Sebagai pengguna Tokopedia, saya ingin mengetahui keluhan yang sering muncul agar dapat mempertimbangkan kemungkinan masalah pada produk. | Should Have |
| US-06 | Sebagai pengguna Tokopedia, saya ingin melihat ulasan yang disertai foto agar dapat membandingkan kondisi produk dengan foto dan deskripsi penjual. | Must Have |

---

## 9. Scope

### 9.1 In Scope

Fitur yang termasuk dalam pengembangan:

1. Filter ulasan berdasarkan aspek produk.
2. Pengelompokan ulasan berdasarkan aspek yang dipilih.
3. Ringkasan kelebihan produk.
4. Ringkasan kekurangan produk.
5. Identifikasi keluhan yang sering muncul.
6. Filter khusus untuk menampilkan ulasan dengan foto.
7. Tampilan kondisi kosong ketika tidak ada ulasan yang sesuai dengan filter.
8. Tampilan informasi ulasan asli sebagai sumber ringkasan.

### 9.2 Out of Scope

Fitur yang tidak termasuk dalam pengembangan:

1. Perubahan sistem rating dan penilaian produk Tokopedia.
2. Pengembangan fitur komunikasi antara pembeli dan penjual.
3. Pengelolaan atau moderasi ulasan oleh penjual.
4. Sistem rekomendasi produk baru.
5. Deteksi keaslian produk atau validasi transaksi pembeli.
6. Analisis sentimen untuk seluruh produk di Tokopedia.
7. Fitur tanya jawab berbasis AI mengenai produk.
8. Perubahan keseluruhan sistem pencarian dan katalog produk Tokopedia.

---

## 10. Assumptions & Dependencies

### 10.1 Assumptions

1. Pengguna telah membuka halaman detail produk dan mengakses bagian ulasan.
2. Data ulasan memiliki informasi dasar berupa rating, isi ulasan, tanggal, dan identitas tampilan pengguna.
3. Sebagian ulasan memiliki foto yang dapat ditampilkan.
4. Ulasan dapat dikategorikan berdasarkan aspek produk melalui proses kategorisasi tertentu.
5. Ringkasan kelebihan, kekurangan, dan keluhan dibuat berdasarkan isi ulasan yang tersedia.
6. Pengguna membutuhkan informasi yang relevan dan terstruktur, bukan sekadar jumlah ulasan yang lebih banyak.

### 10.2 Dependencies

1. **Data Ulasan Produk:** diperlukan sebagai sumber informasi untuk pengelompokan dan pembuatan ringkasan.
2. **Data Foto Ulasan:** diperlukan untuk menjalankan filter ulasan dengan foto.
3. **Mekanisme Kategorisasi:** diperlukan untuk mengelompokkan ulasan berdasarkan aspek produk.
4. **Mekanisme Analisis Teks:** diperlukan apabila ringkasan kelebihan, kekurangan, dan keluhan akan dihasilkan secara otomatis.
5. **Desain Antarmuka:** diperlukan untuk mengintegrasikan filter, pengelompokan, ringkasan, dan daftar ulasan ke dalam halaman detail produk.

> **Catatan implementasi:** PRD ini merupakan rancangan fitur. Penggunaan data dan layanan internal Tokopedia belum diasumsikan tersedia. Untuk prototipe, data ulasan dapat menggunakan data contoh atau data simulasi yang disiapkan secara terpisah.

---

## 11. Expected Deliverables

Hasil yang diharapkan dari pengembangan fitur Ulasan Relevan meliputi:

1. **Desain Halaman Ulasan Produk**  
   Menampilkan bagian ulasan dengan susunan informasi yang lebih terstruktur.

2. **Komponen Filter Aspek**  
   Menyediakan pilihan kategori kualitas, fungsi, kesesuaian dengan deskripsi, dan pengiriman.

3. **Komponen Filter Ulasan dengan Foto**  
   Menyediakan kontrol untuk menampilkan ulasan yang memiliki foto.

4. **Komponen Ringkasan Ulasan**  
   Menampilkan ringkasan kelebihan dan kekurangan produk.

5. **Komponen Keluhan Umum**  
   Menampilkan daftar keluhan yang sering ditemukan dalam ulasan.

6. **Tampilan Daftar Ulasan**  
   Menampilkan ulasan asli berdasarkan filter dan kategori yang dipilih.

7. **Tampilan Kondisi Sistem**  
   Menyediakan tampilan ketika data sedang dimuat atau tidak ditemukan.

8. **Prototipe Interaktif**  
   Menggambarkan alur penggunaan fitur Ulasan Relevan pada halaman detail produk.

---

## 12. Product Acceptance Criteria

Fitur Ulasan Relevan dinyatakan memenuhi kriteria penerimaan apabila:

| ID | Kriteria Penerimaan | Hasil yang Diharapkan |
|---|---|---|
| AC-01 | Pengguna membuka bagian ulasan produk. | Bagian ulasan dan komponen Ulasan Relevan dapat ditemukan dengan mudah. |
| AC-02 | Pengguna memilih salah satu aspek produk. | Sistem menampilkan ulasan yang sesuai dengan aspek yang dipilih. |
| AC-03 | Pengguna berpindah kategori aspek. | Daftar ulasan berubah mengikuti kategori yang dipilih. |
| AC-04 | Pengguna memilih filter ulasan dengan foto. | Sistem hanya menampilkan ulasan yang memiliki foto. |
| AC-05 | Pengguna menonaktifkan filter foto. | Sistem kembali menampilkan ulasan sesuai filter aktif lainnya. |
| AC-06 | Pengguna melihat ringkasan kelebihan dan kekurangan. | Sistem menampilkan informasi positif dan negatif berdasarkan ulasan yang tersedia. |
| AC-07 | Pengguna melihat bagian keluhan umum. | Sistem menampilkan keluhan berulang apabila didukung oleh data yang cukup. |
| AC-08 | Pengguna memilih filter yang tidak memiliki hasil. | Sistem menampilkan pesan bahwa ulasan tidak ditemukan. |
| AC-09 | Pengguna ingin memeriksa sumber informasi ringkasan. | Pengguna tetap dapat melihat ulasan asli yang menjadi sumber informasi. |
| AC-10 | Pengguna mengakses fitur melalui perangkat berbeda. | Komponen fitur tetap dapat digunakan dan ditampilkan dengan baik pada ukuran layar yang didukung. |

---

## Penutup

Fitur Ulasan Relevan dirancang untuk membantu pengguna Tokopedia mengatasi kesulitan dalam menemukan informasi penting di antara banyaknya ulasan produk. Melalui pengelompokan ulasan berdasarkan aspek, ringkasan kelebihan dan kekurangan, identifikasi keluhan umum, serta filter ulasan dengan foto, pengguna diharapkan dapat mengevaluasi produk secara lebih cepat, terarah, dan percaya diri sebelum melakukan pembelian.

---

**End of PRD v1.0**
