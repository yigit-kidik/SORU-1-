sayilar = []
for i in range (1,11):
    sayi = int(input("Sayı Giriniz:"))
    sayilar.append(sayi)
print(sayilar)
toplam=sum(sayilar)
adet=len(sayilar)
aritmekort = toplam/adet
print(aritmekort)
