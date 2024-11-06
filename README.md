# Deteksi Penyakit Kulit Wajah

Proyek ini berfokus pada melatih model deep learning untuk mendeteksi lima jenis penyakit kulit wajah dengan menggunakan dataset yang digabungkan dari berbagai sumber. Kami menggunakan model seperti MobileNetV2, MobileNetV3 (Large dan Small), EfficientNetB2, dan YOLOv8-cls (varian n dan s) untuk melatih dan mengevaluasi kinerja deteksi.

## Deskripsi Proyek

Dataset yang digunakan dalam proyek ini diambil dari Kaggle ([Dataset Kaggle](https://www.kaggle.com/datasets/amellia/face-skin-disease/data)) dan terdiri dari berbagai gambar penyakit kulit wajah, yaitu Acne, Actinic Keratosis, Basal Cell Carcinoma, Eczema, dan Rosacea. Dataset ini mencakup 440 gambar untuk pelatihan dan validasi, serta 185 gambar untuk pengujian. Hingga saat ini, belum banyak penelitian yang menggunakan dataset ini, sehingga proyek ini menawarkan kontribusi signifikan dalam area ini.

Untuk memperkaya dataset pelatihan, kami juga menambahkan data dari DermNet ([Image Library DermNet](https://dermnetnz.org/image-library)) dan Google Image, sehingga dapat mendukung dan memperluas cakupan pelatihan model.

Dataset yang digunakan : ([Dataset](https://drive.google.com/drive/folders/1E-GUnlG7FOssWxzrMuNSgYIpEqY1_smk?usp=sharing))

## Menjalankan Proyek di Google Colab

Anda dapat menjalankan proyek ini langsung melalui Google Colab tanpa instalasi tambahan:

1. Buka notebook proyek di Google Colab.
2. Perhatikan letak penyimpanan dataset dan letak penyimpanan model terbaik.
3. jalankan proses pelatihan.
4. Lakukan prediksi pada data uji menggunakan model yang telah dilatih.

## Cara Penggunaan

1. Unduh dan siapkan dataset dari sumber yang telah disebutkan.
2. Perhatikan letak penyimpanan dataset dan letak penyimpanan model terbaik.
3. jalankan proses pelatihan.
3. Gunakan model yang telah dilatih untuk melakukan prediksi pada data uji.
