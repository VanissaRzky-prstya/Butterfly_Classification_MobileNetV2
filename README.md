# Butterfly Classification Using MobileNetV2
# Deskripsi
Proyek ini merupakan website klasifikasi spesies kupu-kupu menggunakan metode Deep Learning dengan model MobileNetV2. Pengguna dapat mengunggah gambar kupu-kupu, kemudian sistem akan memprediksi spesies beserta tingkat keyakinannya.

# Bahasa Pemrograman
- Python 3
- HTML
- CSS

# Framework, Library, dan API
## Framework
- Flask
## Deep Learning
- TensorFlow
- Keras
## Library
- NumPy
- Pillow
- Matplotlib
- Scikit-learn

# Fitur
- Upload gambar kupu-kupu
- Prediksi spesies kupu-kupu
- Menampilkan tingkat confidence
- Website sederhana menggunakan Flask
- Model hasil training MobileNetV2

## Kelebihan
- Menggunakan Transfer Learning MobileNetV2
- Proses prediksi cepat
- Akurasi tinggi
- Tampilan website sederhana dan mudah digunakan

# Kekurangan
- Hanya dapat mengenali 20 spesies kupu-kupu.
- Prediksi dapat menurun jika gambar buram atau pencahayaan kurang baik.
- Belum mendukung upload banyak gambar sekaligus.

# Dataset

Dataset berasal dari Kaggle:
https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species
Dataset asli memiliki:
- 100 kelas
- 13.610 gambar
Pada proyek ini hanya digunakan **20 kelas pertama** sebagai dataset pelatihan.

# Penjelasan Dataset
Dataset terdiri dari tiga folder.
- train
- valid
- test
Masing-masing kelas memiliki gambar kupu-kupu yang digunakan untuk proses pelatihan, validasi, dan pengujian model.

# Hasil Training
Training Accuracy : 97.99%
Validation Accuracy : 98.00%
Test Accuracy : 98.00%

# Cara Menjalankan
Install library
```bash
pip install -r requirements.txt
```
Jalankan aplikasi
```bash
python app.py
```
Buka browser
```
http://127.0.0.1:5000
```

# Struktur Folder
```
Butterfly_Classification_MobileNetV2
│
├── app.py
├── best_butterfly_model.keras
├── labels.txt
├── requirements.txt
├── UAS_KBL91.ipynb
│
├── templates
│     └── index.html
│
├── static
│     ├── css
│     └── uploads
│
└── dataset-kaggel
      ├── train
      ├── valid
      └── test
```
