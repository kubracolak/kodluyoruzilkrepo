# MERGE SORT

- [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    
    Merge Sort ile sıralama işlemi, diziyi bölerek parçalara ayrılır, ardından parçaları tekrar birleştirerek sıralanmış hale getirir. Aşağıda verilen dizinin sıralanması için adım adım aşamaları:

    [16,21,11,8,12,22] dizisi 2'ye bölünür ve [16,21], [11,8,12,22] parçaları oluşur.
    Her bir parça tekrar 2'ye bölünür ve [16], [21], [11,8], [12,22] parçaları oluşur.
    Her bir parça daha küçük parçalara ayrılmaz, çünkü sadece 1 elemanlıdır ve zaten sıralıdır.
    [16], [21] parçaları birleştirilir ve [16,21] oluşur. [11,8], [12,22] parçaları birleştirilir ve [8,11,12,22] oluşur.
    [16,21] ve [8,11,12,22] parçaları birleştirilerek [8,11,12,16,21,22] dizisi oluşur.

- Big-O gösterimini yazınız.

    Merge Sort, dizinin bölünerek sıralanması işlemi O(n log n) zaman karmaşıklığına sahiptir. Bu, dizinin boyutu ne olursa olsun, sıralama işlemi için aynı zaman gerektiği anlamına gelir. Bu yüzden, Merge Sort genellikle büyük boyutlu diziler için tercih edilir.