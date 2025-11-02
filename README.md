# Dataset-Narkotika_424_431
Kumpulan 51 putusan pengadilan klasifikasi Narkotika dan Psikotropika dari Pengadilan Negeri Makassar untuk Tugas 2 Mata Kuliah Temu Kembali Informasi.


# 🧾 Dataset Putusan Pengadilan: Narkotika dan Psikotropika

## 📘 Deskripsi Umum
Repositori ini berisi **dataset 51 dokumen putusan pengadilan** yang dikumpulkan secara manual dari situs resmi [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/direktori.html).  
Dataset ini disusun untuk memenuhi tugas mata kuliah **Temu Kembali Informasi (SUBCPMK-2)** dengan topik *Pemahaman Metadata, Format Dokumen, dan Markup Language dalam Temu Kembali Informasi*.

Semua dokumen bersifat **terbuka** dan **tidak terikat hak atas kekayaan intelektual (HaKI)** sesuai ketentuan publikasi Mahkamah Agung Republik Indonesia.

---

## 🏛️ Informasi Dataset

| **Atribut** | **Deskripsi** |
|--------------|---------------|
| **Jumlah Dokumen** | 51 dokumen putusan pengadilan |
| **Format Dokumen** | PDF (`.pdf`) |
| **Klasifikasi** | Pidana Khusus – Narkotika dan Psikotropika |
| **Tahun Putusan** | 2023–2025 |
| **Pengadilan Negeri** | PN Makassar|
| **Status Putusan** | Tidak berkekuatan hukum tetap |
| **Sumber Data** | [https://putusan3.mahkamahagung.go.id/direktori.html](https://putusan3.mahkamahagung.go.id/direktori.html) |
| **Lisensi** | Publik (tanpa hak cipta) |
| **Metadata** | Tersedia dalam file `Overview.xlsx` |

---

## 📂 Struktur Repositori
Dataset-Narkotika_424_431/
│
├── Dataset/
│ └── Narkotika.zip → berisi 51 file putusan (format .pdf)
│
├── Overview/
│ └── Overview.xlsx → ringkasan metadata 51 dokumen
│
└── README.md → dokumentasi dataset

# 🧾 Dataset Putusan Narkotika – PN Makassar

## 📑 Struktur File `Overview.xlsx`
File `Overview.xlsx` memuat ringkasan metadata dari 50 dokumen putusan dengan kolom sebagai berikut:

| No | Nama File | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
|----|-------------|------------------|---------------|---------------|---------------|
| 1 | putusan_1017_pid.sus_2023_pn_mks_20250615205038.pdf | 1017/Pid.Sus/2023/PN Mks | PN Makassar | 10 paket narkotika jenis shabu ukuran kecil dalam kemasan sachet plastik bening; 2 sachet plastik kosong; 1 buah timbangan digital; 1 buah alat hisab shabu; 1 buah kotak warna putih; 1 unit HP Oppo warna hitam | Menjatuhkan pidana penjara 5 tahun 6 bulan dan denda Rp800.000.000 subsidair 8 bulan penjara |
| 2 | ... | ... | ... | ... | ... |

---

## 🎯 Tujuan Pembuatan Dataset
1. Sebagai **sumber data hukum** untuk pembelajaran dan penelitian di bidang *Temu Kembali Informasi (Information Retrieval)*.  
2. Untuk **analisis teks hukum**, seperti:
   - Ekstraksi metadata hukum  
   - Klasifikasi isi putusan  
   - Analisis pola amar putusan  
3. Untuk **melatih keterampilan mahasiswa** dalam pengelolaan data dokumen digital dan pemahaman struktur metadata.

---

## ⚙️ Cara Penggunaan Dataset
1. Download file `Narkotika.zip` dari folder `/Dataset/`.
2. Ekstrak file ZIP untuk mendapatkan 50 dokumen `.pdf`.
3. Gunakan file `Overview.xlsx` untuk melihat ringkasan metadata seperti nomor putusan, barang bukti, dan amar putusan.
4. Dataset dapat digunakan untuk eksperimen *information retrieval*, *text mining*, atau *document classification* menggunakan Python dan library seperti `pandas`, `nltk`, dan `PyPDF2`.

---

## 👥 Anggota Kelompok
| Nama | NIM | 
|------|-----|
|Ismi Dwi Junianti | 202210370311431 |
|Ulva Nuha Muvidah | 202210370311424 | 

---

## 📅 Informasi Tugas
- **Mata Kuliah:** Temu Kembali Informasi (SUBCPMK-2)  
- **Dosen Pengampu:** Ir. Galih Wasis Wicaksono, S.Kom., M.Cs.  
- **Tahun Ajaran:** 2025  
- **Jenis Tugas:** Akuisisi dan Pengelolaan Dokumen Putusan Pengadilan  

---

## 📝 Catatan Penting
- Seluruh dokumen diambil dari sumber resmi **Mahkamah Agung Republik Indonesia**.  
- Tidak ada perubahan isi pada dokumen putusan.  
- Dataset ini disusun untuk **tujuan akademik**, bukan komersial.  

---
