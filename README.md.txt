# Data Mining – Preprocessing

Repositori ini dibuat untuk memenuhi tugas praktikum Data Mining (Preprocessing).

## 📂 Isi Repo
- `preprocessing_movie.py` → Script Python untuk preprocessing dataset film.
- `movie_sample_dataset.csv` → Dataset asli (raw data).
- `movie_dataset_cleaned.csv` → Dataset hasil preprocessing.

## 🔧 Langkah Preprocessing
1. Load dataset dengan Pandas.
2. Hapus missing values pada kolom penting (`gross`, `budget`).
3. Normalisasi teks (`color`, `country`, `genres`, dll.).
4. Konversi tipe data (`budget`, `gross` → numerik).
5. Hapus nilai negatif pada `budget` dan `gross`.
6. Pisahkan `genres` yang dipisahkan oleh tanda `|`.
7. Simpan dataset bersih ke file `movie_dataset_cleaned.csv`.

## 🚀 Cara Menjalankan
```bash
python preprocessing_movie.py