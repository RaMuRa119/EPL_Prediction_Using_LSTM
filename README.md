# EPL Prediction Using LSTM

Prediksi klasemen akhir **English Premier League (EPL)** menggunakan model **Long Short-Term Memory (LSTM)** berdasarkan data historis pertandingan.  
Proyek ini dibuat sebagai bagian dari tugas akhir sarjana Informatika.

---

##  Struktur Proyek

EPL_Prediction_Using_LSTM/
├── data/ # Dataset mentah dan hasil preprocessing
├── notebooks/ # Jupyter notebook untuk eksplorasi & modeling
├── models/ # Model terlatih dan arsitektur
├── outputs/ # Grafik hasil prediksi dan evaluasi
├── README.md # Deskripsi proyek ini

## 📊 Dataset
- **Sumber:** [football-data.co.uk](https://www.football-data.co.uk)
- **Fitur yang digunakan:**
  - Statistik Home/Away team
  - Kemenangan, hasil imbang, kekalahan
  - Skor pertandingan, selisih gol
  - Form performa terakhir

---

## 🧠 Model
- 📦 **Framework:** TensorFlow / Keras  
- 🔁 **Arsitektur:** LSTM (Recurrent Neural Network)  
- 🎯 **Target:** Prediksi klasemen akhir EPL

---

## 🔎 Evaluasi Model
- Akurasi klasemen akhir
- Visualisasi posisi peringkat vs prediksi
- Mean Squared Error (MSE)

---

## 🚀 Cara Menjalankan Proyek
```bash
# 1. Clone repository ini
git clone https://github.com/username/EPL_Prediction_Using_LSTM.git

# 2. Jalankan notebook
jupyter notebook sequence.ipynb
