# Tugas-Akhir

# 📘 Skripsi - Identifikasi Ayat-Ayat Al-Qur'an yang Sulit Menggunakan Random Forest

Repositori ini berisi file data dan kode program yang digunakan dalam penelitian skripsi dengan judul **"Identifikasi Ayat-Ayat Al-Qur’an yang Sulit Menggunakan Random Forest"**.

## 📂 Isi Folder

### 1. Dataset
- `responden.xlsx`  
  Berisi 300 ayat yang telah dilabeli berdasarkan penilaian responden (label: mudah atau sulit).
- `new-label.xlsx`  
  Berisi tambahan 325 ayat dengan format dan label yang sama.
- `quran-simple-plain.xlsx`  
  Berisi teks lengkap seluruh ayat Al-Qur’an (sekitar 6.236 ayat), digunakan sebagai sumber teks.

### 2. Kode Program
- `rf-without sampling-version.ipynb`  
  Notebook utama berisi implementasi preprocessing, TF-IDF, klasifikasi dengan Random Forest, dan evaluasi model.
- `rf-sampling-version.ipynb`  
  Versi kode yang dilengkapi dengan teknik penyeimbangan data (Random Undersampling + SMOTE).


## 📌 Tujuan
Penelitian ini bertujuan mengembangkan sistem klasifikasi otomatis untuk mengenali ayat-ayat Al-Qur’an yang tergolong sulit, sebagai kontribusi terhadap pengembangan alat bantu pembelajaran Al-Qur’an berbasis teknologi.

## 📝 Catatan
- Data dan kode ini hanya digunakan untuk kepentingan akademik dan non-komersial.
- Harap tidak menyalahgunakan isi file tanpa mencantumkan sumber.

