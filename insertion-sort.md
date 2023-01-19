### Insertion Sort ;
[22,27,16,2,18,6]

(en küçük olan sayı seçilir ve en baştakiyle yeri değiştirilir)
- [2,27,16,22,18,6]

- (ikinci en küçük sayıda seçilir ve 2. sırayla yer değiştirir)
- [2,6,16,22,18,27]
- (diğerleri de aynı sırayla küçükten büyüğe doğru yer sıralanır)
- [2,6,16,18,22,27]

- Big-O gösterimi : n+(n-1)+(n-2)+..+.= n*(n+1)/2 
=n^2+n/2
Big O(n^2)

### Selection Sort olarak inceleme;
- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı ;
- [2,3,5,8,7,9,4,15,6] 1.adım
- [2,3,4,8,7,9,5,15,6] 2.adım
- [2,3,4,5,7,9,8,15,6] 3.adım
- [2,3,4,5,6,9,8,15,7] 4.adım
