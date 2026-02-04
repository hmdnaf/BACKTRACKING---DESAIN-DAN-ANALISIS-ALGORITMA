# BACKTRACKING---DESAIN-DAN-ANALISIS-ALGORITMA

Repository ini dibuat untuk memenuhi **Ujian / Tugas** pada mata kuliah **Desain dan Analisis Algoritma**.  
Project ini berfokus pada penerapan konsep **algoritma backtracking** untuk menyelesaikan masalah konflik pekerja/karyawan (backtracking) berdasarkan dataset yang tersedia.


### 👤 Author
**Hamdan Al Fattah (105841108323)**  
BACKTRACKING – Desain dan Analisis Algoritma - 5C

---

## 📌 Deskripsi Project

Algoritma *backtracking* adalah paradigma algoritma yang digunakan untuk mencari solusi dari masalah dengan ruang solusi yang besar melalui pencarian rekursif dan *pruning*.  
Ide dasarnya adalah mencoba membangun solusi secara bertahap dan **kembali (*backtrack*)** ketika mencapai keadaan yang tidak konsisten atau tidak memenuhi batasan. :contentReference[oaicite:0]{index=0}

Project ini menggunakan backtracking untuk menyelesaikan konflik pada dataset dalam **`dataset_50_karyawan_konflik_backtracking.xlsx`**, yang kemungkinan memetakan konflik di antara sejumlah karyawan dan mencari penempatan yang valid.

---

---

## 📄 Penjelasan File

### 1. `dataset_50_karyawan_konflik_backtracking.xlsx`

Ini merupakan **dataset Excel** berisi data konflik antar karyawan yang akan digunakan untuk solusi dengan algoritma backtracking.

---

### 2. `revisi2.ipynb`

Notebook Jupyter ini kemungkinan berisi:
- Implementasi algoritma backtracking untuk menyelesaikan konflik karyawan.
- Analisis atau eksperimen dengan dataset.
- Visualisasi atau langkah-langkah pengerjaan.

Notebook ini adalah inti dari project karena memuat kode dan hasil eksekusi backtracking secara interaktif.

---

## 🧠 Konsep Utama yang Digunakan

- **Backtracking** – strategi pencarian solusi dengan mencoba kandidat dan kembali (*prune*) jika tidak memenuhi batasan. :contentReference[oaicite:1]{index=1}  
- **Pencarian Rekursif** – metode pemanggilan fungsi itu sendiri untuk menyelesaikan bagian kecil dari masalah.  
- **Constraint Satisfaction** – pemenuhan batasan tertentu pada data input sebelum solusi diterima.

---

## ▶️ Cara Menjalankan

1. Pastikan Anda menggunakan **Jupyter Notebook** atau **Google Colab**.  
2. Buka file `revisi2.ipynb`.  
3. Jalankan semua sel dari atas ke bawah untuk melihat proses backtracking dan outputnya.

---

## 🎯 Tujuan Project, Struktur Folder, dan Author

### 🎯 Tujuan Project
- Memahami algoritma backtracking secara langsung melalui implementasi.  
- Menyelesaikan permasalahan konflik (constraint satisfaction) pada dataset.  
- Mengaplikasikan teori *Design & Analysis of Algorithms* dalam praktik.

### 📂 Struktur Folder
```
BACKTRACKING---DESAIN-DAN-ANALISIS-ALGORITMA/
│
├── README.md
├── dataset_50_karyawan_konflik_backtracking.xlsx
└── revisi2.ipynb
```

