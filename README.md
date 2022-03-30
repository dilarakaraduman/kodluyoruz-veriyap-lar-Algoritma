# kodluyoruz-veriyap-lar-Algoritma

# Proje 1

**[22,27,16,2,18,6] -> Insertion Sort**
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1. [22,27,16,2,18,6] --ilk hali--
2. [2,27,16,22,18,6] --en küçük 1.sayı--
3. [2,6,16,22,18,27] --en küçük 2.sayı--
4. [2,6,16,22,18,27] --en küçük 3.sayı--
5. [2,6,16,18,22,27] --en küçük 4.sayı--
5. [2,6,16,18,22,27] --en küçük 5.sayı--(Tamamen kontrolden geçirilmiş ve sıralanmış dizi elde edilmiştir.)
```

2. Big-O gösterimini yazınız.
```O(n^2)```
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
``Worst case-->O(n^2)``
``Average case-->O(n^2)``
``Best case-->O(n)``

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 
``Average case``
5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. 
```1. [7,3,5,8,2,9,4,15,6] --ilk hali--
  2. [2,3,5,8,7,9,4,15,6] --en küçük 1.sayı--
  3. [2,3,4,8,7,9,5,15,6] --en küçük 2.sayı--
  4. [2,3,4,5,7,9,8,15,6] --en küçük 3.sayı--
  5. [2,3,4,5,6,9,8,15,7] --en küçük 4.sayı--
```

# Project 3
## Binary Search Tree Projesi
1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
                      5
                   /     \
                  2       7
                 / \     / \
                1   3   6   8
               /     \       \
              0       4       9


# Project 2
## Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort
1. [16,21,11,8,12,22] -> Merge Sort
```
1. [16,21,11,8,12,22]
2. [16,21,11] [8,12,22]
3. [16,21][11] [8,12][22]
4. [16][21][11] [8][12][22]
5. [16,21][11] [8,12][22]
6. [11,16,21] [8,12,22]
7. [8.11,12,16,21,22]
```

2. Big-O gösterimini yazınız.
```
O(n*logn)```
