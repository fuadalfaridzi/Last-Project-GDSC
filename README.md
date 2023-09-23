# Last-Project-GDSC


Proyek machine learning ini bertujuan untuk memprediksi harga emas di masa depan dengan menggunakan algoritma Regressor Random Forest, berdasarkan data historis harga emas dan atribut-atribut ekonomi terkait. Langkah-langkah proyek meliputi preprocessing data, eksplorasi data, pelatihan model, evaluasi model, dan prediksi harga emas. Tujuan akhirnya adalah memberikan manfaat bagi para pelaku perdagangan emas dan investor dengan menyediakan perkiraan harga emas yang lebih akurat, meskipun harus diingat bahwa prediksi aset keuangan tetap memiliki ketidakpastian.

Work flow:
1. Data Gathering: Kumpulkan data harga emas selama 10 tahun. Data ini harus mencakup harga emas untuk beberapa hari. Sumber data: https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data
2. Data Preprocessing: Lakukan preprocessing pada data. Ini mungkin termasuk menghapus data yang hilang, menormalkan atau mengubah skala data, dan mengatasi outlier jika diperlukan. Pastikan data siap digunakan oleh algoritma machine learning.
3. Data Analysis: Lakukan analisis data untuk memahami hubungan antara fitur (atribut) dalam data, menentukan fitur-fitur yang paling berpengaruh terhadap harga emas, dan visualisasi data untuk mendapatkan wawasan tambahan.
4. Train-Test Split: Bagi data menjadi dua bagian: data pelatihan (training data) dan data pengujian (test data). Data pelatihan akan digunakan untuk melatih model, sedangkan data pengujian akan digunakan untuk menguji kinerja model.
5. Machine Learning Model Selection: Pilih model machine learning yang sesuai untuk tugas ini. Dalam kasus ini, gunakan model Regressor Random Forest. Random Forest adalah salah satu algoritma learning machine yang digunakan untuk tugas-tugas seperti klasifikasi dan regresi. Ini adalah jenis algoritma ensemble, yang berarti itu menggabungkan prediksi dari beberapa model learning machine untuk menghasilkan hasil yang lebih kuat dan stabil daripada menggunakan satu model tunggal.
6. Model Training: Latih model Random Forest Regressor dengan menggunakan data pelatihan. Model ini akan belajar dari data pelatihan untuk melakukan prediksi harga emas.
7. Model Evaluation: Evaluasi model menggunakan data pengujian. Hitung metrik evaluasi seperti R-squared.

** Note: Jika ingin run semua code nya, harap download dulu file "gld_price_data.csv" yang sudah disediakan, lalu upload pada google colab **    
