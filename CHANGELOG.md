# Changelog

Seluruh perubahan penting pada proyek **Ulasan Relevan – Tokopedia** dicatat dalam dokumen ini.

Format catatan mengikuti urutan versi dan tanggal pengerjaan. Tanggal dicantumkan ketika perubahan benar-benar dilakukan.

## [1.1.0] - 2026-11-23

### Added
- Mengembangkan prototipe interaktif menjadi lima layar: Search Results, Product Detail, Review Summary, Review List & Filters, serta Review Detail.
- Menambahkan mode wireframe low-fidelity dan prototype high-fidelity pada kelima layar.
- Menambahkan navigasi antarlayar dan alur evaluasi produk dari pencarian hingga detail ulasan.
- Menambahkan filter aspek ulasan: kualitas, fungsi, kesesuaian dengan deskripsi, dan pengiriman.
- Menambahkan filter ulasan dengan foto, ringkasan kelebihan dan kekurangan, keluhan umum, serta tampilan detail ulasan.
- Menambahkan dokumentasi Worksheet 12 pada workspace proyek.

### Improved
- Menyempurnakan alur navigasi dan konsistensi tampilan antarlayar.
- Mempertahankan pilihan filter ketika pengguna berpindah dari daftar ulasan ke detail ulasan dan kembali.
- Menyediakan tampilan kondisi kosong ketika kombinasi filter tidak menghasilkan ulasan.

### Testing
- Berdasarkan laporan implementasi, 17 skenario pengujian otomatis dinyatakan berhasil, mencakup navigasi, filter aspek, filter foto, kombinasi filter, tampilan detail ulasan, persistensi filter, dan konsistensi ringkasan.
- Pengujian tersebut merupakan pengujian fungsional otomatis, bukan pengujian usability terhadap pengguna nyata.

### Notes
- Prototipe menggunakan data ulasan simulasi dan bukan integrasi dengan sistem Tokopedia.
- Screenshot wireframe dan prototype masih perlu diambil secara manual untuk melengkapi bukti dokumentasi Worksheet 12.
- Source code prototipe masih berada di workspace pengembangan dan belum dipublikasikan pada repository GitHub ini.

## [1.0] - 2026-11-23

### Added
- Menambahkan dokumen Product Requirements Document (PRD) versi 1.0.
- Mendokumentasikan latar belakang, visi produk, target pengguna, dan permasalahan pengguna.
- Mendefinisikan product goals, success metrics, functional requirements, dan non-functional requirements.
- Mendokumentasikan business rules dan user stories.
- Menetapkan ruang lingkup pengembangan, assumptions, dan dependencies.
- Mendefinisikan expected deliverables dan product acceptance criteria.

### Notes
- PRD berstatus **Draft**.
- Target success metrics merupakan hipotesis awal untuk pengujian prototipe, bukan hasil pengukuran.
- Prototipe direncanakan menggunakan data contoh atau data simulasi; integrasi dengan data dan layanan internal Tokopedia belum diasumsikan tersedia.

## [Unreleased]

### Planned
- Mengunggah source code prototipe ke repository GitHub.
- Menambahkan bukti screenshot lima layar dalam mode wireframe dan prototype.
- Melengkapi dokumentasi Worksheet 12 dengan hasil pemeriksaan manual.
- Melakukan pengujian usability terhadap pengguna apabila diperlukan dalam tahapan evaluasi.
