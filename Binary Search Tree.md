# Veri-Yapilari-Ve-Algoritmalar

# Binary Search Tree

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

**Örneğin :** Root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Binary Search Tree Aşamaları

[7,5,1,8,3,6,0,9,4,2]

"Öncelikle rootumuzu belirliyoruz. Burada root'u 7 seçelim. Sıradaki eleman 5. 5, 7'den küçüktür ve kural gereği solunda yer alır. "

1. 5<7 old 5 solda

      7
     /
    5

2. 1<7 old 1 solda

       7
      / 
     5   
    / 
   1



3. 7<8 old 8 sağda

       7
      / \
     5   8
    /
   1
    

4. 3<7 old. 3 solda ve 0<7 old. 0 da solda

       7
      / \
     5   8
    /
   1
  / \
 0   3  



5. 6<7 old. 6 solda

           7
          / \
         5   8
        / \
       1   6
      / \
     0   3


6. 7<9 old 9 sağda   

           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3


7. 4<7 old 4 solda

           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3
          \
           4


8.  2<7 old 2 solda
           7
          / \
         5   8
        / \   \
       1   6   9
      / \
     0   3
        / \
       2   4
 
 "olarak tamamlanır."