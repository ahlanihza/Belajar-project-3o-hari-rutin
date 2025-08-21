# Hari-03: Membaca File CSV dengan Pandas

## 🎯 Tujuan
- Belajar membaca dataset `.csv` menggunakan `pandas`.
- Mengeksplorasi data dengan fungsi dasar: `head()`, `shape`, `columns`, `describe()`.

## 📂 Dataset
Dataset: `sample.csv`  
Jumlah baris: X  
Jumlah kolom: Y  
Kolom: [daftar kolom yang muncul di file]

## 🐍 Kode Utama
```python
import pandas as pd

df = pd.read_csv("sample.csv")
print(df.head())
print("Ukuran dataset:", df.shape)
print("Kolom:", df.columns.tolist())
print(df.describe())
