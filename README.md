```
Nama    : Muhammad Rafi Al Ghifari
Nim     : 312110526
Kelas   : TI.21.BA.1
```

# labpy03
# Latihan1
<img width="704" alt="LATIHAN1 03" src="https://user-images.githubusercontent.com/93661771/141990866-37f7d688-85b9-47db-99a6-8a499266fadf.PNG">

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
<img width="945" alt="LATIHAN1 HASIL CODINGAN 03" src="https://user-images.githubusercontent.com/93661771/141991158-db2f08e1-85df-4954-9e00-24cda4572a3c.PNG">

# Latihan2
<img width="704" alt="latihan 22" src="https://user-images.githubusercontent.com/93661771/141991276-1e600187-e1fb-4277-a040-87dd0012ef20.PNG">

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
<img width="945" alt="hasil codingan 22" src="https://user-images.githubusercontent.com/93661771/141991386-6d020928-7b38-4c82-a782-80d46ec845e1.PNG">

# Latihan3
<img width="704" alt="latihan 33" src="https://user-images.githubusercontent.com/93661771/141991550-6f351862-b5b1-4021-9e87-920eecc0e125.PNG">

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
<img width="946" alt="hasil codingan 33" src="https://user-images.githubusercontent.com/93661771/141991566-808c094b-0182-440b-b2bb-7ab8ea82faf3.PNG">

# Sekian & Terimakasih
