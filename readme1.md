## [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
.......
//Merge Sort yönteminde dizi tek eleman kalacak şekilde sürekli iki bölünür.

1-> [16,21,11] - [8,12,22]

2-> [16] - [21,11] -- [8] - [12,22]

3-> [16] - [21] - [11] -- [8] - [12] - [22] //aynı sırayla artık birleştirilir ve sıralanır.

4-> [16] - [11,21] -- [8] - [12,22] 

5-> [11,16,21] -- [8,12,22] // birleştirilken sıralanıyor.

6-> [8,11,12,16,21,22]

Time Complexity:
-Her seferinde ikiye bölerek işlem yaptığımız için 2^x = n yani logn=x diyebiliriz.
-Bütün işlemler düşünüldüğünde Big-O gösterimi=O(nlogn)


