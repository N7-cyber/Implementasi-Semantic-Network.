# 🧠 Implementasi Semantic Network & Knowledge Base

Repositori ini berisi implementasi dari struktur **Semantic Network** yang dikonversi menjadi **Knowledge Base** dan diproses menggunakan bahasa pemrograman Python. Proyek ini disusun untuk memenuhi tugas mata kuliah **Kecerdasan Buatan**.

## 👤 Identitas Mahasiswa
* **Nama:** Muhammad Rafi Nur Setiawan
* **Kelas:** IF24B
* **Program Studi:** Teknik Informatika
* **Universitas:** Universitas Nahdlatul Ulama Sidoarjo (UNUSIDA)

## 📝 Detail Tugas
Proyek ini mencakup penyelesaian 5 tahapan instruksi berikut:
- [x] **1. Buat Semantic Network:** Visualisasi graf relasi antar entitas (Mahasiswa, Dosen, Matkul).
- [x] **2. Jadikan Knowledge:** Ekstraksi graf menjadi format representasi pengetahuan (*Triple*).
- [x] **3. Tulis Code Collab dengan Python:** Pembuatan algoritma pencarian properti berbasis rekursif dan *Dictionary*.
- [x] **4. Demo-kan:** Simulasi tanya-jawab interaktif berbasis CLI.
- [x] **5. Upload pada GitHub:** Dokumentasi dan penyimpanan repositori.

## ⚙️ Konsep Sistem
Sistem ini memodelkan data akademik secara semantik. Dengan menerapkan konsep *inheritance* (pewarisan sifat menggunakan relasi `is-a`), program dapat melakukan penarikan kesimpulan sederhana. 

Sistem dapat memahami bahwa entitas spesifik memiliki atribut dari kelas umumnya, dan mampu menjawab pertanyaan interaktif seperti:
* Tanya: `rafi mengambil` ➔ Jawaban: `kecerdasan-buatan`
* Tanya: `kecerdasan-buatan ruangan` ➔ Jawaban: `r404`

## 🚀 Cara Menjalankan Program
1. Buka file implementasi Python (Jupyter Notebook / `.ipynb`).
2. *Run* semua sel kode (*cells*).
3. Saat program interaktif berjalan, ketikkan perintah berdasarkan entitas dan properti (contoh: `rafi jurusan` atau `ali prodi`).
4. Ketik `exit` untuk menghentikan program.
