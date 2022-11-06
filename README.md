# patikaodev01
patika bitirme ödevi: insertion sort

[22,27,16,2,18,6]

1.verilmiş olan dizinin sort türüne göre aşamaları:

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2

[2,6,16,18,22,27] 1

2.big O gösterimi:

n.(n+1):2

n^2+n:2

O(n^2)(dominant karakter n^2)

3.time complexity (worst best average cases):

worst case: aradığımız sayının (2) dizinin sonunda olmasıdır: o(n^2) 

[27,22,18,16,6,2]

best case: aradığımız sayının (2) dizinin başında olmasıdır:o(n)

[2,6,16,18,22,27]

average case: aradığımız sayının (18) dizinin ortasında olmasıdır:o(n^2)

[2,6,16,18,22,27]

4.dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.

5.[7,3,5,8,2,9,4,15,6] dizisinin insertion sorta göre ilk 4 adımı:

[2|3,5,8,7,9,4,15,6]

[2,3|,5,8,7,9,4,15,6]

[2,3,4|8,7,9,5,15,6]

[2,3,4,5|7,9,8,,15,6]

www.patika.dev
