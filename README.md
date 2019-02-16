# labpy3
A.) Latihan 1 py ALGORITMA ALUR

    a. import random
    b. n = int(input("Masukan nilai N : "))
Untuk menginputkan bilangan yang di inginkan
   
    c. for i in range(n) :
Rumus menghitung perulangan sebanyak nilai N

    d. a=random.uniform(0.0,0.5)
untuk menampilkan jumalah bilangan terkecil dari 0.0 sampai 0.5 nilai yang di inputkan

    e. print ("Data ke : ", i, "=> ", a)
untuk menamnpilkan hasil

    f. print("Selesai")
untuk menampilkan hasil teks selesai

CODINGAN LATIHAN1PY

    import random
    n = int(input("Masukan nilai N : "))
    for i in range(n) :
    a=random.uniform(0.0,0.5)
    print ("Data ke : ", i, "=> ", a)
    
    print("Selesai")
    
![img](https://github.com/Khoiriladinata/labpy3/blob/master/latihan1py.PNG)


B).Latihan 2 py ALGORITMA ALUR

    a=1
    max=0
1. agar bisa masuk ke syarat while max=0 //variable max diisi 0

        while a!=0:
2. looping while dengan syarat a bukan 0

        if a>max:
        max=a
3. proses if untuk mencari nilai terbesar

        a=int(input('Masukkan bilangan :'))
4. input nilai a dengan tipe data integer

        if a==0:
        break
5. jika inputan a diisi angka 0 maka break alias berhenti looping

        print ('Nilai terbesarya adalah :',max)
        print nilai terbesar, variabel max


CODINGAN LATIHAN 2 py

    a=1
    max=0
    while a!=0:
     if a>max:
        max=a
    a=int(input('Masukkan bilangan :'))
    if a==0:
         break
        
    print ('Nilai terbesarya adalah :',max)


![img](https://github.com/Khoiriladinata/labpy3/blob/master/latihan2py.PNG)



C).Program 1 py ALGORITMA ALUR

    x=100000000 modal 100,000,000, 
1. variable x

        sum=0 
2. variable untuk menjumlah total laba

        y=0 
3. variable untuk masa bulan

        lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 
4. variable untuk jumlah laba perbulan,dipisahkan dengan koma, tipe data integer
         
         for i in lb : 
5. looping for indexs i, dengan mengambil data dari lb

        sum=sum+i 
6. rumus untuk menghitung total laba perbulan

        y+=1 
7. masa bulan, tiap looping menambah 1

        print("laba bulan ke-", y ,"sebesar :", i ) 
8. print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb

        print("Total laba adalah :", sum) 
9. print total laba Tampilkan hasil kelayar 

CODINGAN PROGRAM 1 py

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


![img](https://github.com/Khoiriladinata/labpy3/blob/master/praktikum3.PNG)
