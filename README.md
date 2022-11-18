# latihan 4

hallo guys, disini saya akan mencoba latihan membuat list dengan bahasa pemrograman python di vscode.
1. pertama saya akan membuat sebuah list 5 elemen
![Screenshot (39)](https://user-images.githubusercontent.com/115749975/202351629-4c1959af-d2db-4d38-bb30-714556cdfbfb.png)
gambar di atas saya membuat akses list:
- menampilkan elemen ke 3
- mengambil elemen ke 2 sampai akhir
- mengambil elemen terakhir

2. mengubah elemen list
![Screenshot (40)](https://user-images.githubusercontent.com/115749975/202352074-4eabef8e-d2c0-4ea5-ba47-1f09fbcd45ae.png)
- mengubah elemen ke 4 dengan nilai lainnya
- mengubah elemen ke 4 sampai dengan elemen terakhir.

3. menambah elemen list.
![Screenshot (41)](https://user-images.githubusercontent.com/115749975/202352299-53199171-89cc-49ed-905b-12ba206482aa.png)
- mengambil 2 bagian dari list a dan jadikan list b
- menambahkan list b dengan nilai string
- menambakan list b dengan 3 nilai
- menggabungkan list b dengan list a

praktikum 4 pemrograman

jadi disini saya membuat program sederhana menambahkan data kedalam sebuah list

-berikut adalah tampilan program menggunakan bahasa python
![Screenshot (45)](https://user-images.githubusercontent.com/115749975/202710647-472b0508-2f1d-4617-924e-b0e3d8b84a33.png)

-from prettytable import PrettyTable Membuat header table menggunakan prettytable. Variabel import berfungsi untuk memanggil file lain di dalam satu module yang berbeda.

-print("Program Input Data Mahasiswa") print() untuk menampilkan kalimat yang di input.

-tabelNama = PrettyTable(["No" ,"Nama" ,"NIM" ,"Nilai Tugas" ,"Nilai UTS" ,"Nilai UAS" ,"Nilai Akhir" ])
a = 0
-(Deklarasi list)untuk menginput data yang dimasukkan kedalam list. input tabelNama untuk memanggil. sedangkan PrettyTable berfungsi untuk membungkus semua list. Deklarasi *a = 0* untuk membuat nomor pada isi table.

-Membuat program perulangan menggunakan py while True:
 a += 1
 b = input("Masukkan Nama : ")
 c = input("Masukkan NIM : ")
 d = int(input("Masukkan Nilai Tugas : "))
 e = int(input("Masukkan Nilai UTS : "))
 f = int(input("Masukkan Nilai UAS :" ))
 g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))
a += 1 untuk menginput nomer pada awal table. deklarasi list dan Memasukkan Input Dengan Fungsi input() untuk menulis nama yang akan kita simpan dalam variabel. int(input()) untuk menginput tipe data interger (bilangan bulat) dalam variabel.

{:.2f}".format((d*.30) + (e*.35) + (f*.35)) untuk menginput Nilai Akhir yang di ambil dari perhitungan 3 komponen nilai.

 tabelNama.add_ro ([a,b,c,d,e,f,g])
 tabelNama.horizontal_char = "="
 tabelNama.junction_char = "="
 variabel di atas adalah untuk membentuk sebuah table.
Program input tanya [y/t], apabila jawaban t atau T, maka program inputan dihentikan statement break dan akan menampilkan data yang sudah diinput.
 

-dan berikut adalah outputan nya
![Screenshot (46)](https://user-images.githubusercontent.com/115749975/202711757-03b2c6dc-1916-495d-990b-b96d7fa9f7ce.png)

TERIMA KASIH ATAS.....