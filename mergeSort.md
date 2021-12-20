[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22] 
            [16,21,11,8,12,22]

    [16,21,11]              [8,12,22]                dizisinin elemanlarını tek bir sayıya düşürene kadar ayırma(bölerek gruplama) işlemi yapacağız.

    [16]     [21,11]         [8,12]         [22]

[16]      [21]    [11]     [8]     [12]       [22]    böldükten sonra  sıralama işlemine başlanıyor.

[16]         [11,21]           [8,12]           [22]  bölünen elemanlar yeniden küçük gruplar haline getirilerek sıralanıyor.

    [11,16,21]                          [8,12,22]     2 küçük grup kendi aralarında birleşerek sıralanmaya devam ediyor, 

            [8,11,12,16,21,22]                        bu işlem tek bir grup haline gelene kadar devam ediyor.


                                                      bu sıralama türünde iki grubun ilk elemanları en küçük sayılar oldukları için birbirleriyle karşılaştırılarak işlem kolaylığı elde ediliyoruz


Big-O gösterimini yazınız. 
O(nlogn)
