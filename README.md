# Proje 2

[patika.dev](www.patika.dev)

[16,21,11,8,12,22] -> Merge Sort

## 1. Soru

1. [16,21,11,8,12,22]              => ikiye bölünecek
2. [16,21,11] - [8,12,22]          => her bölüm tekrar ikiye bölünecek
3. [16]-[21,11] -- [8]-[12,22]     => her bölüm tekrar ikiye bölünecek
4. [16]-[21]-[11]--[8]-[12]-[22]   => her bölüm tekrar ikiye bölünecek
5. [16]-[11,21]--[8]-[12,22]       => sıralama yapılıyor ve birleştiriliyor
6. [11,16,21]--[8,12,22]           => sıralama yapılıyor ve birleştiriliyor
7. [8,11,12,16,21,22]              => son hali



## 2. Soru

Her bölmede (n-1) sorgulama yapıldığından her bölmenin Time complexity O(n) olacak
Sorunun tüm aşaması için Time complezity O[nlog(n)] olacaktır. 



















