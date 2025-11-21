# Analisis Komparatif Kinerja Klasifikasi Support Vector Machine (SVM) dan Model Baseline pada Prediksi Nilai Akhir Mahasiswa Perguruan Tinggi
## Pendahuluan
Kinerja akademik mahasiswa merupakan indikator vital bagi keberhasilan institusi pendidikan tinggi. Dengan volume data akademik, demografi, dan kebiasaan belajar yang terus meningkat, bidang Educational Data Mining (EDM) menawarkan peluang besar untuk memprediksi hasil akhir mahasiswa. Prediksi yang akurat memungkinkan pengembangan Sistem Peringatan Dini (Early Warning System), yang memungkinkan dosen dan penasihat akademik memberikan intervensi tepat waktu kepada mahasiswa yang berisiko.

## Tujuan Penelitian
1. Mengembangkan model klasifikasi SVM yang teroptimasi untuk prediksi Nilai Akhir Mahasiswa
2. Melakukan analisis perbandingan yang valid antara kinerja SVM dengan model baseline
3. Menarik kesimpulan mengenai efektivitas SVM sebagai metode klasifikasi prediktif dalam kasus kinerja akademik

```
📁 Tugas_Akhir_SVM_Student_Performance/
│
├── 📁 data/
│   ├── raw/
│   │   └── DATA (1).csv                    # Dataset asli (jangan diubah)
│   └── processed/
│       └── data_cleaned.csv                # Data setelah preprocessing (akan dibuat)
│
├── 📁 notebooks/
│   ├── 01_EDA_and_Preprocessing.ipynb      # Tahap 1-2
│   ├── 02_Baseline_Models.ipynb            # Tahap 3
│   ├── 03_SVM_Modeling.ipynb               # Tahap 4
│   └── 04_Evaluation_and_Comparison.ipynb  # Tahap 5
│
├── 📁 models/
│   ├── svm_best_model.pkl                  # Model SVM terbaik (akan dibuat)
│   ├── knn_model.pkl                       # Model KNN (akan dibuat)
│   ├── rf_model.pkl                        # Model Random Forest (akan dibuat)
│   └── ann_model.pkl                       # Model ANN (akan dibuat)
│
├── 📁 results/
│   ├── figures/
│   │   ├── distribution_plots/             # Grafik distribusi data
│   │   ├── confusion_matrices/             # Confusion matrix semua model
│   │   └── comparison_charts/              # Grafik perbandingan model
│   └── metrics/
│       └── model_comparison.csv            # Tabel hasil metrik (akan dibuat)
│
├── 📁 reports/
│   ├── Laporan_Akhir.docx                  # Laporan final
│   └── Presentasi.pptx                     # Slide presentasi
│
├── 📁 scripts/
│   └── utils.py                             # Fungsi helper (opsional)
│
├── Kelompok 8 - Students Performance Evaluation.dox
├── Peper Higher Education Students Performance Evaluation.pdf
└── Peper Referensi A Study of Factors Affecting Learning Efficiency on Higher Education Student.pdf                     
```
Kontributor
Kelompok 08 – Machine Learning
Rahma Fitria Tunnisa & Rahmawati
