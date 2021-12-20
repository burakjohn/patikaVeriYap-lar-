[22,27,16,2,18,6] -> Insertion Sort
1. [2,27,16,22,18,6] -> ilk adımda en küçük sayı bulunup listenin başındaki sayıyla yer değişti. 2 ile 22 yer değişti. (n) tane işlem 
2. [2,6,16,22,18,27] -> 27 ile 2. en küçük sayı olan 6 yer değişti, en küçük sayıya bakılmadığı için (n-1) tane işlem
3. [2,6,16,22,18,27] -> 16 3. en küçük sayı olduğu için aynı yerde kaldı (n-2)
4. [2,6,16,18,22,27] -> 18 ile 22 yer değiştirdi (n-3)
5. [2,6,16,18,22,27] -> 22 ile 27 aynı kalır. (n-4)

bigO = (n.n-1)/2 = O(n^2)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı average case 

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- [2,3,5,8,7,9,4,15,6]
 2- [2,3,4,8,7,9,5,15,6]
 3- [2,3,4,5,7,9,8,15,6] 
 4- [2,3,4,5,6,9,8,15,7]