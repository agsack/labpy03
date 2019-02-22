#labpy03

## LATIHAN1 ###
## Program Menampilkan N Bilangan Acak Yang Lebih Kecil Dari 0.5 ###


## -- Algoritmanya ###

1. import random memanggil file random.
2. n = int(input("Masukan nilai N : ")) input variabel n, tipe data integer.
3. for c in range(n) : looping for index c dengan jumlah perulangan sebanyak n.
4. b = random.uniform(.0,.5) variabel a berisikan random angka dari 0.0 sampai 0.5.
5. print ("Data ke : ",a,"==>",b) print data ke : a = index looping b = angka random sesuai syarat nomor 4.
6. print("-----FINISH-----") print Selesai di luar looping.
7. Run program latihan1.

## - Flowchart ###

flowchart latihan1

<img width="187" alt="fc3" src="https://user-images.githubusercontent.com/46734315/53229204-386b1380-36b6-11e9-87c1-87f8bfd1b42f.png">

## - Screenshot ###
screenshot syntax & hasil program latihan1

![2 - copy](https://user-images.githubusercontent.com/46734315/53229351-8a139e00-36b6-11e9-808a-5237ab90b64c.png)

1. Ketikan Program print ("Bilangan Acak yang Lebih Kecil Dari 0.5")

  =>print ('Bilangan Acak yang Lebih Kecil Dari 0.5') Untuk Menampilkan atau Mencetak kalimat *Bilangan Acak
  yang Lebih Kecil Dari 0.5

2. Ketikan Program import random

  => import random memanggil file random.
  
3. ketikan program n = int(input("Masukan nilai N : "))

  => n = int(input("Masukan nilai N : ")) input variabel n, tipe data integer.

4. Ketikan Program a=0

5. ketikan program for c in range(n) :

  => for c in range(n) : looping for index c dengan jumlah perulangan sebanyak n.

6. ketikan program a+=1

  => a+=1, setiap looping nilai akan bertambah 1
  
7. ketikan program b = random.uniform(.0,.5

  = >  b = random.uniform(.0,.5) variabel a berisikan random angka dari 0.0 sampai 0.5.
  
8. ketikan program print ("Data ke : ",a,"==>",b)

  => print ("Data ke : ",a,"==>",b) print data ke : a = index looping b = angka random sesuai syarat nomor 4.

9. ketikan program print("-----FINISH-----")


#3 - Hasilnya ###
![2](https://user-images.githubusercontent.com/46734315/53229390-a44d7c00-36b6-11e9-9e5f-3138949ad31d.png)



## LATIHAN2 ###
## Program Menentukan Bilangan Terbesar ###

## - Algoritma ###

1. max=0 variable max diisi 0.
2. while True: looping while dengan syarat True.
3. if max < a: max = a proses if untuk mencari nilai terbesar.
4. a = int(input('Masukan bilangan = ')) input nilai a dengan tipe data integer.
5. if a==0 : break jika inputan a diisi angka 0 maka break alias berhenti looping.
6. print('Bilangan terbesarnya adalah = ',max) print nilai terbesar, variabel max.
7. Run program latihan2.

## - Flowchart ###

flowchart latihan2

![fc1](https://user-images.githubusercontent.com/46734315/53190575-7c213700-363c-11e9-9cf6-d5f6eb59185f.png)

## - Screenshot ###

screenshot syntax & hasil program latihan2

![3 - 
copy](https://user-images.githubusercontent.com/46734315/53190669-a5da5e00-363c-11e9-8df0-6e1c0f8590f9.png)

1. Ketikan Program print ('***** Menentukan Bilangan Terbesar *****')

  =>print ('Menampilkan Bilangan Terbesar Dari N Buah Data Yang Diinputkan') Untuk menampilkan kalimat Menampilkan Bilangan Terbesar
  Dari N Buah Data Yang Diinputkan

2. Ketikan Program max= 0

  =>max= 0 kode max disini untuk menentukan nilai max nya dalah 0

3. Ketikan Program while true:

  =>while true: Untuk perulangan hingga waktu yang tidak di tentukan atau selamanya

4. Ketikan Program a=int(input("Masukan Bilangan :"))

  =>a=int(input("Masukan Bilangan :")) a untuk menginput tipe data interger ( bilangan bulat )

5. Ketikan Program if max < a

6. Ketikan Program max=a

  =>if max < a max=a jika max kurang dari a maka max = a

7. Ketikan Program if a==0:

8. Ketikan Program break

  =>if a==0: break jika a= 0 maka akan berhenti dengan syarat break yang terpenuhi

9. Ketikan Program print("Bilangan Tebesarnya Adalah :", max)

  =>print("Bilangan Tebesarnya Adalah :", max) Menampilkan *Bilangan Tebesar Adalah : Nilai maxiumnya


## - Hasilnya ###
![3](https://user-images.githubusercontent.com/46734315/53190680-a8d54e80-363c-11e9-9867-75cb3ca5aa7f.png)


## PROGRAM1 ###
## Program Sederhana Pengulangan Dengan Menghitung Laba Pengusaha ###

## - Algoritma ###
1. x=100000000 modal 100.000.000, variable x.
2. sum=0 variable untuk menjumlah total laba.
3. y=0 variable untuk masa bulan.
4. lb = [int(0), int(0), int(a) * .1, int(a) * .1, int(a) * .5, int(a) * .5, int(a) * .5, int(a) * .2] variable untuk jumlah laba perbulan, dipisahkan dengan koma dan tipe data integer.
5. for i in lb : looping for index i dengan mengambil data dari lb.
6. sum=sum+i rumus untuk menghitung total laba perbulan.
7. y+=1 masa bulan, tiap looping menambah 1.
8. print('Laba Bulan Ke-', y ,'Sebesar :',y) print : y = ambil masa bulan, i = ambil dari data yang ada di dalam lb.
9. print('TOTAL LABA YANG DI DAPAT ADALAH :',sum) print total laba.
10. Run Program1.

## - Flowchart ###

flowchart program1

![fc2](https://user-images.githubusercontent.com/46734315/53190839-08cbf500-363d-11e9-8384-d2b46430c8d6.png)

## - Screenshot ###

screenshot hasil & syntax program1

![4 - 
copy](https://user-images.githubusercontent.com/46734315/53190795-ed60ea00-363c-11e9-934f-2cd82662b1fd.png)

1. Ketikan program

  => x=100000000 modal 100.000.000, variable x.

2. Ketikan program sum=0

  => sum=0 kode sum disini untuk menentukan jumlah total laba

3. ketikan program

  => y=0 y= untuk variable masa bulan
 ![4 - 
copy](https://user-images.githubusercontent.com/46734315/53190795-ed60ea00-363c-11e9-934f-2cd82662b1fd.png) 
4. ketikan program lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x)* .5, int(x) * .2]

  => lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x)* .5, int(x) * .2]  Untuk Mendeklarasikan
  presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000

5. ketikan program print(" Modal Awal Seorang Pengusaha :',x")

  => print(" Modal Awal Seorang Pengusaha :',x") Menampilkan kalimat *Modal Awal : dan data yang berisi di x yaitu 100000000
  
6. ketikan program for i in lb :

  => for i in lb : looping for index i dengan mengambil data dari lb.
  
7. ketikan program  sum=sum+i

   sum=sum+i rumus untuk menghitung total laba perbulan.
   
8. ketikan program y+1

  =>  y+=1, masa bulan tiap looping menambah 1.
  
9. print('Laba Bulan Ke-', y ,'Sebesar :',i)

  => print('Laba Bulan Ke-', y ,'Sebesar :',i) print : y = ambil masa bulan, i = ambil dari data yang ada di dalam lb.
  
10. print('TOTAL LABA YANG DI DAPAT ADALAH :',sum)

  => print('TOTAL LABA YANG DI DAPAT ADALAH :',sum) print total laba.


## - Hasilnya ###
![4](https://user-images.githubusercontent.com/46734315/53190790-e9cd6300-363c-11e9-9aa5-1d25e57829de.png)

## Sekian Dan Terima Kasih ###

## AGUS SAPUTRA ###
## TI 18 B1 ###
## 311810946 ###
