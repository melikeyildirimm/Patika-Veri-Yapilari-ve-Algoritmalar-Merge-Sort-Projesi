# Patika-Veri-Yapilari-ve-Algoritmalar-Merge-Sort-Projesi


[16,21,11,8,12,22] dizinin Merge Sort türüne göre aşamaları:

Tek eleman kalana kadar liste iki parçaya ayrılırak devam edilir:

[16,21,11] , [8,12,22]

[16], [21,11]    ,   [8,12] , [22]

[16],  [21], [11]   , [8] , [12]  ,  [22] 

Daha sonra birbirleiyle kıyaslanarak küçükten büyüğe doğru olacak şekilde sıralı olarak yine gruplar halinde birleştirilir.

[11,16,21]  ,  [8,12,22]

Tekrar aynı işlem uygulanır. Örneğin sırayla 11, 8 ile kıyaslanır; 8 daha küçük olduğu için başa yazılır. Daha sonra 11, 12 ile kıyaslanır; 11 daha küçük olduğu için 11 yazılır. 

Son durumda dizimiz

[8,11,12,16,21,22] olur.

BigO: O(nlogn)
