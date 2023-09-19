# Hesap-Makinesi-2
"""Basit Hesap Makinesi
"""Basit Hesap Makinesi
Bu proje, basit matematiksel işlemleri gerçekleştiren bir hesap makinesidir.
Kullanıcılar, toplama, çıkarma, çarpma, bölme ve diğer matematiksel işlemleri yapabilirler.
Bu proje, Python'da temel operatörlerin nasıl kullanılacağını ve kullanıcı girdilerinin nasıl alınacağını gösterir.
"""
import sys

#İşlemi seçtikten sonra sayıları giriyoruz
print("""
         işlem 1 = Toplama
         İşlem 2 = Çıkarma
         İşlem 3 = Çarpma
         İşlem 4 = Bölme
         İşlem 5 = Programdan çıkış yapılıyor""")

while True:
      işlem=int(input("1/2/3/4/5 işlemlerinden birisini giriniz..."))
      if işlem == 1:
          sayi1 = int(input("1.sayiyi gir:"))
          sayi2 = int(input("2.sayiyi gir:"))
          sonuc = sayi1 + sayi2
          print("Toplama sonucu=", sonuc)
      elif işlem == 2:
          sayi1 = int(input("1.sayiyi gir:"))
          sayi2 = int(input("2.sayiyi gir:"))
          sonuc = sayi1 - sayi2
          print("Çıkarma sonucu=", sonuc)
      elif işlem == 3:
          sayi1 = int(input("1.sayiyi gir:"))
          sayi2 = int(input("2.sayiyi gir:"))
          sonuc = sayi1 * sayi2
          print("Çarpma sonucu=", sonuc)
      elif işlem == 4:
          sayi1 = int(input("1.sayiyi gir:"))
          sayi2 = int(input("2.sayiyi gir:"))
          sonuc = sayi1 / sayi2
          print("Bölme sonucu=", sonuc)
      elif işlem == 5:
          print("Programdan çıkış yapılıyor...")
          break
      else:
          print("Geçersiz işlem !!!, tekrar işlem giriniz")
