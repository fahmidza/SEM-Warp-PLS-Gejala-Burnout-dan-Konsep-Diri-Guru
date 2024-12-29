# 📊 **Analisis Pengaruh Teacher Self-Concept dan Teacher Efficacy terhadap Burnout Guru** 🔥

## 📚 **Deskripsi Proyek**
Proyek ini bertujuan untuk menganalisis hubungan antara **Teacher Self-Concept (TSC)**, **Teacher Efficacy (TE)**, dan tiga aspek burnout guru:
1. **Emotional Exhaustion (EE)**: Kelelahan emosional.
2. **Depersonalization (DE)**: Depersonalisasi.
3. **Reduced Personal Achievement (RPA)**: Penurunan pencapaian pribadi.

Metode analisis menggunakan pendekatan **Structural Equation Modeling (SEM)** berbasis **Warp Partial Least Squares (WarpPLS)**. Penelitian dilakukan menggunakan data dari kuesioner yang diisi oleh 200 tenaga pengajar.

---

## 🎯 **Tujuan**
1. Menganalisis hubungan antara **Teacher Self-Concept (TSC)** dan **Teacher Efficacy (TE)**.
2. Mengukur pengaruh **Teacher Efficacy (TE)** terhadap tiga aspek burnout guru (**EE**, **DE**, **RPA**).
3. Mengevaluasi kualitas model SEM yang digunakan.
4. Memberikan rekomendasi solusi berbasis hasil analisis untuk mengurangi burnout guru.

---

## 🛠️ **Tahapan Analisis**
1. **Pengumpulan Data**:
   - Data diperoleh melalui kuesioner dengan indikator:
     - **5 indikator** untuk **TSC**, **TE**, **EE**, dan **RPA**.
     - **3 indikator** untuk **DE**.

2. **Pemodelan SEM-WarpPLS**:
   - **Outer Model**: Mengukur hubungan antara variabel laten dan indikator.
   - **Inner Model**: Mengukur hubungan antara variabel laten.

3. **Pengujian Validitas dan Reliabilitas**:
   - **Convergent Validity** dan **Discriminant Validity** untuk menguji validitas.
   - **Composite Reliability** untuk menguji reliabilitas.

4. **Evaluasi Model**:
   - Goodness-of-Fit (GoF) dengan kriteria seperti Average Path Coefficient (APC), Average R-squared (ARS), dan lainnya.

5. **Interpretasi Hubungan Antarvariabel**:
   - Analisis signifikansi hubungan menggunakan koefisien lintasan dan p-value.

6. **Rekomendasi Solusi**:
   - Berdasarkan hasil analisis, menyusun langkah strategis untuk mendukung kesejahteraan guru.

---

## 🌟 **Hasil Utama**
1. **Hubungan Antarvariabel**:
   - **TSC → TE**: Koefisien lintasan 0.649, p-value < 0.001 (signifikan).
   - **TE → EE**: Koefisien lintasan 0.698, p-value < 0.001 (signifikan).
   - **TE → DE**: Koefisien lintasan 0.647, p-value < 0.001 (signifikan).
   - **TE → RPA**: Koefisien lintasan 0.652, p-value < 0.001 (signifikan).

2. **Goodness-of-Fit (GoF)**:
   - **Nilai GoF**: 0.527 (kategori baik).
   - Semua kriteria evaluasi model terpenuhi.

3. **Kesimpulan**:
   - Persepsi diri guru (**TSC**) memiliki dampak signifikan pada kepercayaan diri (**TE**).
   - Kepercayaan diri guru (**TE**) secara signifikan memengaruhi risiko burnout pada tiga aspek (**EE**, **DE**, **RPA**).

4. **Rekomendasi**:
   - Program pelatihan untuk meningkatkan **TSC** dan **TE**.
   - Dukungan kesejahteraan mental untuk mencegah burnout.
   - Praktik reflektif untuk meningkatkan kualitas pengajaran.

---

## 📂 **Struktur File**
- **Analisis WarpPLS.prj**: File proyek WarpPLS untuk pemodelan SEM.
- **Hasil Analisis.pdf**: Laporan detail hasil analisis SEM-WarpPLS.
- **Presentation.pdf**: Ringkasan visual hasil analisis dan rekomendasi utama.

---

## 📦 **Teknologi dan Metode**
- **WarpPLS 7.0**: Untuk analisis SEM-WarpPLS.
- **Metode**:
  - Structural Equation Modeling (SEM).
  - Validitas (Convergent dan Discriminant Validity).
  - Reliabilitas (Composite Reliability).

---

## ✍️ **Penulis**
Proyek ini dikembangkan oleh **Tim Dodoco** untuk kompetisi NSC 2024:
- **Dzulfahmi Dzakia Ahmad**
- **Kurniawan Chandra Wijaya**
