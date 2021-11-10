```
Nama    : Muhammad Rafi Al Ghifari
Nim     : 312110526
Kelas   : TI.21.BA.1
```

# labpy03
# Latihan1
![latihan1](https://user-images.githubusercontent.com/46749500/53287677-ee1b8c80-37b2-11e9-94ed-3cae74178a40.png)

# Codingan
```
print(' ')
import random
N = int(input("Masukan nilai N : "))
a = 0
for x in range(N):
    a += 1
    b = random.uniform(.0,.5)
    print('Data ke:',a,'==>',b)
print('Selesai')
print(' ')
jawab = 'lanjutkan'
hitung = 0
while jawab == "lanjutkan":
    hitung += 1
    jawab = input('Ingin Mengulang ? (yes/no) : ')
    if jawab == "Lanjutkan":
        break
print('Total perulangan : ' + str (hitung))
```

# Hasil codingan
![hasil codingan](https://user-images.githubusercontent.com/46749500/53287636-a9dbbc80-37b1-11e9-8043-13169152b9dd.png)

# Latihan2
![latihan2](https://user-images.githubusercontent.com/46749500/53287784-d4c71000-37b3-11e9-9296-4b5b9b2ca9bf.png)

# Codingan
```
print("\n")
max=0
while True:
    a=int(input("Masukan Bilangan :"))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar = ", max)
input("\n")
```
# Hasil Codingan
![hasilcoding2](https://user-images.githubusercontent.com/46749500/53288065-d514da80-37b6-11e9-9627-613c44a72965.png)

# Latihan3
![program 1](https://user-images.githubusercontent.com/46749500/53288204-7a7c7e00-37b8-11e9-8730-80df3981e44e.png)

```
print("Menhitung laba perusahaan dengan modal Rp. 100.000.000")
print("")
print('note')
print('Bulan pertama dan ke 2 = 0%')
print('pada bulan ke 3 = 1%')
print('pada bulan ke 5 = 5%')
print('pada bulan ke 8 = 8%')
print("")
a=100000000
for x in range(0,9):
        if(x>0 and x<=2):
                b=a*0
                print("laba bulan ke-",x," :",b)
        if(x>=3 and x<=4):
                c=a*0.1
                print("laba bulan ke-",x," :",c)
        if(x>=5 and x<=7):
                d=a*0.5
                print("laba bulan ke-",x," :",d)
        if(x==8):
                e=a*0.2
                print("laba bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)
input("\n")
```

# Hasil Codingan
![hasil codingan](https://user-images.githubusercontent.com/46749500/53288263-fbd41080-37b8-11e9-95f3-461481ab5974.png)

# Sekian & Terimakasih
