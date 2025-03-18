# Neural Network Regression with TensorFlow: Weather Temperature Prediction

## Deskripsi Proyek
Repositori ini berisi implementasi model regresi neural network menggunakan TensorFlow untuk memprediksi suhu cuaca berdasarkan data historis cuaca dari kota Szeged, Hungaria. Dataset yang digunakan mencakup berbagai variabel seperti suhu, kelembaban, kecepatan angin, dan curah hujan. Proyek ini mencakup pra-pemrosesan data, pembuatan model, pelatihan, dan evaluasi model menggunakan metrik seperti Mean Absolute Error (MAE) dan Root Mean Squared Error (RMSE). Hasil dari model ini diharapkan dapat memberikan prediksi suhu yang akurat dan dapat diaplikasikan dalam berbagai konteks, seperti perencanaan pertanian dan sistem peringatan dini cuaca.

## Dataset
Dataset yang digunakan dalam proyek ini berasal dari Kaggle dan dapat diakses melalui [link berikut](https://www.kaggle.com/datasets/budincsevity/szeged-weather/data). Dataset ini mencakup data cuaca per jam dari tahun 2006 hingga 2016.

## Struktur Repositori

<pre>
/project
│
├── <b>/data</b>
│   └── szeged-weather.csv
│
├── <b>/notebooks</b>
│   └── Neural_network_regression_with_TensorFlow_Predict_Weather_Temperature.ipynb
│
├── <b>/models</b>
│   └── model.h5
│
├── README.md
└── requirements.txt
</pre>


## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/Neural-Network-Regression-Weather-Prediction.git
   cd Neural-Network-Regression-Weather-Prediction
   
2. Buat dan aktifkan lingkungan virtual:
   ```bash
    python -m venv venv
    source venv/bin/activate  # Pada Windows: venv\Scripts\activate
3. Install dependensi:
    ```bash
    pip install -r requirements.txt
4. Buka notebook Jupyter:
    ```bash
    jupyter notebook
5. Buka file Neural_network_regression_with_TensorFlow_Predict_Weather_Temperature.ipynb untuk menjalankan kode.

## Penggunaan
1. **Pra-pemrosesan Data**: Melakukan pra-pemrosesan data seperti normalisasi dan pembagian data menjadi set pelatihan dan pengujian.
2. **Pembuatan Model**: Membangun arsitektur neural network menggunakan TensorFlow.
3. **Pelatihan Model**: Melatih model menggunakan data pelatihan.
4. **Evaluasi Model**: Mengevaluasi performa model menggunakan metrik MAE dan RMSE pada data pengujian.
5. **Prediksi**: Menggunakan model yang telah dilatih untuk memprediksi suhu cuaca.

## Hasil
Model yang dikembangkan diharapkan dapat memberikan prediksi suhu yang akurat berdasarkan data historis cuaca. Hasil evaluasi model akan ditampilkan dalam bentuk metrik MAE dan RMSE.

## Kontribusi
Kontribusi sangat diterima! Jika Anda ingin berkontribusi pada proyek ini, silakan buka issue atau pull request.

## Lisensi
Proyek ini dilisensikan di bawah lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

## Kontak
Jika Anda memiliki pertanyaan atau masukan, silakan hubungi [nama Anda] di [email Anda].
