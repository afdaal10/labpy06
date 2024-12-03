# labpy06
Nama : Afdhal Agislam <p>
NIM : 312410445 <p>
Kelas : TI.24.A.5 <p>
Mata Kuliah: Bahasa Pemrograman <p>
# Program Input Nilai
## Flowchart
![gambar 3](https://github.com/user-attachments/assets/6bfecd4c-6f3c-4370-9d2b-a0ca01b1be05)

## Program Python
![gambar 5](https://github.com/user-attachments/assets/895430ce-350b-4149-939b-4b641165012b)

![gambar 6](scr2.png)

### Penjelasan Program
1. Kelas Student:
   - Kelas ini menyimpan informasi tentang mahasiswa, seperti NIM, nama, nilai tugas, UTS, dan UAS.
   - Metode calculate_final_grade menghitung nilai akhir mahasiswa berdasarkan bobot yang diberikan (30% tugas, 35% UTS, dan 35% UAS).
     > class Student:
         def __init__(self, nim, nama, tugas, uts, uas):
            self.nim = nim
            self.nama = nama
            self.tugas = tugas
            self.uts = uts
            self.uas = uas
            self.akhir = self.calculate_final_grade()
     
2. Fungsi display_menu:
   - Fungsi ini menampilkan menu pilihan kepada pengguna dengan opsi untuk melihat, menambah, mengubah, menghapus, atau keluar.
     > def display_menu():
         print("\n[(L)ihat, (T)ambah, (U)bah, (H)apus, (K)eluar]: ", end=' ')
     
3. Fungsi display_students:
   - Fungsi ini menampilkan daftar mahasiswa beserta nilai-nilainya dalam format tabel.
4. Fungsi find_student_index:
   - Fungsi ini mencari indeks mahasiswa dalam daftar berdasarkan Nama yang diberikan. Jika ditemukan, mengembalikan indeks tersebut; jika tidak, mengembalikan None.
5. Fungsi main:
   - Fungsi utama yang menjalankan program.
   - Di dalamnya terdapat loop yang terus berjalan menampilkan menu dan memproses pilihan pengguna:
     - t: Menambah data mahasiswa baru.
     - l: Menampilkan daftar mahasiswa.
     - u: Mengubah data mahasiswa berdasarkan Nama.
     - h: Menghapus data mahasiswa berdasarkan Nama.
     - k: Keluar dari program.
## Hasil Program
![gambar 1](scr3.png)
![gambar 2](scr4.png)