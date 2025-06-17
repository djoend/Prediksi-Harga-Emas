# Prediksi Harga Emas Menggunakan RNN dan LSTM

Proyek ini mengimplementasikan prediksi harga emas menggunakan model Recurrent Neural Network (RNN) dan Long Short-Term Memory (LSTM). Proyek ini menganalisis data historis harga emas dan membuat model prediktif untuk meramalkan harga emas di masa depan.

## Anggota Tim (Kelompok 12 2023A)
* Layyinatul Qolbiyah (23031554025)
* Nailah Masruroh (23031554100)
* Yulia Eka Restania (23031554199)
* Novia Djoend Lestari (23031554220)

## Gambaran Proyek
Proyek ini berfokus pada analisis dan prediksi harga emas menggunakan pendekatan deep learning. Kami mengimplementasikan model RNN dan LSTM secara manual untuk membandingkan kinerja keduanya dalam memprediksi harga emas.

### Fitur yang Digunakan
- Harga Pembukaan
- Harga Tertinggi
- Harga Terendah
- Harga Penutupan
- Volume Perdagangan
- Persentase Perubahan Harga
- Volatilitas Harga

## Analisis Data
Proyek ini mencakup Analisis Data Eksplorasi (EDA) yang komprehensif:
- Analisis tren harga
- Analisis volume
- Analisis volatilitas
- Dekomposisi musiman
- Indikator teknis (Moving Average, RSI)
- Analisis korelasi
- Distribusi return harian
- Distribusi harga berdasarkan hari/bulan

## Model yang Diimplementasikan
1. **RNN Manual (Recurrent Neural Network)**
   - Implementasi kustom layer RNN
   - Arsitektur: RNN(64) -> Dropout(0.1) -> Dense(1)

2. **LSTM Manual (Long Short-Term Memory)**
   - Implementasi kustom layer LSTM
   - Arsitektur: LSTM(64) -> Dropout(0.1) -> Dense(1)

## Metrik Performa Model
Kedua model dievaluasi menggunakan:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)
- R-squared (R²)

## Fitur Utama
- Preprocessing dan pembersihan data
- Rekayasa fitur
- Analisis deret waktu
- Implementasi model kustom
- Perbandingan model
- Kemampuan prediksi harga masa depan

## Detail Teknis
- Bahasa Pemrograman: Python
- Pustaka Utama:
  - TensorFlow
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Penggunaan
Proyek ini memiliki fungsionalitas untuk:
1. Memuat dan memproses data historis harga emas
2. Melatih model RNN dan LSTM
3. Membandingkan kinerja model
4. Membuat prediksi harga masa depan

## Penyimpanan Model
Model dan scaler yang telah dilatih disimpan untuk penggunaan di masa depan:
- Model LSTM: `manual_model_lstm.keras`
- X-scaler: `scaler_x.pkl`
- Y-scaler: `scaler_y.pkl`
