# 📈 Stock Price Prediction using ARIMA Model

Notebook ini merupakan bagian dari Ujian Tengah Semester (UTS) yang bertujuan untuk melakukan **prediksi harga saham** menggunakan model statistik **ARIMA (AutoRegressive Integrated Moving Average)**.

---

## 🧠 Tujuan
Membangun model prediksi harga saham berdasarkan data historis menggunakan model **time series ARIMA**, dengan langkah-langkah:
1. Eksplorasi data harga saham.
2. Prapemrosesan dan visualisasi.
3. Penentuan parameter ARIMA yang optimal.
4. Pelatihan model.
5. Evaluasi hasil prediksi.

---

## 📂 File

- `215314148_UTS_Stock Price Prediction using ARIMA Model (2).ipynb`  
  Notebook utama berisi seluruh proses dari pengambilan data, eksplorasi, training, hingga evaluasi model ARIMA.

---

## 🛠️ Teknologi yang Digunakan

- **Python 3**
- **Jupyter Notebook**
- **Pustaka**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `statsmodels`
  - `seaborn`

---

## 🔁 Langkah-Langkah Analisis

1. **Import dan Persiapan Data**
   - Data harga saham dibaca ke dalam DataFrame.
   - Mengecek missing values, outliers, dan format tanggal.

2. **Visualisasi Data**
   - Grafik harga saham dari waktu ke waktu.
   - Pendeteksian tren dan musiman secara visual.

3. **Stasioneritas**
   - Uji **Dickey-Fuller** untuk mengecek apakah data stasioner.
   - Differencing dilakukan jika data tidak stasioner.

4. **Plot ACF dan PACF**
   - Untuk menentukan parameter p (AR) dan q (MA).

5. **Pemodelan ARIMA**
   - Pelatihan model ARIMA dengan parameter terbaik.
   - Plot hasil prediksi vs aktual.


---

## 📈 Contoh Output
- Plot harga saham aktual vs prediksi.
- Residual plot untuk validasi model.

---

## 📌 Catatan
- Data saham dapat berupa dataset publik atau hasil scraping dari sumber seperti Yahoo Finance.
- Model ARIMA bersifat statistik, cocok untuk prediksi jangka pendek hingga menengah, namun tidak mempertimbangkan faktor eksternal seperti berita atau sentimen.

---

## 🧑‍🎓 Informasi Akademik

- 📄 Nama File: `215314148_UTS_Stock Price Prediction using ARIMA Model (2).ipynb`
- 🎓 Proyek: UTS Pemodelan Data / Data Science
- 🧾 NIM: 215314148

---


