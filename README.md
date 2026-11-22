# Ulasan Relevan – Tokopedia

Repository ini berisi dokumentasi kebutuhan produk untuk konsep fitur **Ulasan Relevan**, yaitu fitur pendukung evaluasi ulasan produk pada platform Tokopedia.

Fitur ini dirancang untuk membantu pengguna menemukan informasi penting dari ulasan secara lebih cepat dan terstruktur sebelum mengambil keputusan pembelian.

> **Status proyek:** PRD v1.0 telah disusun dan prototipe interaktif lima layar telah dikembangkan pada workspace lokal. Source code prototipe belum dipublikasikan ke repository ini.
>
> **Catatan:** Proyek ini merupakan rancangan dan prototipe akademik, bukan fitur resmi Tokopedia dan bukan integrasi dengan sistem internal Tokopedia.

## Latar Belakang

Banyaknya ulasan pada halaman produk dapat menyulitkan pengguna dalam menemukan informasi yang sesuai dengan kebutuhan mereka. Informasi mengenai kualitas, fungsi, kesesuaian produk dengan deskripsi, serta kekurangan produk dapat tersebar di berbagai ulasan.

Ulasan Relevan dirancang untuk menyajikan informasi tersebut secara lebih terarah melalui pengelompokan aspek, ringkasan ulasan, identifikasi keluhan umum, dan filter ulasan yang disertai foto.

## Tujuan Proyek

- Mempermudah pengguna menemukan ulasan berdasarkan aspek produk.
- Membantu pengguna memahami kelebihan dan kekurangan produk.
- Membantu pengguna mengenali keluhan yang sering muncul.
- Mempermudah pengguna menemukan ulasan yang memiliki foto.
- Mendukung proses evaluasi produk sebelum pembelian.

## Fitur Utama

1. Filter ulasan berdasarkan aspek:
   - Kualitas.
   - Fungsi.
   - Kesesuaian dengan deskripsi.
   - Pengiriman.
2. Pengelompokan ulasan berdasarkan aspek yang dipilih.
3. Ringkasan kelebihan dan kekurangan produk.
4. Identifikasi keluhan umum.
5. Filter ulasan dengan foto.
6. Tampilan kondisi kosong ketika tidak ada ulasan yang sesuai.
7. Tampilan detail ulasan asli sebagai sumber informasi.

## Struktur Prototipe

Prototipe interaktif dirancang dalam lima layar yang saling terhubung:

| No. | Layar | Fungsi |
|---|---|---|
| 1 | Search Results | Menampilkan hasil pencarian dan produk yang akan dievaluasi. |
| 2 | Product Detail | Menampilkan informasi produk dan akses menuju bagian ulasan. |
| 3 | Review Summary | Menampilkan ringkasan kelebihan, kekurangan, dan keluhan umum. |
| 4 | Review List & Filters | Menampilkan daftar ulasan dengan filter aspek dan foto. |
| 5 | Review Detail | Menampilkan isi lengkap ulasan dan foto apabila tersedia. |

Kelima layar dirancang memiliki dua mode tampilan:
- **Wireframe Low-Fidelity:** rancangan struktur dan susunan komponen antarmuka.
- **Prototype High-Fidelity:** tampilan visual dengan gaya antarmuka yang lebih mendekati produk akhir.

Alur utama prototipe: Search Results → Product Detail → Review Summary → Review List & Filters → Review Detail.

## Teknologi Prototipe

Berdasarkan implementasi pada workspace pengembangan, prototipe menggunakan:
- HTML5.
- CSS3.
- JavaScript Vanilla.
- Node.js Test Runner untuk pengujian otomatis.

## Dokumentasi

| Dokumen | Deskripsi |
|---|---|
| [PRD.md](PRD.md) | Product Requirements Document versi 1.0 yang memuat kebutuhan produk, user stories, aturan bisnis, ruang lingkup, dan kriteria penerimaan. |
| [CHANGELOG.md](CHANGELOG.md) | Riwayat perubahan dan perkembangan proyek berdasarkan versi. |

## Pengujian

Berdasarkan laporan implementasi, terdapat 17 skenario pengujian otomatis yang dinyatakan berhasil. Pengujian mencakup navigasi antarlayar, filter aspek, filter foto, kombinasi filter, tampilan detail ulasan, persistensi filter, dan konsistensi ringkasan.

Pengujian fungsional otomatis tersebut tidak sama dengan pengujian usability terhadap pengguna nyata. Target keberhasilan dan skor SUS pada PRD tetap merupakan target awal yang belum dapat dianggap sebagai hasil pengukuran.

## Batasan Prototipe

- Data ulasan yang digunakan merupakan data simulasi.
- Prototipe tidak terhubung dengan backend, database, maupun API Tokopedia.
- Prototipe tidak menjalankan analisis AI/NLP otomatis terhadap ulasan nyata.
- Prototipe tidak memproses transaksi atau aktivitas pembelian.
- Source code prototipe belum tersedia pada repository ini; dokumentasi cara menjalankan dari hasil clone akan ditambahkan setelah source code dipublikasikan.
- Screenshot wireframe dan prototype untuk bukti dokumentasi masih perlu dilengkapi.

## Rencana Pengembangan

- [x] Menyusun PRD fitur Ulasan Relevan versi 1.0.
- [x] Mendokumentasikan riwayat perubahan proyek.
- [x] Mengembangkan prototipe interaktif lima layar pada workspace lokal.
- [x] Menyediakan mode wireframe low-fidelity dan prototype high-fidelity.
- [x] Menjalankan pengujian fungsional otomatis berdasarkan laporan implementasi.
- [ ] Mengunggah source code prototipe ke repository GitHub.
- [ ] Menambahkan screenshot lima layar pada kedua mode tampilan.
- [ ] Melengkapi dokumentasi Worksheet 12 dengan bukti visual.
- [ ] Melakukan pengujian usability apabila diperlukan pada tahap evaluasi.

## Riwayat Versi

Lihat [CHANGELOG.md](CHANGELOG.md) untuk catatan perubahan yang lebih lengkap.

---

Dokumen dan prototipe dalam repository ini disusun untuk keperluan pembelajaran dan pengembangan proyek akademik.
