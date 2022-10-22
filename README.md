# Data-Structures-and-Algorithms

## Proje 1

### [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız

### Çözüm

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.\
**1.** ``[22, 27, 16, 2, 18, 6]``\
**2.** ``[2, 27, 16, 22, 18, 6]``\
**3.** ``[2, 6, 16, 22, 18, 27]``\
**4.** ``[2, 6, 16, 18, 22, 27]``

- Big-O gösterimini yazınız.\
**1.** Her seferinde dizede bir eleman azalacağı için n, (n-1), (n-2), ... ,1 şeklinde işlem sayıları oluşur. Bu da 1'den n'e kadar olan sayıların toplamını verir.\
``(n.(n+1))/2=(n^2+n)/2``\
**2.** n^2 baskın olacağı için Big O Notation O(n^2) olur.

- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.\
**1.** Average Case:\
``O(n^2)``\
**2.** Best Case:\
``O(n)``\
**3.** Worst Case:\
``O(n^2)``


- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.\
**1.** 18 dizinin ortalarında kaldığı için ***Average Case*** kapsamına girer.

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.\
**1.** ``[2, 3, 5, 8, 7, 9, 4, 15, 6]``\
**2.** ``[2, 3, 5, 8, 7, 9, 4, 15, 6]``\
**3.** ``[2, 3, 4, 8, 7, 9, 5, 15, 6]``\
**4.** ``[2, 3, 4, 5, 7, 9, 8, 15, 6]``

## Proje 2
### [16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

### Çözüm

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.\
**1.** ``[16, 21, 11]   [8, 12, 22]``\
**2.** ``[16, 21]   [11]   [8, 12]   [22]``\
**3.** ``[16]   [21]   [11]   [8]   [12]   [22]``\
**3.** ``[16, 21]   [11]   [8, 12]   [22]``\
**4.** ``[11, 16, 21]   [8, 12, 22]``\
**5.** ``[8, 11, 12, 16, 21, 22]``

- Big-O gösterimini yazınız.\
**1.** Her adım sırasında işlem sayısı yarıya inerek devam ettiği için time complexity ***adım sayısı * işlem sayısı*** olur.\
`` İşlem Sayısı = logn``\
`` Adım Sayısı = n``\
``O(nlogn)``

## Proje 3
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Çözüm

**1.**\
  ``   7``\
``   /\``\
``  5  8``\
`` /\   \``\
``1  6   9``\
``/\ ``\
``0 3 ``\
``  /\ ``\
`` 2  4  ``


[Patika.dev](https://app.patika.dev/)
 
