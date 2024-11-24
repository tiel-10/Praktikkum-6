**PRAKTIKUM 6**
# Soal
**Tugas Praktikum**

Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan
- Program dibuat dengan menggunakan Dictionary
- Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md. 
- Commit dan push repository ke github.

# Flowchart
![flowchart Praktikum-6](https://github.com/user-attachments/assets/686c1995-5c66-4530-b35d-e8687abe7a74)

# Jawaban
Alur Flowchart:

1. Mulai
- Flowchart dimulai dari titik awal, menandakan permulaan proses algoritma
2. Input Nama dan NIM
- Tahap pertama meminta pengguna untuk memasukkan identitas
- Pengguna diminta menginput nama dan NIM (Nomor Induk Mahasiswa)
- Ini merupakan proses pengumpulan data awal
3. Input Nilai Tugas, UTS, dan UAS
- Selanjutnya pengguna menginputkan tiga komponen penilaian:
  - Nilai Tugas
  - Nilai Ujian Tengah Semester (UTS)
  - Nilai Ujian Akhir Semester (UAS)
- Ketiga nilai ini akan digunakan untuk perhitungan selanjutnya
4. Hitung Nilai Akhir
- Sistem melakukan kalkulasi nilai akhir
- Perhitungan dilakukan dengan rumus: Nilai Akhir = (Tugas * 30%) + (UTS * 30%) + (UAS * 40%)
- Bobot penilaian berbeda untuk setiap komponen
5. Tentukan Nilai Huruf
- Berdasarkan nilai akhir yang dihitung, sistem menentukan nilai huruf:
  - A = 80-100
  - B = 70-79
  - C = 60-69
  - D = 50-59
  - E = <50
6. Tampilkan Hasil
- Menampilkan keseluruhan informasi:
  - Nama
  - NIM
  - Nilai Tugas
  - Nilai UTS
  - Nilai UAS
  - Nilai Akhir
  - Nilai Huruf
7. Selesai
- Proses flowchart berakhir

Flowchart ini menggambarkan algoritma sederhana untuk menghitung nilai akhir mahasiswa dengan mempertimbangkan tiga komponen penilaian dan mengonversinya ke dalam nilai huruf.
