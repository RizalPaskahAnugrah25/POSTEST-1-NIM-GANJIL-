```
input("Nama: ")
input("NIM: ")

print("Selamat datang di program konversi nilai tukar mata uang rupiah")
print("Silahkan pilih mata uang yang ingin anda konversikan")
print("1. USD")
print("2. Yen")
print("3. Ringgit Malaysia")

pilihan = int(input("Masukkan pilihan anda (1/2/3): "))

if pilihan ==1:
    def idrtousd(rupiah):
        return(rupiah/15357)
    uangrupiah = int(input("masukkan nominal uangmu dalam rupiah: "))
    uangusd = idrtousd(uangrupiah)
    print("Uang DOLLAR anda sebesar: ""$", uangusd)
elif pilihan == 2:
    def idrtoyen(rupiah):
        return(rupiah/103)
    uangrupiah = int(input("masukkan nominal uang anda dalam rupiah: "))
    uangyen = idrtoyen(uangrupiah)
    print("Uang YEN anda sebesar: " "¥", uangyen)
elif pilihan == 3:
    def idrtoringgit(rupiah):
        return(rupiah/3.273)
    uangrupiah = int(input("masukkan nominal uang anda dalam rupiah: "))
    uangringgit = idrtoringgit(uangrupiah)
    print("Uang RINGGIT anda sebesar: " "RM", uangringgit)
else:
    print("Pilihan yang anda masukkan tidak sesuai, silahkan coba lagi!")
```
![postest1 drawio](https://github.com/RizalPaskahAnugrah25/POSTEST-1-NIM-GANJIL-/assets/144990780/6eb6d452-53cd-47e0-ba3a-9051754c4199)
