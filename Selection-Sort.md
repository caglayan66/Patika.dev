#Selection-Sort Ödevi

[22,27,16,2,18,6] -> Selection-Sort

## Selection-Sort

Dizinin elemanlarını sırayla kontrol edip en küçük elemanı başa yazıyoruz.  Sırasıyla aşağıdaki adımlarla dizimiz değişiyor

* [2,27,16,22,18,6] --> En küçük sayıyı buluyoruz ve başa yazıyoruz. Baştaki sayıyla yerini değiştiriyoruz!
* [2,6,16,22,18,27] --> ilk elemandan sonra kalan n-1 eleman için bu işlemi tekrarlıyoruz.
* [2,6,16,22,18,27] --> 16 sırası doğru
* [2,6,16,18,22,27]
* [2,6,16,18,22,27] --> son adımda dizimiz değişmiyor ve sıralanmış oluyor

## Big-O Gösterimi

lk adımda (n) eleman, ikinci adımda (n-1) eleman, üçüncü adımda (n-2) eleman ile işlem yaparak 1 eleman kalana kadar devam ediyoruz.

Formül--> n+(n-1)+(n-2)+...+1= n(n+1) /2

n^2+n /2 elde ettik. n^2 yi alıyoruz. Sonuç--> O(n^2)

## Time Complexity: 

Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

Dizide 18 sayısı orta ve sona doğru olduğu için avarege case ile worst case arasında olur.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

* [2,3,5,8,7,9,4,15,6]
* [2,3,5,8,7,9,4,15,6] --> 3 yeri doğru
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6] 4. Adım

