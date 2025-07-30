# EPL Prediction Using LSTM

Prediksi klasemen akhir **English Premier League (EPL)** menggunakan model **Long Short-Term Memory (LSTM)** berdasarkan data historis pertandingan.  
Proyek ini dibuat sebagai bagian dari tugas akhir sarjana Informatika.

---

##  Struktur Proyek
```yaml
EPL_Prediction_Using_LSTM/
├── data/
│ ├── raw/ # Dataset mentah asli
│ └── processed/ # Dataset hasil preprocessing
├── models/ # Model terlatih
├── lstm_tuning/ # Hasil parameter tuning
├── README.md # Deskripsi proyek ini

```
---

## Dataset
- **Sumber:** [football-data.co.uk](https://www.football-data.co.uk) dan [fbref.com](https://fbref.com/en/comps/9/Premier-League-Stats)
- **Fitur yang digunakan:**
  - Statistik Home/Away team
  - Kemenangan, hasil imbang, kekalahan
  - Skor pertandingan, selisih gol
  - Form performa
  - Ekspektasi gol

---

## Model
-  **Framework:** TensorFlow / Keras  
-  **Arsitektur:** LSTM (Recurrent Neural Network)  
-  **Target:** Prediksi klasemen akhir EPL

---

## Evaluasi Model
- Akurasi klasemen akhir
- Visualisasi posisi peringkat vs prediksi
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Spearman's Corr
- Kendal Tau

---

## Cara Menjalankan Proyek
```bash
# 1. Clone repository ini
git clone https://github.com/username/EPL_Prediction_Using_LSTM.git

# 2. Jalankan notebook
jupyter notebook sequence.ipynb
