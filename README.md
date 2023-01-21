# Proje 1
##  Selection Sort Türünden
[22,27,16,2,18,6] -> 
```
[2,27,16,22,18,6] (n)    Dizideki en küçük sayıyı nul ve baştakiyle değiştir
[2,27,16,22,18,6] (n-1)  sayı içinden tekrar en küçük sayıyı bul ikinci sıradaki ile değiştir. (6-27)
[2,6,16,22,18,27] (n-2)  sayı içinden tekrar en küçük sayıyı bul zaten üçüncü sırada. (16)
[2,6,16,18,22,27] (1)    sayı içinden tekrar en küçüğü bul dördüncü sıradaki ile değiştir, sıralama tamamdır (18-22)

```
## Big-O gösterimini yapınız
```
Big-O = (n^2)
```
## Time Complexity: 

Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
```
Average case: Aradığımız sayının ortada olması
```
 ## [7,3,5,8,2,9,4,15,6]
 Dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
 ```
[2 | 3, 5, 8, 7, 9, 4, 15, 6] (n-1) 1.adım
[2, 3, 4 | 8, 7, 9, 5, 15, 6] (n-2) 2.adım
[2, 3, 4, 5 | 7, 9, 8, 15, 6] (n-3) 3.adım
[2, 3, 4, 5, 6 | 9, 8, 15, 7] (n-4) 4.adım
 ```


