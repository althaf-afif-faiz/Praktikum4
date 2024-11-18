# Praktikum4
## Nama : Althaf Afif Faiz
## Nim  : 312410404
## Kelas : TI.24.A.3

# Program Python menambahkan data ke dalam sebuah list

Rincian dari program tersebut yaitu:

• Progam meminta memasukkan data sebanyak-banyaknya (gunakan
perulangan)

• Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban
t (Tidak), maka program akan menampilkan daftar datanya.

• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)

# Tampilan Code Program List 
![code project4](https://github.com/user-attachments/assets/a42be838-a672-4cde-bbd4-f10b4469376e)

Berikut adalah penjelasan setiap bagian program:

Class Mahasiswa: Mendefinisikan class dengan nama "Mahasiswa".

Constructor init(): Merupakan method constructor yang digunakan untuk menginisialisasi objek "Mahasiswa" dengan atribut yang diberikan.

Method hitung_nilai_akhir(): Merupakan method yang digunakan untuk menghitung nilai akhir mahasiswa dengan perhitungan (nilai tugas * 0.30) + (nilai UTS * 0.35) + (nilai UAS * 0.35).

Function tambah_data(): Merupakan function yang digunakan untuk meminta input data mahasiswa dari user seperti nama, NIM, nilai tugas, nilai UTS, dan nilai UAS. Kemudian, 

function ini membuat objek "Mahasiswa" baru dengan data yang diinputkan dan mengembalikan objek tersebut.

Function tampilkan_data(): Merupakan function yang digunakan untuk menampilkan data semua mahasiswa yang ada di dalam list "mahasiswa_list".

Main Program:

Menginisialisasi list kosong "mahasiswa_list".

Memasuki loop while True untuk meminta input dari user apakah ingin menambah data atau tidak.

Jika user memilih "y" (ya), maka program memanggil function tambah_data() untuk menambahkan data mahasiswa baru ke dalam list "mahasiswa_list".

Jika user memilih "t" (tidak), maka program keluar dari loop while.

Jika user memasukkan input selain "y" atau "t", maka program menampilkan pesan "Pilihan tidak valid."

Setelah loop while selesai, program memanggil function tampilkan_data() untuk menampilkan semua data mahasiswa yang sudah disimpan di dalam list "mahasiswa_list".

# Hasil Code dari Program List
![Hasil Codingan](https://github.com/user-attachments/assets/74814692-5d32-430c-ba0b-a6e2cfd11552)

Berikut Flowchart dari Program List

![flowchart project4](https://github.com/user-attachments/assets/7efb4e30-a78b-4e26-9346-b7f81f78cc72)


# Penjelasan singkat algoritma dari flowchart
flowchart tersebut adalah algoritma untuk input data mahasiswa, menghitung nilai akhir, dan menampilkan data mahasiswa.

Pertama, input nama mahasiswa.

Kedua, input nilai tugas, uts, dan uas.

Ketiga, hitung nilai akhir berdasarkan bobot nilai tugas, uts, dan uas.

Keempat, simpan data mahasiswa.

Terakhir, tanyakan apakah akan menambah data mahasiswa lagi. Jika ya, ulangi langkah input data. Jika tidak, tampilkan data mahasiswa yang telah diinput.






