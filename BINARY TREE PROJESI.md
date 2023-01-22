# BINARY TREE PROJESI 

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

    Binary Search Tree:

    Binary Search Tree, her düğümde anahtar değerlerini saklayan bir veri yapısıdır. Her düğüm solunda küçük anahtar değerleri, sağında ise büyük anahtar değerleri bulunur. Aşağıda verilen dizinin Binary Search Tree oluşturma aşamaları:

1. Root olarak 7 seçilir.
2. 5 eklenir, 5 < 7 olduğu için solunda yer alır.
3.    1 eklenir, 1 < 5 olduğu için solunda yer alır.
4.    8 eklenir, 8 > 7 olduğu için sağında yer alır.
5.    3 eklenir, 3 < 5 olduğu için solunda yer alır.
6.    6 eklenir, 6 > 5 olduğu için sağında yer alır.
7.    0 eklenir, 0 < 1 olduğu için solunda yer alır.
8.    9 eklenir, 9 > 8 olduğu için sağında yer alır.
10.    4 eklenir, 4 > 3 olduğu için sağında yer alır.
11.    2 eklenir, 2 < 4 olduğu için solunda yer alır.

    Bu şekilde oluşan Binary Search Tree'nin yapısı, root düğümü 7 olduğu için 7, solunda 5, sağında 8 olduğu için 5'in solunda 1, sağında 3 olduğu için 1'in solunda 0, sağında 2 olduğu için 3'ün solunda yok, sağında 4 olduğu için 8'in solunda 6, sağında 9 olduğu şeklinde olacaktır.