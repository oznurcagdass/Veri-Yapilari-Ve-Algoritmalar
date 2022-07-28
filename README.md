# Veri-Yapilari-Ve-Algoritmalar
Insertion Sort Project 




# Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamaları yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin ilk dört adımını yazınız..


# Insertion Sort Aşamaları

1. Öncelikle dizimizin ilk iki elemanını karsılaştırıyoruz.22 ve 27 sayıları, sıralı durumda. Daha sonra üçüncü elemanımız olan 16 ya bakıyoruz. 272den küçük olan 16 yer değiştirmeli diyoruz ve dizimiz şu hali alıyor 
[22,16,27,2,18,6] aynı kuralları tekrar tekrar uyguluyoruz.

[22,27,16,2,18,6]
[22,16,27,2,18,6]
[16,22,27,2,18,6] (ilk aşama bitti) sıra 2 de 
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,18,27,6]  18 ile devam ediyoruz
[2,16,18,22,27,6]  
[2,16,18,22,6,27]  6 yı işleme aldık...
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]  ve son.

# Big-O Gösterimi

2. sorumuzun cevabı:  "n+(n-1)+(n-2)+...+1 = n(n+1)/2 --> O(n^2)"


# Time Complexity

3. sorumuzun cevabını bulmak için "Dizimizi sıraladığımızda -aradığımız- 18 sayısının dizideki konumuna bakıyoruz."
4. sorunun cevabı ise sıralanmış halinde ( [2,6,16,18,22,27] ) 18 tam ortada olduğu için Avarage Case olur.


# [7,3,5,8,2,9,4,15,6] İlk Dört Adımı

[2|,3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|,8,7,9,5,15,6]

[2,3,4,5|,7,9,8,15,6]


[Patika.dev](https://www.patika.dev/tr) 