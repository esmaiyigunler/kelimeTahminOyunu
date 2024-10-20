import random

kelimeler=["kulaklık","telefon","laptop","klavye","mouse","yazıcı","ekran"]

#rastgele kelime seç
gizliKelime=random.choice(kelimeler)
print("gizli kelime belirlendi")

tahminHakki=5
tahminler=[]
print("gizli kelimeyi tahmin et")
print(f"{tahminHakki} tahmin hakkınız var")

while tahminHakki>0:
    tahmin=input("Tahmininizi girin:").lower() #kullanıcıdan tahmin al

    if tahmin in tahminler:
        print("Bu tahmini zaten yaptınız. Lütfen başka bir tahmin girin")
        continue
    tahminler.append(tahmin) #tahminleri kaydet

    if tahmin==gizliKelime:
        print("Tebrikler.Gizli kelimeyi doğru tahmin ettiniz.")
        break #doğru tahmin yapılınca döngüden çık
    tahminHakki-=1 #tahmin hakkını azalt

    if tahminHakki>0:
        print(f"Yanlış tahmin. Kalan tahmin hakkınız:{tahminHakki}")

    else:
        print(f"Üzgünüm tahmin hakkınız kalmadı. Gizli kelime:{gizliKelime}")
        
