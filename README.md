# Prediksi Penyakit Jantung menggunakan Machine Learning

## Ikhtisar Proyek
Penyakit jantung merupakan salah satu penyebab kematian tertinggi di dunia. Tantangan utama adalah banyak pasien baru menyadari adanya risiko ketika penyakit sudah pada tahap serius.  
Proyek ini bertujuan untuk membangun model machine learning yang mampu memprediksi risiko penyakit jantung pada pasien berdasarkan data medis, sehingga memungkinkan deteksi dini dan pencegahan lebih efektif.  

Target model:  
- Akurasi ≥ 70%  
- Recall tinggi agar lebih sensitif dalam mendeteksi pasien berisiko  

## Tautan Dataset
Dataset yang digunakan: [UCI / Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  

Fitur utama: usia, jenis kelamin, tekanan darah, kolesterol, detak jantung maksimal, hasil tes thalassemia, dan status target (ada/tidak penyakit jantung).  

## Wawasan & Temuan
Hasil analisis dan eksperimen menunjukkan:  
- Variabel yang paling berpengaruh terhadap risiko penyakit jantung adalah **usia, tipe nyeri dada (cp), detak jantung maksimal (thalach), dan depresi ST (oldpeak)**.  
- Model **Random Forest** memberikan performa terbaik dengan akurasi sekitar **80%** dan recall yang cukup tinggi, sehingga efektif mendeteksi pasien berisiko.  
- Distribusi data menunjukkan pasien dengan **usia lebih tua, kolesterol tinggi, dan hasil abnormal pada tes EKG** lebih rentan terkena penyakit jantung.  
- Visualisasi confusion matrix memperlihatkan bahwa model relatif seimbang dalam memprediksi pasien yang sehat maupun berisiko.  

## Rekomendasi
- Model dapat dijadikan dasar **alat screening awal** untuk mendeteksi pasien berisiko tinggi sebelum dilakukan pemeriksaan medis lanjutan.  
- Pasien dengan faktor risiko utama (usia tinggi, nyeri dada, hasil EKG abnormal) perlu mendapatkan perhatian lebih dalam pemeriksaan klinis.  
- Dataset dapat diperluas dengan data riwayat keluarga, gaya hidup (merokok, aktivitas fisik) agar prediksi semakin akurat.  

## Dukungan AI
Proyek ini memanfaatkan teknik Machine Learning untuk analisis dan prediksi:  
- **Algoritma yang digunakan**: Logistic Regression, Decision Tree, Random Forest, SVM  
- **Evaluasi model**: Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC Curve  
- **AI Insight**: Feature importance dari Random Forest untuk mengetahui variabel paling berpengaruh  

Dengan dukungan AI/ML, proyek ini membantu menghasilkan **wawasan berbasis data** yang dapat digunakan sebagai rekomendasi medis preventif.  
