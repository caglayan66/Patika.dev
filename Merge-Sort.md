#Merge Sort Ödevi
[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

Diziyi bölerek sıralama yapıyoruz ve sonra birleştiriyoruz.

[16,21,11] v [8,12,22]
[16,21] v [11] v [8,12] v [22]
[16] v [21] v [11] v [8] v [12] v [22] --> diziyi böldük. Birleştirmeye başlayalım. Birleştiriken sıralıyoruz.
[16,21] v [11] v [8,12] v[22]  
[11,16,21] v [8,12,22]
[8,11,12,16,21,22]

## Big-O gösterimi

bu işlem dizi sayısı n ise her seferinde yarıya inerek işlem yapılıyor. 2^x = n x buradan x = logn n kere bu işlemi tekrar ediyoruz. Sonuç O(nlogn)

