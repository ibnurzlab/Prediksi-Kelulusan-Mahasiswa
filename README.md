# Prediksi-Kelulusan-Mahasiswa
Proyek ini bertujuan untuk memprediksi apakah mahasiswa akan lulus tepat waktu menggunakan pendekatan machine learning. Dataset mencakup data akademik mahasiswa seperti nilai IPS per semester dan atribut lainnya untuk melatih model agar bisa mengenali pola kelulusan.

---

## 🔄 Alur Proyek
1. **Integrasi dan Transformasi Data**  
   Melakukan penggabungan data dari beberapa sumber dan mengubahnya menjadi format yang siap diolah.

2. **Pengolahan IPS dan Gabung dengan DF_Kelulusan**  
   Menghitung Indeks Prestasi Semester (IPS), lalu menggabungkan data IPS dengan data status kelulusan untuk membuat target prediksi.

3. **Penyesuaian Kolom dan Data Cleaning**  
   Menyeleksi kolom-kolom yang relevan, membersihkan missing values, dan menghapus duplikat berdasarkan NIM.

4. **Pemeriksaan Missing Values dan Duplikasi**  
   Memastikan data bebas dari nilai kosong dan entri ganda agar model bisa belajar dari data yang bersih dan berkualitas.

5. **Pelatihan dan Evaluasi Model**  
   Membagi data menjadi data training dan testing, melatih model klasifikasi menggunakan **Support Vector Machines (SVM)**, dan mengevaluasi performa model.

---

## 🧠 Algoritma
- **Support Vector Machines (SVM)** sebagai model utama untuk memprediksi kelulusan mahasiswa tepat waktu.

---

## 🛠️ Tools & Libraries
- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy** untuk pengolahan data
- **Scikit-learn** untuk pemodelan dan evaluasi model
- **Matplotlib / Seaborn** untuk visualisasi data (opsional)

---
