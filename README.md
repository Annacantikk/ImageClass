# Image Classification (Shoe, Boot, Sandal)

Model ini digunakan untuk klasifikasi tiga jenis sepatu: Shoe, Boots, Sandal yang berisi model deep learning yang dikembangkan menggunakan TensorFlow, dengan format yang didukung untuk berbagai platform:

SavedModel → Untuk deployment di server atau cloud.
TensorFlow Lite (TFLite) → Untuk penggunaan di perangkat mobile dan embedded.
TensorFlow.js (TFJS) → Untuk eksekusi di browser dan aplikasi berbasis JavaScript.

ImageClass
├───model_Anna_tfjs
|   ├───group1-shard1of1.bin
|   └───model.json
├───model_Anna_tflite
|   ├───model.tflite
|   └───label.txt
├───Anna_model
|   ├───saved_model.pb
|   └───variables
├───Shoe_vs_Boots_vs_Sandal.ipynb
├───README.md
└───requirements.txt

model_Anna_tfjs/ → Model dalam format TensorFlow.js.
model_Anna_tflite/ → Model dalam format TensorFlow Lite.
Anna_model/ → Model dalam format standar TensorFlow.
Shoe_vs_Boots_vs_Sandal.ipynb → Notebook yang berisi kode untuk pelatihan dan konversi model.
requirements.txt → Daftar pustaka yang diperlukan untuk menjalankan model.
README.md → Dokumentasi proyek.
