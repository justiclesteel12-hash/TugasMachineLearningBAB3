# TugasMachineLearningBAB3
3. Praktikum Bab 3: Penanganan Imbalanced Data

### Perbandingan F1-Score Berbagai Pendekatan:
1. *Baseline (Tanpa Penanganan):* Memiliki skor $F_1$ paling rendah karena model cenderung mengabaikan kelas minoritas dan hanya menebak kelas mayoritas.
2. *SMOTE (Oversampling):* Meningkatkan performa kelas minoritas dengan cara sintetis, menghasilkan skor $F_1$ yang jauh lebih baik[cite: 6].
3. *Undersampling:* Mengurangi data mayoritas agar seimbang dengan minoritas, membantu model mengenali pola kelas minoritas dengan baik.
4. *Class Weight ("balanced"):* Memberikan bobot otomatis pada fungsi loss sehingga model lebih peka terhadap kelas minoritas tanpa mengubah jumlah data.

### Kesimpulan:
Pendekatan berbasis penyeimbangan data seperti *SMOTE* atau *Class Weight* jauh lebih efektif untuk kasus imbalanced data dibandingkan menggunakan *Baseline*, karena metrik evaluasi seperti $F_1$-Score pada kelas minoritas dapat dioptimalkan dengan baik.
