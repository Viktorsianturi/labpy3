Nama : Viktor M Sianturi

Nim : 311810676

Kelas : TI.18.C.2

Latihan 1 (Program menampilkan n bilangan acak lebih < 0.5)

1).Alur Agoritmanya :

=>import random memanggil file random

=>n = int(input("Masukan nilai N : ")) input variabel n, tipe data integer

=>for i in range(n) : looping for, dengan jumlah perulangan sebanyak n

=> a=random.uniform(0.0,0.5) variabel a berisikan random angka dari 0.0 sampai 0.5

=>print ("data ke : ", i, "=> ", a) print data ke : i = index looping a = angka random sesuai syarat nomer 4

=>print("Selesai") print Selesai di luar looping

=>Tampilkan hasil kelayar

2).Berikut kode lengkapnya :

print('|-----------------------------------------------|')

print('|PROGRAM MENAMPILKAN N BILANGAN ACAK LEBIH < 0.5|')

print('|-----------------------------------------------|')

print('')


import random

n = int(input("Masukan nilai N : "))

for i in range(n) :

    a=random.uniform(0.0,0.5)

    print ("Data ke : ", i, "=> ", a)

print("Selesai")

3).Berikut scrennshotnya:

![alt text](https://github.com/Viktorsianturi/labpy3/blob/a8de04b4cc847d9c43a7d0160a90d7be1f479141/latihan1/Screenshot%20(45).png)

4).Berikut flowchartnyya

![alt text](https://github.com/Viktorsianturi/labpy3/blob/a8de04b4cc847d9c43a7d0160a90d7be1f479141/latihan1/Flowlat1.png)

Latihan 2 (Program menampilkan bilangan terbesar)

1).Alur Algoritmanya :

=> a=1 //variable a diisi 1, agar bisa masuk ke syarat while max=0 //variable max diisi 0

=> while a!=0 : looping while dengan syarat a bukan 0

=> if x > max : max = a proses if untuk mencari nilai terbesar

=> a = int(input("Masukan bilangan : ")) input nilai a dengan tipe data integer

=> if a == 0 : break jika inputan a diisi angka 0 maka break alias berhenti looping

=> print("Bilangan terbesar adalah : ",max) print nilai terbesar, variabel max

2).Berikut kode lengkapnya:

print ('|-------------------------------------|')

print ('|PROGRAM MENAMPILKAN BILANGAN TERBESAR|')


print ('|-------------------------------------|')

print ('')

a=1

max=0

while a!=0:

    if a>max:

        max=a

    a=int(input('Masukkan bilangan :'))

    if a==0:

         break

3).Berikut Flowchatnya:
![alt text](https://github.com/Viktorsianturi/labpy3/blob/master/latihan2/flowchart%202.png)

4).Berikut screenshotnya:
![alt text](https://github.com/Viktorsianturi/labpy3/blob/master/latihan2/Screenshot%20(46).png)

Latihan 3 (Program menghitung laba pengusaha)

1).Alur Agoritmanya :

=> x=100000000 modal 100,000,000, variable x

=> sum=0 variable untuk menjumlah total laba

=> y=0 variable untuk masa bulan

=> lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 

*variable untuk jumlah laba perbulan, 

 dipisahkan dengan koma, tipe data integer

=> for i in lb : looping for indexs i, dengan mengambil data dari lb

=> sum=sum+i rumus untuk menghitung total laba perbulan

=> y+=1 masa bulan, tiap looping menambah 1

=> print("laba bulan ke-", y ,"sebesar :", i ) print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb

=> print("Total laba adalah :", sum) print total laba

=>Tampilkan hasil kelayar 

print ('Nilai terbesarya adalah :',max)


2).Berikut kode lengkapnya :

x=100000000

sum=0

y=0

lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]

print('Modal awal seorang pengusaha        :',x)

for i in lb :

    sum=sum+i

    y+=1

    print('Laba bulan ke-', y ,'sebesar            :', i)


print('Total laba yang didapat adalah      :', sum)


3).Berikut Flowchatnya:

![alt text](https://github.com/Viktorsianturi/labpy3/blob/8dae16ba24ff7db00b8cdafae954ce37aa2f726a/latihan3/flowchat3.png)

4).Berikut Screenshot hasilnya:
![alt text](https://github.com/Viktorsianturi/labpy3/blob/8dae16ba24ff7db00b8cdafae954ce37aa2f726a/latihan3/Screenshot%20(47).png)





