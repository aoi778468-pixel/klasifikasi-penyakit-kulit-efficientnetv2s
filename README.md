# Sistem Klasifikasi Penyakit Kulit Berbasis Citra Medis Menggunakan CNN Arsitektur EfficientNetV2-S

## Deskripsi

Repository ini berisi source code penelitian klasifikasi enam kelas penyakit kulit berbasis citra medis menggunakan arsitektur *Convolutional Neural Network* (CNN) EfficientNetV2-S.

Kelas yang diklasifikasikan meliputi *Acne*, *Atopic Dermatitis*, *Eczema Herpeticum*, *Keratosis*, *Psoriasis*, dan *Urticaria*.

Pengembangan model menerapkan *transfer learning*, *fine-tuning* dua tahap, *ensemble* dua model (seed 42 dan 59), serta *Test-Time Augmentation* (TTA) empat variasi citra. Model memperoleh akurasi sebesar **93,57%** pada data pengujian.

## Struktur Repository

| Notebook | Deskripsi |
|---|---|
| `01_Persiapan_Dataset.ipynb` | Pengumpulan, pembersihan, deduplikasi, dan pembagian dataset. |
| `02_Pelatihan_dan_Evaluasi_Model.ipynb` | Pelatihan model, evaluasi, dan analisis hasil klasifikasi. |
| `03_Implementasi_Antarmuka_Gradio.ipynb` | Implementasi antarmuka web untuk prediksi penyakit kulit. |

## Dataset

Dataset penelitian berasal dari beberapa repositori publik Kaggle yang mencakup enam kelas penyakit kulit.
Dataset tidak disertakan dalam repository ini. Sumber dataset dapat diakses melalui tautan berikut:

* [Skin Disease Classification](https://www.kaggle.com/datasets/adtech1234/skin-disease-classification)
* [Skin Issues Version 2](https://www.kaggle.com/datasets/ahmedismaiil/skin-issues-version-2-dataset-balanced)
* [Psoriasis Data Set](https://www.kaggle.com/datasets/devendrababu9666/psoriasis-data-set)
* [Skin Diseases Image Dataset](https://www.kaggle.com/datasets/ismailpromus/skin-diseases-image-dataset)
* [SD-198](https://www.kaggle.com/datasets/longngzzz/sd-198)
* [Psoriasis Skin Dataset](https://www.kaggle.com/datasets/pallapurajkumar/psoriasis-skin-dataset)
* [DermNet](https://www.kaggle.com/datasets/shubhamgoel27/dermnet)

## Teknologi

- Python
- TensorFlow
- EfficientNetV2-S
- NumPy
- Scikit-learn
- Matplotlib
- Gradio

## Menjalankan Notebook

Seluruh notebook dirancang untuk dijalankan menggunakan Kaggle Notebook dengan dukungan GPU. Jalankan notebook secara berurutan:

1. Persiapan dataset.
2. Pelatihan dan evaluasi model.
3. Implementasi antarmuka Gradio.

Direktori dataset dan lokasi penyimpanan file model perlu disesuaikan dengan lingkungan eksekusi masing-masing.

---

*Repository ini merupakan dokumentasi source code penelitian Tugas Akhir untuk keperluan akademik dan bukan merupakan pengganti diagnosis medis profesional.*
