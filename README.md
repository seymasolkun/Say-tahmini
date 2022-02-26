# Sayı-tahmini
gizli_sayı="45"
tahmin=""
tahmin_sayısı=0
tahmin_cıkıs=False
    
while tahmin_sayısı<4 and not(tahmin_cıkıs):
    tahmin=input("tahmin giriniz:")
    if tahmin<gizli_sayı:
         print("Tahminden uzaklaştın... Tahminini yükselt")
    elif tahmin>gizli_sayı:
         print ("Tahminden uzaklaştın... Tahminini düşür")  
    elif tahmin==gizli_sayı:
         print("Tebrikler... Doğru tahmin.")
         tahmin_is_bool = True 
    tahmin_sayısı +=1
