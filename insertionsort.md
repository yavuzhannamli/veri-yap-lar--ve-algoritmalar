Proje 1 1)[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2)Big-O gösterimini yazınız.

3)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması.

4)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Insertion Sort

En küçük eleman bulunur ve sayı dizisi 1 azalarak son sayı kalana kadar tek tek bakılır.
[22,27,16,2,18,6] n [2,27,16,22,18,6] n-1 [2,6,16,22,18,27] n-2 [2,6,16,18,22,27] n-3

Big-O gösterimi: n+(n-1)+(n-2)...+1= n(n+1)/2= Baskın ifade n² --> O(n²)

[2,6,16,18,22,27] dizinin son hali bu şekilde olduğu için 18 sayısı ortada yer alır. Bu durumda 18 sayısı average case senaryosuna girer.

[7,3,5,8,2,9,4,15,6]

2,3,5,8,7,9,4,15,6 --> 1. adım: soldan 1. sıraya dizindeki en küçük sayı 2 yazıldı. 2,3,4,8,7,9,5,15,6 --> 2. adım: 2 ve 3'ten sonra en küçük sayı 4 olduğu için 5 ile yer değiştirildi. 2,3,4,5,7,9,8,15,6 --> 3. adım: 2,3,4'ten sorna en küçük sayı 5 olduğu içim 8 ile yer değiştirildi. 2,3,4,5,6,9,8,15,7 --> 4. adım: 2,3,4,5'ten sonra en küçük 6 olduğu için 7 ile yer değiştirildi. 2,3,4,5,6,7,8,15,9 2,3,4,5,6,7,8,9,15

