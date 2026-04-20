# Komputasi Sains Data — SD234402

> **Institut Teknologi Sepuluh Nopember**  
> Fakultas Sains dan Analitika Data | Departemen Statistika  
> Program Sarjana Sains Data | Semester 4 | 2024/2025

Repository ini berisi kumpulan materi, rangkuman, dan implementasi kode dari mata kuliah **Komputasi Sains Data (SD234402)**. Setiap topik disajikan dalam format R Markdown (`.Rmd`) yang dapat dijalankan secara interaktif.

---

## 👥 Anggota Kelompok

| No | Nama | NRP |
|----|------|-----|
| 1 | Naomy Athaya Jovany | 5052241002 |
| 2 | Ghisele Valerin | 5052241005 |
| 3 | Kirana Indy | 5052241014 |
| 4 | Elena Miska Faradisa | 5052241022 |
| 5 | George Eldzen Edison | 5052241024 |
| 6 | Shafa Agnia Ramadhan | 5052241029 |
| 7 | Bassa Bhaskara Desno Gabrihi | 5052241030 |
| 8 | Juan Glori | 5052241031 |
| 9 | Alycia Zada | 5052241034 |
| 10 | Najwa Aulia | 5052241035 |
| 11 | Agata Corinna Aulia Widyawati | 5052241036 |
| 12 | Inessa Regina Angelica Munda | 5052241037 |
| 13 | Annisa Maulida Zahro | 5052241038 |

---

## 📁 Struktur Repository

```
Komputasi-Sains-Data-Project/
│
├── 1_Intro_Statdes/           # Pengenalan Sains Data & Statistik Deskriptif
├── 2_Data_Preprocessing/      # Manipulasi & Pembersihan Data
├── 3_Penjelasan_Github/       # Panduan Penggunaan GitHub
├── 4_Regresi_Linear/          # Regresi Linear
├── 5_Pemodelan_Time_Series/   # Pemodelan Time Series
├── 6_Regresi_Logistik_Biner/  # Regresi Logistik Biner: Newton-Raphson
└── README.md
```

---

## 📚 Daftar Materi

### 1. Intro & Statistik Deskriptif `1_Intro_Statdes/`
Pengenalan konsep dasar sains data dan eksplorasi awal data menggunakan R dan Python. Mencakup jenis-jenis data terstruktur dan tidak terstruktur, serta statistik deskriptif sebagai langkah pertama analisis.

### 2. Data Preprocessing `2_Data_Preprocessing/`
Teknik manipulasi dan pembersihan data menggunakan library **Pandas** (Python) serta **dplyr** dan **tidyr** (R). Topik yang dibahas meliputi penanganan *missing values*, normalisasi data, dan transformasi data.

### 3. Penjelasan GitHub `3_Penjelasan_Github/`
Panduan kolaborasi menggunakan GitHub — mulai dari konsep dasar *version control*, cara membuat branch, commit, push, hingga pull request dalam proyek tim.

### 4. Regresi Linear `4_Regresi_Linear/`
Implementasi regresi linear sederhana dan berganda menggunakan R dan Python. Mencakup estimasi parameter, uji asumsi, interpretasi koefisien, serta evaluasi model.

### 5. Pemodelan Time Series `5_Pemodelan_Time_Series/`
Analisis dan pemodelan data deret waktu. Mencakup identifikasi pola (tren, musiman), serta penerapan model seperti ARIMA menggunakan R.

### 6. Regresi Logistik Biner `6_Regresi_Logistik_Biner/`
Rangkuman dan implementasi **Regresi Logistik Biner** dengan metode estimasi **Newton-Raphson** dan **IRLS**, dilengkapi studi kasus menggunakan dataset *Cleveland Heart Disease*. Implementasi dilakukan secara manual di R dan dibandingkan dengan fungsi `glm()` bawaan R.

---

## 🛠️ Tools & Teknologi

| Bahasa | Library Utama |
|--------|--------------|
| R | `glm`, `dplyr`, `tidyr`, `ggplot2`, `caret` |
| Python | `pandas`, `numpy`, `scikit-learn`, `matplotlib` |
| Format | R Markdown (`.Rmd`) → HTML / PDF |
| Platform | RStudio, Jupyter Notebook, GitHub |

---

## ▶️ Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/Ju4n-web/Komputasi-Sains-Data-Project.git
   ```

2. Buka folder materi yang diinginkan di **RStudio**

3. Buka file `.Rmd` dan klik **Knit** untuk menghasilkan output HTML atau PDF

4. Pastikan semua dataset yang dibutuhkan tersedia di direktori yang sama dengan file `.Rmd`

---

## 📋 Mata Kuliah

| | |
|---|---|
| **Nama** | Komputasi Sains Data |
| **Kode** | SD234402 |
| **Bobot** | 3 SKS (T=2, P=1) |
| **Semester** | 4 |
| **Prasyarat** | Pemrograman Open Source |

**Dosen Pengampu:**
- Veniola Forestryani, S.Si., M.Si.
- Erma Oktania Permatasari, S.Si., M.Si.
- Widhianingsih Tintrim Dwi Ary, S.Si., M.Stat., Ph.D.

---

*Institut Teknologi Sepuluh Nopember · Fakultas Sains dan Analitika Data · 2024/2025*
