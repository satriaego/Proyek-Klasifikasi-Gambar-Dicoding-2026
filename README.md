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
Tahap inferensi menggunakan import **SavedModel** untuk memvalidasi model pada data baru.
<p align="center">
  <img src="https://lh3.googleusercontent.com/u/0/d/1FxNPIcXtaCCQiImkeWB_RIhIFr41p_Im" width="600" title="Accuracy Plot">
</p>

---
*Project ini memenuhi seluruh kriteria wajib dan saran submission klasifikasi gambar.*
