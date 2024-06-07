# Final-Project-for-AI
# Pemeliharaan Prediktif Mesin Milling
Repositori ini berisi kode dan sumber daya untuk melakukan pemeliharaan prediktif pada data mesin milling. Tujuan utamanya adalah untuk memprediksi kegagalan mesin menggunakan berbagai teknik pembelajaran mesin.
1. Dataset
   Dataset yang digunakan dalam proyek ini adalah ai4i2020.csv. Dataset ini berisi fitur-fitur, yaitu: Suhu udara [K], Suhu proses [K], Kecepatan rotasi [rpm], Torsi [Nm], Keausan alat [min], dan Kegagalan mesin (target).
   
2. Syarat Menjalankan Kode
   Untuk menjalankan kode ini, diperlukan paket Python berikut:
numpy
pandas
scikit-learn
imbalanced-learn
matplotlib
seaborn
plotly
tensorflow
Kemudian, dapat diinstal paket-paket ini menggunakan pip:
"pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn plotly tensorflow"

3. Persiapan Data
   - Dataset dimuat dari ai4i2020.csv.
   - Menghapus duplikat dan nilai yang hilang.
   - Menormalisasi fitur numerik menggunakan StandardScaler.
   - Membuat fitur baru berdasarkan fitur yang sudah ada.
   - Membagi data menjadi set pelatihan, validasi, dan uji.
     
4. Pelatihan Model
   - Mendefinisikan model, menggunakan jaringan saraf dengan Keras.
   - Mengompilasi model, menggunakan optimizer Adam dan fungsi loss binary cross-entropy.
   - Melatih model, melatih model pada data pelatihan.

5. Evaluasi Model
   - Memprediksi kelas, dengan menggunakan model yang dilatih untuk memprediksi data uji.
   - Menghitung metrik, dengan menghitung confusion matrix, classification report, akurasi, presisi, recall, F1 score, kurva ROC, dan kurva precision-recall.
   - Pentingnya fitur, untuk membuat plot pentingnya fitur.

6. Menjalankan Kode
   Ikuti langkah-langkah ini untuk menjalankan kode dan menghasilkan hasil.
   1. Setel jalur data, yaitu dengan memastikan variabel DATA_PATH menunjuk ke direktori yang berisi ai4i2020.csv.
   2. Jalankan skrip persiapan data, yaitu dengan menjalankan skrip untuk membersihkan, menormalisasi, dan membagi data.
   3. Latih model, yaitu dengan menjalankan skrip untuk mendefinisikan, mengompilasi, dan melatih model.
   4. Evaluasi model, yaitu dengan menjalankan skrip untuk mengevaluasi model dan membuat plot hasil.

7. Hasil
   Hasil dari pelatihan dan evaluasi model akan ditampilkan dalam bentuk, berikut ini:
   - Confusion Matrix
   - Classification Report
   - Akurasi, Presisi, Recall, F1 Score
   - Kurva ROC
   - Kurva Precision-Recall
   - Pentingnya Fitur
Visualisasi dan metrik ini akan membantu memahami kinerja model pemeliharaan prediktif untuk mesin milling.
Panduan ini dapat membantu pengguna memahami dan menjalankan kode dengan efektif.
