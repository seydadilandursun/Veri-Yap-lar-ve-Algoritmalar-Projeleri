# Veri-Yapilari-ve-Algoritmalar-Projeleri
## **Insertion Sort Projesi**
---
Proje 1
**[22,27,16,2,18,6] -> Insertion Sort**

*1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.*
```
   [22,27,16,2,18,6]
   [2,27,16,22,18,6]
   [2,6,16,22,18,27]
   [2,6,16,18,22,27]
```
Not: Ders videosu ve altındaki kaynakçalar anlatım olarak çakışmaktadır.Burada yaptığımız kaynakçalara göre selection sorttur.:)
Kaynaklar : [Ders anlatımı](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje),[Selection Sort](https://www.tutorialspoint.com/data_structures_algorithms/selection_sort_algorithm.htm),[Insertion Sort](https://www.tutorialspoint.com/data_structures_algorithms/insertion_sort_algorithm.htm)
*2. Big-O gösterimini yazınız.*
```
Genel Big-O Notation : O(n²)
```
*3. Time Complexity*
```
Selection Sort için:
   Average case: Aradığımız sayının ortada olması : O(n²)
   Worst case: Aradığımız sayının sonda olması:O(n²)
   Best case: Aradığımız sayının dizinin en başında olması.: O(n²)
[Kaynakça](https://www.programiz.com/dsa/selection-sort)
Insertion Sort için:
   Average case: Aradığımız sayının ortada olması : O(n²)
   Worst case: Aradığımız sayının sonda olması:O(n²)
   Best case: Aradığımız sayının dizinin en başında olması.: O(n)
[Kaynakça](https://www.programiz.com/dsa/insertion-sort) 
```
*4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*
```
18 ortada kalacağı için  Average case kapsamına girer. 
```
*5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.*
```
Selection Sort (Videoya göre insertion sort); 
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6] (Aynı kalıyor)
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7] ...
Insertion Sort ( Başka kaynaklara ve videodaki kaynaklara göre*);
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6] Aynı kalıyor
[2,3,5,7,8,9,4,15,6] "...
```






