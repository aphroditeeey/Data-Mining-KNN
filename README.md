## K-Nearest Neighbor (KNN)

K-Nearest Neighbor (KNN) adalah algoritma dalam :contentReference[oaicite:0]{index=0} yang digunakan untuk klasifikasi dengan cara menentukan label suatu data berdasarkan kedekatan dengan data lain.

KNN bekerja dengan prinsip bahwa data yang memiliki karakteristik mirip akan berada pada jarak yang berdekatan.


## Cara Penerapan KNN pada Dataset

Langkah-langkah yang dilakukan dalam analisis ini adalah:

1. **Menyiapkan Data**
   - Memuat dataset
   - Menghapus data yang tidak diperlukan

2. **Preprocessing**
   - Menangani missing value
   - Mengubah data kategorikal menjadi numerik (encoding)

3. **Normalisasi Data**
   - Menggunakan StandardScaler agar semua fitur memiliki skala yang sama

4. **Membagi Data**
   - Data dibagi menjadi data training dan testing

5. **Membangun Model KNN**
   - Menentukan nilai K (jumlah tetangga)
   - Melatih model menggunakan data training

6. **Melakukan Prediksi**
   - Model digunakan untuk memprediksi data testing

7. **Evaluasi Model**
   - Menggunakan akurasi, confusion matrix, dan classification report
