#range birer birer arttırarak 0'dan itibaren yazmaya başlar
for sayilar in range(10):
    print(sayilar)

for sayilar2 in range(5,10):
    print(sayilar2)

for sayilar3 in range(5,15,2):
    print(sayilar3)

for sayilar4 in range(20,5,-3):
    print(sayilar4)
else:
    print("DÖNGÜ BİTTİ")

#a)0-20 arası çift sayıları for döngüsü ile ekrana yazdırınız.
#b)1-30 arası tek sayıları for döngüsü ile ekrana yazdırınız.
#c)3'ten başlayarak 41'e kadar olan sayıları 5'er arttırarak for döngüsü ile ekrana yazdırınız
#d)50'den 20'ye kadar olan sayıları 3'er azaltarak for döngüsü ile ekrana yazdırınız.

#a)
for sayilar in range(0,20,2):
    print(sayilar)

#b)
for sayilar2 in range(1,30,2):
    print(sayilar2)

#c)
for sayilar3 in range(3,41,5):
    print(sayilar3)

#d)
for sayilar4 in range(50,20,-3):
    print(sayilar4)

#1-10 kadar(10 dahil) olan sayıların toplamını for döngüsü ile yazdırınız.
toplam=0
for sayilar5 in range(11):
 toplam=toplam+sayilar5
print("SAYILARIN TOPLAMI=",toplam)

#a)Girilen iki sayı arasındaki sayıların toplamını bularak ekrana yazdırınız.
#b)Girilen iki sayının arasındaki sayıların ortalamasını bularak ekrana yazdırınız.
#c)Girilen sayının faktöriyelerini bularak ekrana yazdırınız.
#d)ELemanları sırasıyla 4,12,18,33 olan sayılar ile sayilar isminde bir liste oluşturunuz.
#listenin elemanlarıı for döngüsü kullanarak toplayınız ve ekrana yazdırınız.
#a)
sayi1=int(input("İLK SAYIYI GİRİNİZ:"))
sayi2=int(input("İKİNCİ SAYIYI GİRİNİZ:"))
for sayilar6 in range(sayi1+sayi2):
   toplam=toplam+sayilar6
   print(toplam)
print("SAYILARIN TOPLAMI=",toplam)
#b)
toplam=0
ortalama=0
sayi3=int(input("İLK SAYIYI GİRİNİZ:"))
sayi4=int(input("İKİNCİ SAYIYI GİRİNİZ:"))
for sayilar7 in range(sayi3+sayi4):
   toplam=sayi3+sayi4
   print(toplam)
   ortalama=toplam/(sayi3-sayi4)
print("ortalama")

#d)
toplaListe=[4,12,18,33]


