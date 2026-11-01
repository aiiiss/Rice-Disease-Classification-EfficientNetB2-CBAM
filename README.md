# Rice Disease Classification using EfficientNetB2 & CBAM

Repository ini berisi implementasi model *Deep Learning* untuk klasifikasi penyakit daun padi menggunakan arsitektur **EfficientNetB2** yang ditingkatkan dengan **Convolutional Block Attention Module (CBAM)** serta analisis interpretabilitas model menggunakan **Grad-CAM**.

## 🚀 Fitur Utama
- **Arsitektur CNN Lanjutan:** Memanfaatkan EfficientNetB2 yang efisien dan akurat untuk ekstraksi fitur citra daun padi.
- **Attention Mechanism (CBAM):** Mengintegrasikan *Channel and Spatial Attention* untuk memfokuskan model pada bagian daun yang terinfeksi secara spesifik.
- **Explainable AI (Grad-CAM):** Menyediakan visualisasi peta aktivasi (heatmap) untuk melihat bagian gambar mana yang menjadi fokus utama keputusan model.
- **Eksperimen Multi-Fase:** Pelatihan model dibagi dalam beberapa fase (Fase 1 & Fase 2) untuk mengoptimalkan performa bobot model (`.h5`).

## 📁 Struktur Repository
- `best_fase1_*.weights.h5` & `best_fase2_*.weights.h5`: Bobot model terbaik hasil pelatihan dari berbagai fase.
- `confusion_matrix.png`: Visualisasi matriks kebingungan untuk evaluasi performa kelas.
- `gradcam_komparatif.png` / `gradcam_manual.png`: Hasil visualisasi Grad-CAM.
- `result_*.json` & `probs_*.npy`: Log hasil evaluasi dan probabilitas prediksi model.

## 🛠️ Teknologi & Tools
- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Matplotlib
