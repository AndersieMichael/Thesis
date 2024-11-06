Deteksi Penyakit Kulit Wajah
Proyek ini berfokus pada melatih model deep learning untuk mendeteksi lima jenis penyakit kulit wajah dengan menggunakan dataset yang digabungkan dari berbagai sumber. Kami menggunakan model seperti MobileNetV2, MobileNetV3 (Large dan Small), EfficientNetB2, dan YOLOv8-cls (varian n dan s) untuk melatih dan mengevaluasi kinerja deteksi.

Deskripsi Proyek
Dataset yang digunakan dalam proyek ini diambil dari Kaggle (Dataset Kaggle) dan terdiri dari berbagai gambar penyakit kulit wajah, yaitu Acne, Actinic Keratosis, Basal Cell Carcinoma, Eczema, dan Rosacea. Dataset ini mencakup 440 gambar untuk pelatihan dan validasi, serta 185 gambar untuk pengujian. Hingga saat ini, belum banyak penelitian yang menggunakan dataset ini, sehingga proyek ini menawarkan kontribusi signifikan dalam area ini.

Untuk memperkaya dataset pelatihan, kami juga menambahkan data dari DermNet (Image Library DermNet) dan Google Image, sehingga dapat mendukung dan memperluas cakupan pelatihan model.

Menjalankan Proyek di Google Colab
Anda dapat menjalankan proyek ini langsung melalui Google Colab tanpa instalasi tambahan:

Buka notebook proyek di Google Colab.
Ikuti instruksi yang diberikan dalam notebook untuk memuat data dan menjalankan proses pelatihan.
Lakukan prediksi pada data uji menggunakan model yang telah dilatih.
Cara Penggunaan
Unduh dan siapkan dataset dari sumber yang telah disebutkan.
Jalankan notebook Colab untuk memproses data dan melatih model.
Gunakan model yang telah dilatih untuk melakukan prediksi pada data uji.
