# Last-Project-GDSC


Proyek machine learning ini bertujuan untuk memprediksi harga emas di masa depan dengan menggunakan algoritma Regressor Random Forest, berdasarkan data historis harga emas dan atribut-atribut ekonomi terkait. Langkah-langkah proyek meliputi preprocessing data, eksplorasi data, pelatihan model, evaluasi model, dan prediksi harga emas. Tujuan akhirnya adalah memberikan manfaat bagi para pelaku perdagangan emas dan investor dengan menyediakan perkiraan harga emas yang lebih akurat, meskipun harus diingat bahwa prediksi aset keuangan tetap memiliki ketidakpastian.
Work flow:
Data Gathering: Kumpulkan data harga emas selama 10 tahun. Data ini harus mencakup harga emas untuk beberapa hari. Sumber data: https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data
Data Preprocessing: Lakukan preprocessing pada data. Ini mungkin termasuk menghapus data yang hilang, menormalkan atau mengubah skala data, dan mengatasi outlier jika diperlukan. Pastikan data siap digunakan oleh algoritma machine learning.
Data Analysis: Lakukan analisis data untuk memahami hubungan antara fitur (atribut) dalam data, menentukan fitur-fitur yang paling berpengaruh terhadap harga emas, dan visualisasi data untuk mendapatkan wawasan tambahan.
Train-Test Split: Bagi data menjadi dua bagian: data pelatihan (training data) dan data pengujian (test data). Data pelatihan akan digunakan untuk melatih model, sedangkan data pengujian akan digunakan untuk menguji kinerja model.
Machine Learning Model Selection: Pilih model machine learning yang sesuai untuk tugas ini. Dalam kasus ini, Anda telah memilih untuk menggunakan model Regressor Random Forest.
Model Training: Latih model Random Forest Regressor dengan menggunakan data pelatihan. Model ini akan belajar dari data pelatihan untuk melakukan prediksi harga emas.
Model Evaluation: Evaluasi model menggunakan data pengujian. Hitung metrik evaluasi seperti R-squared, Mean Absolute Error (MAE), atau Mean Squared Error (MSE) untuk menilai seberapa baik model Anda berkinerja.
