# Animals-10 Image Classification (MobileNetV2)

Proyek klasifikasi gambar berbasis **Transfer Learning** menggunakan arsitektur **MobileNetV2** untuk mengenali 10 jenis hewan dari dataset **Raw Animals-10** (Kaggle). Model ini dioptimalkan untuk performa tinggi dan fleksibilitas deployment.

## Key Features
* **Dataset:** 10,000+ gambar dengan 10 kelas kategori.
* **Architecture:** Pre-trained **MobileNetV2** (Sequential) dengan *Global Average Pooling* dan *Dropout*.
* **Optimization:** Implementasi callback `EarlyStopping` dan `ReduceLROnPlateau` untuk stabilitas training.
* **Multi-Format Deployment:** Export model ke **SavedModel**, **TF-Lite**, dan **TFJS**.



## Model Performance
Model mencapai akurasi di atas **95%** pada data training maupun validasi. Visualisasi performa tersedia dalam notebook.

| Metric | Score |
| :--- | :--- |
| **Test Accuracy** | 98.56% |
| **Loss Data Test** | 0.0570 |





## Inference & Deployment
Proyek ini mencakup tahap inferensi menggunakan **TF-Lite** untuk memvalidasi model pada data baru secara efisien. Output prediksi dan bukti eksekusi tersedia di bagian akhir notebook.

---
*Project ini memenuhi seluruh kriteria wajib dan saran submission klasifikasi gambar.*
