## [22,27,16,2,18,6] 

## 1.Adım: Insersition sort algortması en baştan başlayarak elemanları kıyaslayarak en küçük olanı bulduğunda başa yazarak ilerler.
[22,27,16,2,18,6] (n) 
[2,27,16,22,18,6] (n-1) ->2
[2,6,16,22,18,27] (n-2) ->27
[2,6,16,18,22,27]  (n-3) ->18
[2,6,16,18,22,27]  1

## 2.Adım : n*(n+1)/2 => Big-O  O(n^2)
## 3.Adım : 
- Worst Case: Tam tersi sıralanmış dizi,buna göre dizi de her eleman bir öncekinden küçük olmalı,geriye doğru hareket yapacağından O(n^2)
- Best Case : Tam sıralı dizi, n uzunluklu bir dizi üzerindeki elemanlardan birer defa geçer ve geriye doğru bir hareketi olmadığından dolayı tek zamanlıdır. O(n)
- Average Case: Worst case ile Best case ortalamasıdır alındığında O(n^2)
## 4.Adım : 18 sayısı tam ortasında olduğundan dolayı ***Average Case***  kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- 1.Adım: [2,3,5,8,7,9,4,15,6] ->7
- 2.Adım: [2,3,4,8,7,9,5,15,6] ->5
- 3.Adım: [2,3,4,5,7,9,8,15,6] ->8
- 4.Adım: [2,3,4,5,6,9,8,15,7] ->7
