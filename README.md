# Belajar-project-30-hari-rutin
# Hari-03: Membaca File CSV dengan Pandas

## 🎯 Tujuan
- Belajar membaca dataset `.csv` menggunakan `pandas`.
- Mengeksplorasi data dengan fungsi dasar:
  - `head()` → menampilkan 5 baris pertama.
  - `shape` → melihat jumlah baris & kolom.
  - `columns` → daftar nama kolom.

## 🐍 Kode Utama
```python
import pandas as pd

# baca dataset
df = pd.read_csv("data/Sample.csv")

# tampilkan 5 baris pertama
print(df.head())

# jumlah baris & kolom
print("Ukuran dataset:", df.shape)

# statistik deskriptif
print(df.describe())
