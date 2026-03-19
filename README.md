# Analisis Efektivitas Platform Pencarian Kerja Berdasarkan Jurusan

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis platform pencarian kerja mana yang memberikan peluang keberhasilan tertinggi (mendapatkan tawaran pekerjaan) bagi mahasiswa berdasarkan kategori jurusan mereka. Analisis ini menggunakan pendekatan **Analisis Deskriptif** untuk membedakan kinerja antara LinkedIn, Indeed, dan Handshake.

## Pertanyaan Utama
- Apakah platform tertentu lebih efektif untuk jurusan tertentu (misalnya STEM vs Business)?
- Berapa rata-rata tingkat keberhasilan (*Offer Rate*) pada setiap platform?

## Dataset
Dataset yang digunakan adalah `job_search_platform_efficacy_100k.csv` yang berisi 100.000 data sampel mahasiswa dengan kolom utama:
- `Major_Category`: Kategori jurusan mahasiswa.
- `Primary_Search_Platform`: Platform utama yang digunakan (LinkedIn, Indeed, Handshake).
- `Offer_Received`: Indikator apakah mahasiswa menerima tawaran kerja (1 = Ya, 0 = Tidak).
- `Applications_Submitted`: Jumlah lamaran yang dikirim.

## Metodologi
1. **Pembersihan Data**: Mengecek nilai yang hilang (missing values).
2. **Agregasi**: Mengelompokkan data berdasarkan jurusan dan platform.
3. **Kalkulasi**: Menghitung persentase keberhasilan per kelompok.
4. **Visualisasi**: Membuat diagram batang (Bar Chart) untuk membandingkan performa platform secara visual.
