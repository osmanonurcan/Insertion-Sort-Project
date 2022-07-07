# INSERTION-SORT-PROJECT
Patika Veri Yapıları ve Algoritmalar Insertion Sort Projesi
<br/>
Patika Dev Profile: https://app.patika.dev/osmanonurcan

## PROJECT 1 
[22,27,16,2,18,6] -> Insertion Sort

  1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  3. Time Complexity: 
      -Average case: Aradığımız sayının ortada olması,
      -Worst case: Aradığımız sayının sonda olması, 
      -Best case: Aradığımız sayının dizinin en başında olması.
  4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


#### 1. INSERTION SORT ####

İlk indeksten yani 22 sayısından aramaya başlarız. Dizinin en küçük sayısını bulduktan sonra 22 sayısı ile en küçük sayıyı yer değiştiririz. Sonra bir sonraki indekse geçip dizi sıralanana kadar aynı işlemleri tekrarlarız.


- [22, 27, 16, 2, 18, 6] 
- [22, 27, 16, 2, 18, 6]
- [16, 22, 27, 2, 18, 6] 
- [2, 16, 22, 27, 18, 6] 
- [2, 16, 18, 22, 27, 6] 
- [2, 6, 16, 18, 22, 27]

#### 2. BIG-O ####

    Best case    : O(n)
    Average case : O(n^2)
    Worst case   : O(n^2)


#### 3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. ####

    Average case. Çünkü dizi sıralandıktan sonra 18 sayısı ortada kalıyor.

