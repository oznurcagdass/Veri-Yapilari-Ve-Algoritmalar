# Veri Yapıları Ve Algoritmalar

# Merge Sort Projesi 

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


# Merge Sort Aşamaları
1. sorunun cevabı ;
[16,21,11,8,12,22] Dizisini her adımda parçalayıp en son tekli halde kalıncaya kadar devam edilir.
[16,21,11]-[8,12,22]
[16]-[21,11]-[8]-[12,22]
[16]-[21]-[11]-[8]-[12]-[22]
Şimdi sıralıyoruz..
[8,11,12,16,21,22]

"Sıralama Tamamlandı"


# Big-O Gösterimi
2. sorunun cevabı ;
Her adımdaa n tane işlem yaptık. 2^x = n --> O(logn) 


[Patika.dev](https://www.patika.dev/tr)